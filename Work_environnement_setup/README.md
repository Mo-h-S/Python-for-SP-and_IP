# Python for TS and TI

## What is Python?
Python is a versatile programming language created by Guido van Rossum. It is known for its clear syntax and ease of use, making it a popular choice for both beginners and professionals.

## Users of Python
Python is used in various fields, including:
* Software Development
* Data Science
* System Administration
* Web Development
* Academic Research

Companies like Netflix, Spotify, and NASA use Python for various applications.

## Advantages of Python
* Easy to learn
* Extensive libraries
* Cross-platform
* Strong community support

## Versions of Python
Python has two main versions you may encounter when installing the language:

### Python 2.x
This is the older version of Python, with the last release being Python 2.7.18. Although Python 2.x is still used in some legacy applications, it reached its end-of-life in January 2020. This means no updates or bug fixes will be provided anymore. Therefore, it is strongly recommended to use Python 3.x for new projects.

### Python 3.x
This is the current and actively maintained version of Python, with continuous updates and improvements. Python 3.x has brought many enhancements and changes to the language, making it more efficient and powerful. It is the recommended version for all new projects and installations.

## How to Install Python
We will now guide you through the process of installing the latest version of Python on your operating system.

## Prerequisites for Installation
* Basic computer knowledge
* Familiarity with the command line
* Computer with internet connection
* Compatible operating system (Windows 7+, macOS 10.9+, or Linux)
* At least 4 GB of RAM and 5 GB of disk space

## Two Choices for Installing Python on Your System

### Installing Python on Different Systems and an IDLE
Download the installer from the official Python website:

| System  | Link  |
| :-------  | :-------  |
| Windows  | https://www.python.org/downloads/windows/  |
| Ubuntu | https://www.python.org/downloads/source/  |
| MacOS | https://www.python.org/downloads/macos/  |

Run the installer
Customize the installation (optional)
Start the installation
Verify the installation via the command `python --version`

An alternative is to install Python via the Microsoft Store.

### IDLE: Integrated Development Environment
IDLE (Integrated Development and Learning Environment) is the integrated development environment for Python, designed to facilitate learning and development. It is fully written in Python and works on multiple platforms, including Windows, Unix, and macOS.

#### Main Features
* **Interactive Console**: Allows you to execute Python code line by line with syntax highlighting for better readability.
* **Text Editor**: Offers advanced features like auto-completion, automatic indentation, and error management.
* **Debugging Tools**: Includes options to set breakpoints and inspect variables.
* **File Management**: Facilitates creating, opening, and saving Python scripts.
* **Integrated Documentation**: Direct access to Python documentation to help users understand features.

IDLE is particularly suitable for beginners due to its intuitive interface but may be limited for more complex projects where other IDEs like VSCode or PyCharm might be more appropriate.

## Simplifying Life by Installing Anaconda for All Packages

### Installing Python with Anaconda
Anaconda is a free and easy-to-install software distribution for Python and R that includes a vast collection of over 7,500 open-source packages (including R). When installing Anaconda, over 250 packages are automatically installed alongside Python.

### Installing Anaconda on Different Systems
Download the installer from the official Anaconda website:

| System  | Link  |
| :-------  | :-------  |
| Windows  | https://repo.anaconda.com/archive/Anaconda3-2024.10-1-Windows-x86_64.exe  |
| Ubuntu | https://repo.anaconda.com/archive/Anaconda3-2024.10-1-Linux-x86_64.sh  |
| MacOS | https://repo.anaconda.com/archive/Anaconda3-2024.10-1-MacOSX-arm64.pkg  |

Open Anaconda Navigator: Launch Anaconda Navigator from your operating system's menu or using the terminal with the command `anaconda-navigator`.

Launch Spyder: In Anaconda Navigator, click on the Spyder icon to open it. You can also launch Spyder directly from the terminal (anaconda prompt) by typing `spyder`.

And there you go!

To check the version of Python, type in the terminal:
```bash
python --version
```

If everything is in order, you do not need to do anything else. However, if you want to separate your projects and work with distinct environments while only installing necessary libraries for each project, it is essential to set up a virtual environment (See section on Configuring a Virtual Environment).

Now that everything is set up, there’s just one last step.

## Configuring Spyder

### Configuring Graphical Output
1. Open Spyder.
2. Go to the **Tools** menu.
3. Select **Preferences**.
4. In the preferences window, go to **IPython console > Graphics** (Choose graphics) and configure graphical output as needed (for example, choose between inline output or a new window).

### Clearing Variables Before Execution
1. Go to **IPython Console > Execution**.
2. Check the option to **Clear all variables before starting execution**.

### Configuring Help in Preferences
1. Go to **Help**.
2. Here you can configure how you want help displayed (for example, inline, in a separate window, etc.).
3. Check all boxes.

### Automatic Indentation
1. Go to **Preferences**.
2. Under **Editor > Indentation**, you can configure automatic indentation. You can choose between tabs or spaces and set the number of spaces per indentation level.

#### To comply with PEP8:
* Select **Use spaces instead of tabs** since PEP8 recommends using 4 spaces for each level of indentation.
* Set the number of spaces per indentation level to 4.

If you've made it this far, congratulations! Your working environment is now configured.

## Getting Started
1. **Configure your project**: Once Spyder is open, go to the "Projects" menu and create a new project.
   - Name your project and choose a directory to store it.
2. **Write and execute code**: Use Spyder's text editor to write your Python code.
   - For example, you can write a simple script like `print("Hello, World!")`.
   - To execute the script, click on the "Run" button in the toolbar or use the keyboard shortcut `Ctrl + Enter`.
3. **Explore variables**: Use the Variable Explorer to see your variable values during program execution.
   - You can find this tool in the "Variables" tab on the right side of the interface.
4. **Access documentation**: To get documentation for a function or module, simply hover over its name and press `F11`.

## Configuring a Virtual Environment

Virtual environments are valuable tools that allow managing multiple distinct Python installations. This is particularly useful when working on multiple Python projects simultaneously. Instead of maintaining a single cluttered installation with all imaginable packages, virtual environments ensure each project has its own clean space with only necessary tools.

To set up your first virtual environment, open Terminal on macOS or Anaconda Prompt on Windows. Then create a new virtual environment with the following command:

```bash
conda create --name Lab1 python=3.4
```

Here, the `--name` parameter specifies the name of the virtual environment; in this case, "Lab1". The `python=3.4` parameter is optional but indicates that this virtual environment should use version 3.4.x of Python, ensuring everyone uses the same version.

Conda may install some packages while asking for confirmation before proceeding. Once installation is complete, activate your conda environment by typing `conda activate Lab1` on macOS or `activate Lab1` on Windows. Your command prompt should now display the name of your environment in brackets before the command line like this:

```text
(Lab1) ➜  ~
```

This confirms that you are now in the environment you just created and that all Python packages you install will remain within this sandbox. Next, let’s install some basic tools:
bash
conda install numpy jupyter pip matplotlib

You can list as many package names as needed after install, and conda will install them all at once. Again, it may ask for confirmation before installing packages you don’t already have.
To access this environment type:
```bash
conda activate ./envs
```

You can deactivate your environment at any time using conda deactivate on macOS or simply deactivate on Windows.

```bash
conda deactivate ./envs
``` 
For more information check this link: https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html


## Feedback

If you have any feedback, please reach out to us.

## Sources 

https://www.anaconda.com/download/success

https://www.python.org/downloads/