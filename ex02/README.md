# Good Luck Finding

You have a pile of files lying around, and one file in the pile seems to be an answer.

The way to find truly non-empty file is to use the `find` command.

## Finding things expressively

If you take a look at `find` command manpage, you can see that we can set options to find things in our system easily.

Here are the sample options that we can use:

* `-type f` Only search for files
* `-type d` Only search for directories
* `-size +1M` Only search for files with size more than 1MB.
* `-empty` Only search for files that are empty
* `-not` Reverses preconditions

It is recommended to see manpage of `find`. (`man find`)

## Clearing the screen

You can clear Linux terminal screen by running `clear`.

Or you can try to push your terminal screen to clear one with CTRL+L.
