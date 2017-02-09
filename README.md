# flask-reminders (wip) [public demo](http://app-bb6ec1713db8.demo.ruanbekker.com/)
App with Python Flask, MongoDB and Elasticsearch that I use to to bookmark websites/resources.

## Motivation:

I tend to make a lot of notes and save info from websites quite alot. But after some time I forget where, what was saved. 

So I made this app to have a quick way to save bookmarks, by specifying the title, category, description and url. Adding info was one part of the app, but the functionality that I really needed, was a view where I can see what was added, from a newest to olderst view.

## Services Used:

* MongoDB
* Elasticsearch
* Python Flask
* Marketing Bootstrap

## Planned Features

* Search Functionality ~~(wip)~~ (done)
* URL Generation for User Defined Notes. Instead of using a URL, the ability to create a note and attach the autogenerated link for your note.

## Setup:

```
$ git clone https://github.com/ruanbekker/flask-reminders
$ cd flask-reminders
$ sudo yum install gcc libffi-devel python-devel openssl-devel -y
$ pip install -r requirements.txt
$ python app.py
```

## Screenshots:

**Home:**

![Alt text](/screenshots/screenshot-home.png?raw=true "Home Screen")

**List:**

![Alt text](/screenshots/screenshot-list.png?raw=true "List Screen")

**Add:**

![Alt text](/screenshots/screenshot-add.png?raw=true "Add Screen")

**Search:**

![Alt text](/screenshots/screenshot-search.png?raw=true "Search Screen")

