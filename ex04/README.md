# The Passcode Is...

In this task, you'll need to modify the answer of `answer.txt` to something else, and run the given binary, `send-answer`.

## Modifying file contents

There are many text editors in Linux, it is up to you to choose which one fits your usage.

For example, most Ubuntu installations come packaged with `nano` which is a beginner-friendly text editor.

```sh
nano answer.txt
```

In order to save and exit in `nano`, you'll need to Write-out (CTRL+O) then Exit (CTRL+X).

Or if `vi` is more of your taste, you can also use it.

## Changing file permissions

In Linux, in order to read, write or even execute files, you need to set the correct permissions for a file.

We can use `chmod` to change permissions of file. In this case, we want `send-answer` to be executable so,

```sh
chmod +x ./send-answer
```

## Hint for the answer

Our university name, lowercase, no university in name.
