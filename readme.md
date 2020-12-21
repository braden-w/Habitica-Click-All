# Habitica Click All/Click One Dailies

A bookmarklet that clicks all Habitica dailies (and another that clicks the first one). Perfect for when you have missed a streak and wish to click all dailies without moving your mouse.

![Picture of Habitica Dailies](https://i.redd.it/hhn82toopr531.png)
Clicking the bookmarklet would complete the final incomplete daily.

## Installation

Install as a bookmarklet using directions [here](https://mreidsma.github.io/bookmarklets/installing.html).

To install Click All, copy and paste the following code as a bookmarklet:
```
javascript:document.querySelectorAll('.task-best-control-inner-daily-todo').forEach(div => {div.click();});
```

To install Click One, copy and paste the following code as a bookmarklet:
```
javascript: document.querySelector('.task-best-control-inner-daily-todo').click();
```

## Usage

To use, simply click on the bookmark.

Click All: Will click all incomplete dailies.
Click One: Will click the first incomplete daily. 
