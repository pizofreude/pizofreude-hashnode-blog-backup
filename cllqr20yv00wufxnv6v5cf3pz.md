---
title: "How to Start Any Program in Terminal"
seoTitle: "start program in terminal"
seoDescription: "How to start any program in terminal"
datePublished: Sun Jan 29 2023 09:21:27 GMT+0000 (Coordinated Universal Time)
cuid: cllqr20yv00wufxnv6v5cf3pz
slug: how-to-start-any-program-in-terminal
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1692977437519/76c8b1a3-65ba-4498-ab2a-aa81d36e209b.jpeg

---

### TL;DR

Terminal is a command line interface that allows users to enter commands and execute them. To start any program in Terminal, you need to understand the basics of how it works and the commands that you can use. Windows, Mac and Linux users can access Terminal via their respective operating systems. To start a program, enter the command found in the program's documentation or search engine. Troubleshooting can be done with the help of the appropriate documentation. To stop a program, use the command "kill" in Windows, Mac and Linux.

## Introduction

Terminal is a powerful tool that allows users to access the command line interface of their computer. It can be used to run a variety of programs, and this guide will show you how to get the most out of Terminal and start any program you need.

## Understanding Terminal

Terminal is a command line interface that allows users to enter commands and execute them. It is the most basic way to interact with your computer, as it allows you to run programs and access system settings. To use Terminal, you will need to understand the basics of how it works and the commands that you can use.

## Setting Up Terminal

For advance user, most probably you already customize the setup of your favorite Terminal. This involves configuring the environment, setting up the directory structure, and adding any custom commands that you may need. Hooray for you!

For beginners out there that don’t want the hassle of installing a new Terminal, simply use your default Terminal:

### Windows

Windows users can access Terminal by navigating to Start &gt; All Programs &gt; Accessories &gt; Command Prompt.

### Mac

Mac users can access Terminal by navigating to Applications &gt; Utilities &gt; Terminal.

### Linux

Linux users can access Terminal by navigating to Applications &gt; System Tools &gt; Terminal.

## Starting a Program

If you don’t want to mess around with the system environment variables for all your installed programs, the this is the way to go.

Once you have your favourite Terminal from plethora of choices set up correctly, you can start any program you need. To do this, you will need to enter the command to start the program. This command can be found in the program's documentation, or you can use a search engine such as Google to look it up.

## Troubleshooting

If you encounter any errors when trying to start a program, it may be due to a number of different issues. If this happens, you can use the Terminal to troubleshoot the problem and find out what went wrong. The following might be a good starting point of your troubleshooting guide:

### Windows

[https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/start](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/start)

[https://learn.microsoft.com/en-us/troubleshoot/windows-server/welcome-windows-server](https://learn.microsoft.com/en-us/troubleshoot/windows-server/welcome-windows-server)

### Mac

[https://support.apple.com/en-us/HT204244](https://support.apple.com/en-us/HT204244)

[https://support.apple.com/en-us/HT201372](https://support.apple.com/en-us/HT201372)

### Linux OpenSUSE

[https://doc.opensuse.org/documentation/leap/reference/html/book.opensuse.reference/cha.basics.startstop.html](https://doc.opensuse.org/documentation/leap/reference/html/book.opensuse.reference/cha.basics.startstop.html)

[https://doc.opensuse.org/documentation/leap/reference/html/book.opensuse.reference/cha.troubleshooting.html](https://doc.opensuse.org/documentation/leap/reference/html/book.opensuse.reference/cha.troubleshooting.html)

## Find the Program Executable Filename

The first step is to find the program or software you want to start in Terminal. You can do this by searching for the program in your computer's search bar or by navigating to the program's installation folder. Alternatively for Windows user, you can hover over the program shortcut, right-click, and select “Open file location”.

### Extensions for Executable Filenames

Windows: .exe Mac: .app Linux: .sh or .bin

## Start the Program

Once you've found the program, you can start it in Terminal by entering the command e.g. for Mac "open \[program name\]" into the Terminal window. This will open the program in the same way it would open if you clicked on it in your computer's file browser. Here’s the list of the command for Windows PC, Mac and Linux:

### Windows

To start a program in Terminal on Windows, use the command:

```bash
 start [program name]
```

To start a program in detached mode in Terminal on Windows, use the command:

```bash
 start /b [program name]
```

This will start the program in the background without opening a new window. Alternatively, you can also use the command:

```bash
 start [program name] -d
```

### Mac

To start a program in Terminal on Mac, use the command:

```bash
 open [program name]
```

To start a program in detached mode in Terminal on Mac, use the command:

```bash
 nohup open [program name] &
```

This will start the program in the background without opening a new window.

### Linux

To start a program in Terminal on Linux, use the command:

```bash
  ./[program name]
```

To start a program in detached mode in Terminal on Linux, use the command:

```bash
 nohup ./[program name] &
```

This will start the program in the background without opening a new window.

## Stop the Program

Terminal can also be used to stop programs. To stop a single program, in Windows use the command:

```bash
 kill [program name]
```

In Mac:

```bash
 killall [program name]
```

Or in Linux:

```bash
 kill [program name]
```

To stop all programs from the Terminal, use the following commands:

* In Windows:
    

```bash
  killall
```

* In Mac:
    

```bash
 killall -9
```

* In Linux:
    

```bash
 killall -9 -v
```

## Conclusion

Starting a program or software in Terminal is a useful tool for accessing and manipulating your computer's operating system. It's a powerful tool, and you can use it to start any program or software on your computer. With a few simple steps, you can start and stop any program or software from Terminal. Hopefully, you have gained knowledge from this guide on how to use Terminal to its fullest potential.