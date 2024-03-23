---
title: "How to Create Virtual Environments in Python for Windows, Mac, and Linux"
seoTitle: "create python virtual environment"
seoDescription: "How to create Python virtual environment in Windows, Mac, and Linux."
datePublished: Thu Feb 16 2023 09:25:23 GMT+0000 (Coordinated Universal Time)
cuid: cllqr1wd700wielnvb1p6f9sc
slug: how-to-create-virtual-environments-in-python-for-windows-mac-and-linux
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1692977431394/3f6a2068-5dec-40d8-b8fa-c302d21a00a1.jpeg

---

## Introduction

Creating virtual environments in Python can be an important part of your development process, providing a safe and isolated workspace for your project. In this blog post, we’ll discuss how to create virtual environments for Python on Windows, Mac, and Linux. We'll also provide step-by-step tutorials with command line codes for each as well to serve as aids.

## Creating a Virtual Environment in Python on Windows

Python’s virtual environments provide a way to separate different projects and their dependencies from each other. This can be especially useful when working with different versions of the same libraries, or when you want to experiment with a project without making changes to your main Python installation.

Creating a virtual environment in Python on Windows is fairly straightforward. First, open the command line window by typing `cmd` into the Windows search bar. Then, navigate to the directory where you want to create the virtual environment, typically the same directory as your project. Once you’re in the desired directory, type `python -m venv env` to create the virtual environment within the `env` folder.

The next step is to activate the virtual environment, which you can do with the command `env\\Scripts\\activate`. Once you’ve activated the virtual environment, you’ll notice that the prompt has changed to include the name of the active environment in parentheses, like this: `(env) C:\\path\\to\\project>`.

Finally, you can install packages within the virtual environment as you normally would. To deactivate the environment, simply type `deactivate`.

Creating a virtual environment in Python on Windows is a great way to keep your projects separate and organized. It also ensures that you can use different versions of packages for different projects without any conflicts.

## Creating a Virtual Environment in Python on Mac

A virtual environment is a great tool for managing different versions of Python and their dependencies. It allows you to create isolated environments for each of your projects. This article will cover how to create a virtual environment in Python on Mac.

### Command Line

To create a virtual environment in Python on Mac, you'll need to use the command line. First, use the `cd` command to navigate to the directory where you want to store your virtual environment.

Next, use the `python3 -m venv [name of your environment]` command to create your virtual environment. Replace `[name of your environment]` with a name of your choice.

Finally, activate your virtual environment using the `source [name of your environment]/bin/activate` command.

## Creating a Virtual Environment in Python on Linux

Creating a virtual environment in Python on Linux is a great way to keep your development environment organized and secure. By creating virtual environments, you can keep your different projects and their dependencies separate from each other.

To create a virtual environment on Linux, the command is:

```bash
python3 -m venv <name of the environment>
```

This command will create a directory with the specified name in the current working directory. Inside this directory will be the Python installation that will be used when the virtual environment is activated.

Once the virtual environment has been created, you can activate it with the following command:

```bash
source <name of the environment>/bin/activate
```

Once the environment has been activated, you can start installing the packages you need for your project. To deactivate the virtual environment, simply type:

```bash
deactivate
```

Creating and managing virtual environments in Python on Linux is a great way to keep your development environment organized and secure. With the help of virtual environments, you can keep your different projects and their dependencies separate from each other.

## Conclusion

Creating virtual environments in Python can provide a safe and isolated workspace for your project. It's easy to set up virtual environments in Python on Windows, Mac, and Linux, and this blog post has provided step-by-step tutorials with command line codes to help you do so.