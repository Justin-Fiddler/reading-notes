# The Coder's Computer

## Choosing a Text Editor

### It is important to remember a few things when choosing a text editor

- They are all pretty much the same with some having a few different bells and whistles.
- Whichever you like to use and get the job done, is just fine.

### The Most Important Features in a Text Editor to Start

- Code Completion
  - suggests code that you may have already started typing. Sort of like predictive text.
  - Emmet: a shorthand HTML and CSS language extension to speed up your code writing.
- Syntax Highlighting
  - This function will auto highlight different areas of code with different colors to easily reference your code.
- Variety of Themes (to reduce eye strain and fatigue)
  - Themes can change the background and font colors to help you in whatever environment you are working.
  - The goal here is to reduce the strain on your eyes!
- A healthy set of extensions available when needed.

  - Having the ability to add features to your text editor will come in handy!

 > text editors that are pre installed on your computer generally lack the components listed above.
   > However, if you *do* decide to use one of these preloaded programs, make sure that the program does the following:
>
> - Creates code in plains text. You shouldn't see any options for making bold, italic, underlined, etc...
> - File structure needs to be organized by you. Make sure that all files are saved in the appropriate folders
>   or subfolders
> - Double check your file extensions
> - Double-check your code! No code completion means you will need to double-check yourself for typos.

### Third-party Options

#### Notepad++

- Free
- Windows Computers Only
- Syntax Highlighting, Code Completion, Word Completion, Function Completion
- Zoom feature
- Online Community, Chat Room, & Searchable Wiki

#### TextWrangler (now BB Edit)

- Paid features but a free version is available. (30 day free trial)
- For more info, [click here](https://www.barebones.com/products/textwrangler/)

#### Visual Studio Code

- Free from microsoft
- all platforms
- emmit included for html, css
- has syntax highlighting, extensions, themes, code completion
- large following

#### Atom

- Free from Github
- All Platforms
- Atom also has syntax highlighting, themes, & extensions.
- Highly recommended

#### Brackets

- Free from Adobe
- All platforms
- Only supports HTML, CSS, JavaScript without additional extensions which are available
- Live Preview available

#### Sublime Text 3

- Free Version, Premium Version $70
- It has everything

### The Difference between Text Editors and IDE

IDE's contain text editors, but in a suite of software with a file manager, a compiler, and a debugger

- This type of software may be overwhelming to beginners

### Text Editors Conclusion

Text editors change often, so keep up with the times so that your coding experience is efficient to your style.

## Linux Tutorial

### Line One

  1. Prompt - Example: `➜  ~`
  2. Command - Example: `ls`
  3. Argument or Option typically start with a dash. Example: `-l`
  4. Argument

      > Spaces have to be between each of the 4

### The Shell, Bash

The shell is the part of the operating system that defines how the terminal will act and appear after commands.
The most common shell is known as ***Bash***.
  > Use the command `echo $SHELL` to find out what shell you are using.

### How to Move Around

#### `PWD`

Stands for **"Print Working Directory"**

- This will tell you your current location with the directory

#### `ls`

Stands for **"List"**

- This will give you a list of what files are available in your current location.
  - by add (-l), this will now give you more information about the files. This will show what type of file it is, Permissions, Blocks, Owner, group or directory it belongs to, file size, file modification time, name of file or directory.
- by adding (Example `ls -l /etc`), we can see a list of that directories contents.

#### Paths

A path refers to a file or directory on the "command line" or "terminal"

##### **There are 2 types of paths**

##### 1. Absolute Paths

Absolute paths specify a location (file or directory) in relation to the root directory.

- They will always begin with (`/`).
    > Example: `/home/justin/documents/file1.txt`

##### 2. Relative Paths

Relative Paths specify a location in relation to where you are within the system.

- They will **not** begin with (`/`).
  - > Example: `ls documents file1.txt`

#### Path Continued - Short Cuts

- `~` (tilde) represents a shortcut for home directory
  - `.` (dot) represents the current directory.
  - `..` (dotdot) Represents the parent directory
    > (Example: If you are in /home/justin, you can run the command: `ls ../ ../` to get a listing of the home or root directory.

**`CD`** (Change directory)
  
- cd can be ran without any arguments to take you back to the home directory
  - Typically, CD is ran with a single command line argument to show where we want to go.
  - The location can be specified as an absolute or relative path
    > Tip: You can use the "tab" button to help complete the command line possibility as long as there is only one possible outcome.

**`mkdir`** (Make Directory)

- Alternative to right clicking in a folder to create a new folder

**`touch`** (Create a new file)

- Alternative to right clicking in a folder to create a new folder

## Answers

1. The four important features of a text editor
   - Code Completion
   - theme
   - extensions
   - syntax highlighting
  
2. The following commands and their outcomes
   1. `PWD` - Print Working document will show you your location in the terminal
   2. `ls` - List will show you a list of files in your current location
   3. `cd` - Change Directory will take you to the file or directory you choose. However, just stating `cd` will take you to your home directory.
   4. `mkdir` - Make Directory will create a new folder
   5. `touch` - Creates a new file
  
3. Explain Scenarios
   1. `CD Projects` - Changing location in the terminal to the folder named "Projects"
   2. `mkdir new-project` - Create a new folder or directory within the "Projects" folder
   3. `touch new-project/newfile.md` - the user is creating a new file within the "new-project" folder
   4. `cd ..` - returning to the parent directory of "Projects"
   5. `ls projects/new-project` - asking for a list of files within the "new-project" folder that is contained in the parent directory called "projects"