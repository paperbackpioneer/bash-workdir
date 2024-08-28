# BASH-WORKDIR

This is a simple script that I created to make my life a little
easier. I'm sharing with you, so your life becomes easier as
well.

Imagine this: you're working from the terminal on a project
located at `~/Documents/My Project`. This is where you'll spend
most of your day.

But, every now and then, you have to jump to another place, like
the Downloads directory, or somewhere else. Or, you must open a
new terminal window or a new tab on `tmux`, and suddenly, you
find yourself in a default directory like `$HOME`.

Now, you have to type the address of your project directory to
get there and resume your work. If you're like me, this address
will probably be huge.

This script automates this.

When in your working directory, simply type:

``` bash
workdir
```

And, now, this is your working directory.

If you end up somewhere else, and need to jump there quickly,
type:

``` bash
gotowork
```

And bam! You're back at your work directory.

Import to your `bashrc` with the following line:

``` bash
. path/to/bash-workdir
```

Don't forget to change the path to the location of your
`bash-workdir` file.

Then, while in the terminal, type:

``` bash
source ~/.bashrc
```

(Or whatever is your config file)

That's it.

:)
