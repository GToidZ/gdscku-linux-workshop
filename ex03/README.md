# Crunching Numbers

Note: You'd need to use the `REFERNCE` file to get the letter.

```
To get the letter three,
LINENO (line number) indicates where in README,
its not the contents will tell,
rather the size it held,
however it's not in here,
perhaps go up once, I fear,
count the characters that present,
you'll know more where this is sent.
```

## Getting certain lines in a file

The command shall be used are `head` and `tail`.

The following command gets two first lines in the file.
```sh
head -n2 README.md
```

The following command gets two last lines in the file.
```sh
tail -n2 README.md
```

## Counting lines, words and characters

The command to count lines, words and characters is `wc`.

The following command counts characters in the file.
```sh
wc -c README.md
```

## Pipelining the output

Linux can take outputs from previous commands and process them with later commands using the pipe operator (`|`).

For example, you can chain output from `echo` to do `wc`,
```sh
echo "Hello, world!" | wc
```

With this you can also get the specific point in file,
```sh
# Assuming that this file has 50 lines, you are getting line 30-35.
tail -n20 README.md | head -n5
```