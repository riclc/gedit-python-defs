# Introduction #

This is a Python plugin for GEdit. It shows a mini source code browser in the current window, listing all definitions found in the current code and a list of source code folders.

It supports c code and python code (it also parses python docs and shows them).

# Screenshots #

![http://gedit-python-defs.googlecode.com/svn/trunk/Screenshots/screenshot-1.png](http://gedit-python-defs.googlecode.com/svn/trunk/Screenshots/screenshot-1.png)

The user fires up our plugin from GEdit. The function highlighted is the one closest to the cursor.

![http://gedit-python-defs.googlecode.com/svn/trunk/Screenshots/screenshot-2.png](http://gedit-python-defs.googlecode.com/svn/trunk/Screenshots/screenshot-2.png)

A list of folders is presented in the bottom panel. This list goes from the root of the project to the current source code directory. The root path is the upmost directory, starting from the current source code directory, that still have source files (.py, .c etc.). From the plugin, you can select any file or folder in this bar.

![http://gedit-python-defs.googlecode.com/svn/trunk/Screenshots/screenshot-3.png](http://gedit-python-defs.googlecode.com/svn/trunk/Screenshots/screenshot-3.png)

As you select a folder, the bottom panel updates and shows the selected folder contents, where you can select any source file inside that folder.

![http://gedit-python-defs.googlecode.com/svn/trunk/Screenshots/screenshot-4.png](http://gedit-python-defs.googlecode.com/svn/trunk/Screenshots/screenshot-4.png)

On the moment you select the file, the list of classes and functions is updated.

![http://gedit-python-defs.googlecode.com/svn/trunk/Screenshots/screenshot-5.png](http://gedit-python-defs.googlecode.com/svn/trunk/Screenshots/screenshot-5.png)

If you press enter (or double-click) on a selected function/definition, its source code will open in GEdit, with the cursor placed on the correct line for that definition. If the source is already open, it will just place the cursor there.