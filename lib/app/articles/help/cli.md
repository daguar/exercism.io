## Downloading the CLI

You access the exercises via the command line.

The command-line interface (CLI) is a stand-alone binary, and you can install it without installing any particular programming language or environment.

## Installing the CLI

On Mac OS X or Linux you can install the CLI with the following command [view source](http://cli.exercism.io/install):

```bash
$ curl http://cli.exercism.io/install | sh
```

Or, download the [latest release](github.com/exercism/cli/releases/latest) for your operating system and architecture (32-bit or 64-bit), and place the binary [in your PATH](/v1.0/help/path).

To determine your processor architecture, try `uname -m`.

If you're on Windows, get the [latest release](github.com/exercism/cli/releases/latest). To unpack the `.tgz` file you will need a tool like `gzip`, `GNU tar`, or the [universal extractor "uniextract"](http://legroom.net/software/uniextract)". It seems like neither `jzip` or `7-zip` work.

The extracted binary is named `exercism.exe`.

Put the binary in your PATH, or run it by calling the full path to the program: `C:\path\to\exercism\project\exercism.exe`.

If you get stuck, post <a href="https://github.com/exercism/exercism.io/issues/new">an issue</a> so that we can figure out what's confusing, help you out, and then update this text so that the next person doesn't get stuck.
