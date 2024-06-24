# Command

## Linux

### Delete Directory/Files

```rmdir & rm -d``` command is for removing empty directories

```rm -r``` for deletes non-empty directories


## Windows

### Change CMD color

For example,

```set PROMPT=$E[1;37m[user@machine:$E[1;35m$P ]$$ $E[1;37m```

<b>Produces:</b>

![image](https://github.com/AdaniKamal/Command/assets/44063862/1ff3c231-ac45-4619-ad52-65e35f521f5a)

The format for the colors is:

```$E[bold_or_not;colorm```

With m always following the color number. bold_or_not = 0 or 1. Here's a guide for the colors:

| No | Attributes|
| ------------- | ------------- |
| 0 | Turn Off Attributes|
| 1 | High Intensity|
| 2 |  Normal Intensity|
| 4 | Underline (mono only)|
| 5 | Blink|
| 7 | Reverse Video|
| 8 | Invisible|
| 30 | Black|
| 31 |  Red|
| 32 | Green|
| 33 | Yellow|
| 34 | Blue|
| 35 | Magenta|
| 36 | Cyan|
| 37 | White|
| 40 | Black|
| 41 | Red|
| 42 | Green|
| 43 | Yellow|
| 44 | Blue|
| 45 | Magenta|
| 46 | Cyan|
| 47 | White|



