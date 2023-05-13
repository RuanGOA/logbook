# Log Book

According to the definitions by Oxford Languages, a log book is an official record of events during the voyage of a ship or aircraft. This simple application will help you manage your daily voyage logs. 😄

## Installation & Configuration

1. Clone this git repository.

2. Navigate to the logbook directory and run `make install`.

Once installed, you can use the `logb` command to start logging.

By default, the log book uses your default text editor. If you don't have one set, `vim` will be used. If you want to use a specific text editor, you can set it by adding the following line to your `.*rc` file: `export $EDITOR=nameOfYourFavoriteEditor`.

## Usage

When you execute `logb`, a new file will be created with the current date as its name. You can start logging using your text editor.

If you need to search for specific text in all of your log files, you can use the `logb find text` command. It will display the files that contain matching words.

To open and read a specific log, use the `logb open logDate` command.
