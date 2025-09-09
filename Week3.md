# Your intro to Web Development

## Downloading your Dependencies

Download NodeJS [here](https://nodejs.org/en/download/).
Go past the docker stuff, you should download the `.msi` for the Windows x64 Architecture.

Download VSCode [here](https://code.visualstudio.com/download).
Get the Windows version of it.

## Intro to CMD / WT

### Hit Windows + R and Type `wt`

Welcome to the Terminal, you might've used this in your programming courses, but this is one of if not the closest ways that you can interact with the OS. No GUI (Graphical User Interface), no Desktop, just you and the machine.

_Note: most anything you can launch from a GUI you can launch from the command line._

Computers work in a file / directory system, where you have one 'root' folder where all others branch out from. I'm presuming that you've used a computer before, so I hope you're some what familiar with this.

Typically when you launch the terminal you'll be placed at the folder, `Users\<your-msoe-username>>`

Try typing `dir` and pressing enter. You should see a lot of familiar files pop up, particularly the Desktop, Downloads and Pictures. These are directories that Windows has by default in every user profile. (For those who want to know, the Linux equivalent of this is `ls`. You can use it in powershell but not cmd)

Next, let's make a folder in your user directory. Type `mkdir my-test-folder` and hit enter.

Now type `dir` again. Do you see the new `my-test-folder`?

Next, let's change directories into the folder. You can do so by typing `cd my-test-folder`. Try hitting Tab half way though to auto complete the folder name.

Now the line should read `Users\<your-msoe-username>\my-test-folder>`

Let's look at this folder in explorer, type `explorer .` (Don't forget the period!)

You should now see that the folder has been opened up, just like you would with file explorer regularly.

Next go back to the terminal, and type in `code .` (You will have needed to install VS code already.)

_NOTE! `.` is your current directory, and `..` is your parent directory._

This should pull up a VS Code. Note that at the top left of the screen under 'Explorer' you'll see your folder's name! (It' may be cut off by some icons.)

Next hover over the name and click the file icon with the plus sign, then add a name to your file. I'll name it `test.txt`, but you can name it whatever you want. Then hit enter.

Next enter some data into the text file in VSCode, like 'Hello World!' and hit Ctrl + S to save. (You can edit the auto save settings in VSCode if you'd like.)

Now move back to the command line terminal, and close the VSCode window. Next, we're going to delete the folder!

To get back to our parent directory, we're going to type `cd ..` and then hit enter, you should see the text change to `Users\<your-msoe-username>>` again.

Next type `rmdir my-test-folder`.

Uh Oh! There should be a warning, that says the dir has child items in it. Press `n` and hit enter for now. (We're going to manually delete the file)

Chance back to the folder, using the cd command again.

When inside type `del <your-file-name>` (If you can't remember the file name, type `dir` to see all files in the folder.)

Now change back to the parent directory.

Try removing it again. You'll likely run into an issue where it can't delete it because it's in use by another program. Close explorer and then try to delete it again.

Now type `dir` and see that you're folder has been removed.

Congrats! You can now traverse the files of your computer via the command line, open VS code and delete things! You'll need to use the command line to use programs like npm and NodeJS in the future.

#### Alternatively Type `cmd`

You have more limited commands, but can still perform everything that powershell can.

---

That's All for Today!

_SSE Website Development Fall of 2025 - David McIlveen_