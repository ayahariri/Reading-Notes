## Text Editor Reading Notes

### What is a Text Editor

It is one of the most important tools for a software developer. Text Editor is part of a software that you download and install on your computer that will allow you to compose and manage your content.

### What are the most important features in a text editor

The most important features one must pay attention to are the following:

1. code completion;
2. syntax highlighting;
3. wide range of themes;
4. having a reasonable amount of extensions.

#### Other important features

Another great feature that we will come accross with is the code completion which will allow you to start typing, and the code completion
feature will display possible suggestions based on what you originally typed. This saves you time by providing a choice, rather than allowing
you to finish typing and possibly encounter typos. You must always make sure that everything is written properly and making sure all tags, brackets, quotation marks are opened and closed in an efficient way.

Being able to write your HTML and CSS more efficiently is also a feature it provides. A shorthand language called Emmet will speed up your code writing faster than the usual.

Another feature is the syntax highlighting, which is a feature that takes the text you type, and makes it more pleasing and easy to read by adding color to the text.

### Third Party options

There are numerous third-party options that one can use such as:
- Notepad++,
- Text Wrangler,
- BB Edit,
- Visual Studio Code,
- Atom,
- Brackets,
- Sublime Text.


## THE COMMAND LINE

A command line, or terminal, is a text based interface to the system. So basically, you will type and enter whatever command you would want, and you will recieve an answer back based on the command you typed.

Here is an example of a command:

1. user@bash: ls -l /home/ryan
2. total 3
3. drwxr-xr-x 2 ryan users 4096 Mar 23 13:34 bin
4. drwxr-xr-x 18 ryan users 4096 Feb 17 09:12 Documents
5. drwxr-xr-x 2 ryan users 4096 May 05 17:25 public_html
6. user@bash:

To summarize the command line created above;
- The first line presents a prompt(user@bash). After that we entered a command (ls).
A command is usually always the first thing to type in order to give an order to whatever is written next. Typically a command is always the first thing you type.
- Lines 2 - 5 are in other words the answer from running the command. Most commands produce output and it will be listed straight under the issuing of the command.
- The last line presents us with a prompt again. After the command has run and the terminal is ready for you to enter another command the prompt will be displayed. If no prompt is displayed then the command may still be running (you will learn later how to deal with this).

### The Terminal

The Terminal on a Mac is different from windows/Linux;

- Applications to Utilities.
An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up. **Mac**
- Applications to System or Applications -> Utilities.
Alternatively you may be able to 'right-click' on the desktop and there may be an option 'Open in terminal'. **Linus**

## THE BASIC NAVIGATION

#### 1. The PWD 

Which stands for Print Working Directory tells you what your current or present working directory is.

#### 2. The LS

This command is in charge of showcasing a list for whatever is followed by this command.
If the square brackets ( [ ] ) appear,it means that those items are optional.

### 3. The CD

This command is used to move around in the system which stands for change directory. cd [location]

### What are the differences between the Absolute and Relative Paths?

Whenever we refer to a file or directory we are using one of these paths.
Whenever we refer to a file or directory, we can, in fact, use either type of path (either way, the system will still be directed to the same location).

- Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )
- Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.

### Some Shortcuts

- ~ (tilde) - This is a shortcut for your home directory.
- . (dot) - This is a reference to your current directory.
- .. (dotdot)- This is a reference to the parent directory.

**file**

- obtain information about what type of file a file or directory is.

**ls -a**

- List the contents of a directory, including hidden files.

*Everything is a file under Linux, such as directories.*
Linux is an extensionless system. Files can have any extension they like or none at all.

You can find more details on the following link : [moreaboutfiles](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)
You can also find my web page on the following link : [TextEditorReadme](https://ayahariri.github.io/TextEditor/)
