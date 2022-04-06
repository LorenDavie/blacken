# blacken
Shortcut to run [black](https://github.com/psf/black) on all modified python files in your git working directory.

# Installation

Download the black shell script, copy into your path somewhere (I like using `/usr/local/bin` on my Mac).

# Usage

From the root of your git working directory:

`blacken`

Will run `black` on any modified files.

# Known limitations

Will not work on newly added files, only modified files.  Patches welcome.
