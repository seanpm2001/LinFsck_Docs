
***

<!-- <img src="/Logo.png" width="148" height="148" align="left" style="margin-right: 30px"> !-->

# [LinFsck](https://github.com/seanpm2001/LinFsck/) Docs

This is the official documentation repository for [:octocat: `LinFsck`](https://github.com/seanpm2001/LinFsck/). It is highly incomplete.

- [`Click/tap here to see more LinFsck documentation trunk`](/Docs/)

A little amount of starter documentation is in the current file, the [`/Docs/`](/Docs/) trunk contains far more information.

***

## Original project draft (circa 2023 April)

LinFsck

Alternative names

Motherfscker

Write in: C, Shell

A training simulator for using dangerous Linux commands, especially fsck, in a controlled environment

Inspiration: I had to run the fsck command manually, as one of my partitions randomly got corrupted during normal usage, and I was dropped into BusyBox upon each boot. It was a good learning experience, and it felt empowering to utilize the fsck command. I wanted to create a simulator that can simulate problems like these to give new/inexperienced Linux users (like myself) the opportunity to play with fire without messing up their machines, and learn how to troubleshoot these problems better.

2 program modes:

Virtual machine

Programmed

Virtual machine mode is what its title says: it is a small virtual machine hypervisor that is locked into several scenarios for demonstrating commands like fsck.
Programmed mode is what its title says: it is a programmed simulation (program) that does not rely on virtual machines. It is good for users who don't want to use tons of memory.

Some scenarios:

Vanilla: Just a normal day on Linux

{ Difficulty levels: 1, 2, 3, 4, 5 }

Various sub-scenarios

Corrupted partition: Run fsck to save the day

{ Difficulty levels: 1, 2, 3, 4, 5 }

Various sub-scenarios

Lotsa users: Use chmod and other commands to manage lots of users

{ Difficulty levels: 1, 2, 3, 4, 5 }

Various sub-scenarios

Virtual machines:

Plan9

Early Linux distributions (light)


***

**File version:** `1 (2023, Tuesday, May 9th at 3:48 pm PST)`

***
