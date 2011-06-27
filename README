pyline
======

`pyline` is a Python 3 program that enables you run a Python expression
on every line of standard input.

Usage
=====

`pyline` is meant to be used after a UNIX pipe. However, since it reads
its input from stdin, it can also be run interactively.

For example, say I want to get the battery percentage from acpi and not
the entire message, I could do:

    $ acpi
    Battery 0: Discharging, 85%, 06:43:32 remaining
    $ acpi | pyline "s('\d+%', L)"
    85%
