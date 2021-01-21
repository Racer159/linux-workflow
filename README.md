# Linux Workflow Introduction

## So what is this repository?

This repository serves as a very basic introduction to the `Linux` operating system, and what differentiates `Linux` from other common operating systems.  While this should be a good introduction to the concept of Linux it really is only the beginning, with the topic stretching very deep and wide due to all of the applications `Linux` can find itself used for.

## First, what is an "operating system"?

Well, an operating system is pretty much exactly what it sounds like, it's a system that helps you operate your computer.  Below is the textbook definition courtesy of [Merriam-Webster](https://www.merriam-webster.com/dictionary/operating%20system):

```yaml
operating system (noun): software that controls the operation of a computer and directs
the processing of programs (as by assigning storage space in memory and controlling input
and output functions)
```

What that basically means is that the operating system on your computer is the traffic cop that controls how the applications that you run on top of the operating system are allowed to interact with your hardware.  The core part that makes an "operating system" an "operating system" is the `kernel` which along with `drivers` and `kernel modules` is responsible for interacting with system hardware and doling out resources to each application you'd like to run.  Each OS has their own bespoke `kernel` with `Windows` currently utilizing the [NT Kernel](https://en.wikipedia.org/wiki/Architecture_of_Windows_NT), and `Linux` using the obviously named [Linux Kernel](https://www.kernel.org/).  Below is a diagram from [Wikimedia](https://en.wikipedia.org/wiki/Kernel_(operating_system)#/media/File:Kernel_Layout.svg) showing the relationship the `kernel` plays:

![Kernel Layout](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8f/Kernel_Layout.svg/1920px-Kernel_Layout.svg.png)

## Thats cool... But why `Linux` or the `Linux Kernel`?

The main concept that really separates `Linux` from other operating systems like `Windows` is the way in which it and a lot of its software is [built](https://www.youtube.com/watch?v=yVpbFMhOAwE) and [licensed](https://www.gnu.org/licenses/gpl-3.0.en.html).  `Linux` is a collaborative, free ([as in freedom](https://www.youtube.com/watch?v=NB8mCcLRxlg)) software project that allows anyone to view and contribute code, and that provides it and its code freely to anyone who wants it.  "Free as in freedom" means that the software isn't just provided free of charge, but that you, as the user, have the express right to dig deep into the system and modify whatever you want for your own purposes.  This creates a ton of new possibilities and potential from driving [innovation](https://framatube.org/videos/watch/43af45ec-d99a-4e36-a084-e8e1ce28dee8) to enhancing [security and privacy](https://framatube.org/videos/watch/99069c5c-5a00-489e-97cb-fd5cc76de77c).

On top of this core benefit, `Linux` also follows in the footsteps of `Unix` which has a particular philosophy that can be useful for various applications. Mike Gancarz summarized this philosophy in 1994 as the following 9 principles:

```yaml
1. Small is beautiful.
2. Make each program do one thing well.
3. Build a prototype as soon as possible.
4. Choose portability over efficiency.
5. Store data in flat text files.
6. Use software leverage to your advantage.
7. Use shell scripts to increase leverage and portability.
8. Avoid captive user interfaces.
9. Make every program a filter.
```

Below is a summary of what these principles mean when excercised in practice:

```yaml
1. Smaller programs are easier to download, install, run, and understand
2. A program that does one thing can be more easily polished to do it well
3. Building a prototype quickly allows for more experimentation and feedback
4. Choosing portability allows your program to be used by a larger audience
5. Storing data in flat text makes it easier for other programs to use that data
6. Using other peoples code (and offering your code to be used) allows work to build and not be siloed
7. Shell scripts are easy for people to open, modify and understand and will run on any system
8. Capturing the user in an interface breaks their flow and makes it harder for them to use
9. Making every program a filter allows simple, small programs to be chained together to accomplish complex tasks
```

Once you dig into `Linux` you will see these principles in action everywhere throughout the system. From the way `cat`, `grep`, `sed` and `more` function to the way that devices are handled as interrogatable files under`/dev`.

## Getting Started with `Linux`

There are many wayts to get started with Linux today, but one of the easier ways is to spin up a distribution of `Linux` like `Ubuntu` in a `Virtual Machine` like one provided by `VirtualBox`.  A good tutorial on how to do this can be found [here](https://www.makeuseof.com/install-ubuntu-virtualbox/)
