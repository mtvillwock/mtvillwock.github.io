# Just Git'ing Started
#### Understanding the benefits of using Git for version control
#### October 12th, 2014


+ What are the benefits of version control?

Version control is a great thing to have because it provides protection against deleting, accidentally overwriting, or otherwise modifying files in some undesireable way. In addition, version control allows you to keep track of what changes have been made to a file, when, by who, and why. This is useful for finding bugs in code, as well as just keeping up to speed on why certain changes were made, especially regarding projects that are being worked on by multiple people or are inherited down the road by people who didn't do any of the original work on the project.

A simple analogy is that of playdoh (http://www.hasbro.com/playdoh/en_US/). You can roll it out, stretch it, break it apart, smash it all back together... all without compromising the integrity of the material. Using version control like Git lets you branch off from a project, make substantial changes, and then merge those changes with the existing master code, all without having file conflict issues (which, if they do come up, are usually easy to resolve).

Another great thing about specifically using Git as your version control software is that you can commit changes without having access to the remote server. This is nice (possibly critical) for if you want to make some changes while somewhere that you don't have internet access.

Version control provides peace of mind. Knowing that you always have somewhere safe to return back to in case you break something is incredibly comforting, and allows developers to be more flexible and experimental with their changes to code.

Another cool thing is that you can use version control for anything, not just code. Got some essays you want saved? A novel you're working on? Start using Git, and you can feel safe knowing that your changes can be tracked and you'll never accidentally lose an entire writing session because you forget to click Save.


+ How does git help you keep track of changes?

Git keeps a log of all the changes that you (and anyone else working on the files) commits. It provides a date/time entry, a message from the author explaining what changes were made, and who the author of the changes was. Git can also will tell you if you have any changes that are unstaged (modified but not committed), staged (modified, and ready to be committed), and committed (saved as a checkpoint of sorts that can be returned to if anything goes wrong).

All it takes is some familiarity with using the command line, and suddenly your projects are well-protected from normally irrecoverable problems like accidental overwrites as well as more thoughtfully recorded due to the incorporation of messages that describe your commits.

Git helps you know what you did, when, and why.


+ Why use GitHub to store your code?

Using GitHub to store your code is important for a few reasons:

1. It gives you a remote repository, which will keep your code safe in case something happens to your local copy on your computer.
2. GitHub makes it easy to collaborate with other developers. This is beneficial because:
    2a. Having extra sets of eyes looking at your code will help find ways you can improve it.
    2b. It provides remote access, meaning you can access your files from any computer.
    2c. Other developers can interact with your repositories, meaning you can collaborate without swapping physical items like a USB drive.
3. It's free, as long as your repositories are public.


Git is a relatively simple, high-benefit solution that has a multitude of uses. I recommend it for anyone who has frequently changing documents that wants a better way to collaborate on projects and keep track of what they did and why.

