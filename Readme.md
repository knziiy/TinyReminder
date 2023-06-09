# Tiny Reminder

<div align="left">
  <img src="static/icon.iconset/icon_128x128.png">
</div>

Tiny Reminder is an Electron-based reminder app.

It stores reminder data in the local machine's Local Storage.

## Features
It's a simple reminder.  
You can register a reminder by entering the task content in the task registration field and pressing Enter.  
At that time, it automatically reads and sets the date and time from the text.

For example, if the current time is 2023/03/20 10:00, entering "Tasks Title 0401" will automatically set the date and time field to "2023/04/01 00:00".

Entering "Task Title 10:30" will set it to "2023/03/20 10:30".

And when the set time for a task arrives, a desktop notification will be sent.

I wanted to bring back the behavior of Apple's past reminders.

<div align="center">
  <img src="static/tiny-reminder-movie.gif">
</div>


## Install

You can obtain the pre-built .app file from the [Release page](https://github.com/knziiy/TinyReminder/releases). 


## Build

```bash
npm i
npm run make
```

## Author & License

* knziiy
* License:  
  MIT (see LICENSE)
