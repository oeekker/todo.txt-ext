# About

Thunderbird extension for the Todo.txt application. This extension tries to integrate the [Todo.txt](http://todotxt.com/) application with Thunderbird. Using the Lightning extension it is now possible to add, delete or modify todo's directly within Thunderbird.

## Functionality

* Add, delete or modify Todo's from within your Thunderbird
* Automatically use Thunderbirds functions from Todo.txt, such as categories and priorities.
* Get a quick overview of all your tasks.
* Search for complete and incomplete Todo's within Thunderbird using search paramaters such as Contexts or Projects.
* Use Todo.txt's syntax directly within Thunderbird.

# Usage

The extension requires the following options:

1. Location of your Todo.txt file
2. Location of your Done.txt file

After this configuration it is possible to see every finished and incomplete tasks and add, delete or modify them accordingly. 

**Todo.txt works best with a synchronisation application such as Dropbox or Owncloud, in order to prevent accidental overwriting of the file it might be useful to set the refresh time of the calendar to a couple of minutes**

## Syntax

The extension can automatically assign the appropriate properties to a Thunderbird task based on the Todo.txt syntax. This means that when a user enters a new Task with Todo.txt syntax it will result in a correct Thunderbird task.

For example:
`(A) foobar +Dev +Home @PR`

Entered as a new task within Thunderbird, it will automatically have the following properties:
* High priority
* Categories set to DEV & Home
* Title containing *foobar @PR*

Offcourse the Todo.txt file will contain the exact line as entered into Thunderbird.

# Thanks

This project was made possible of the following projects:

* This extension relies heavily on the [todo-txt-js](https://github.com/roufamatic/todo-txt-js) JavaScript library.
* Much of the code was inspired on the [StormCows](https://github.com/moldybeats/stormcows) extension.
