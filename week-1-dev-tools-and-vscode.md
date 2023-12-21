# Week 1 Dev Tools and VSCode

**Requiements** 

* [DevTools 1](https://lib.opencomplib.org/software-development/tools/chrome1.html)
* [VSCode](https://lib.opencomplib.org/software-development/tools/vscode.html)

**DevTools Master the following skills:**
* Master the following skills:
* Discuss the utility of Chrome Dev Tools for front-end web development
* Open Chrome Dev Tools using the mouse
* Inspect HTML elements and view CSS styles
* Open Chrome Dev Tools using a keyboard shortcut
* Make live changes to HTML and CSS
* Locate and list the files that make up a website
* View errors and logs in the console
* Understand which resources and requests take longer to load
* Simulate websites on mobile devices


**VSCode Master the following skills:**

* Discuss the uses of VS Code in Web Development
* Install VS Code on your computer
* Open and close files
* Open an entire folder in VS Code
* Locate and open the embedded terminal
* Install and use extensions in VS Code.
* Modify editor settings for specific coding languages and global
* Apply formatting to poorly formatted code
* Format code using keyboard shortcut

(Also option click for multi-cursor)

### Day 1 DevTools

On Day 1, we can get a lot of gee-wizz fun out of the DevTools. This will improve motivation and make them feel like they a take away.

Be sure to save some time for the install fest of VSCode and GitHub Desktop. They will need VSCode installed by day 3. Chromebooks users will have a hard time!

**Topics:**

* Discuss the utility of Chrome Dev Tools for front-end web development
* Open Chrome Dev Tools using the mouse
* Inspect HTML elements and view CSS styles
* Open Chrome Dev Tools using a keyboard shortcut
* Make live changes to HTML and CSS

## Day 2 DevTools

On Day 2, we will review the DevTools concepts from Day 1. Be careful to review methodically. Students will forget, and some will be coming in new if they missed the first class.

We will also introduce topics like files and servers. For simplicity, build a simple website in Replit or Codespaces and give them the live link to browse from their own browser. (If you are able to use a tunnel to share your localhost, you might do that, too.) Show them the relationship between files on the server and documents in the browser.

You can introduce h1, p, a, and img tags. Show how images are served just like files. Demo links and folders if possible.

Put in missing image files to show the errors that can pop up in the console.

*Save time for a check-in about VSCode installation.*

**Topics:**

* Locate and list the files that make up a website
* View errors and logs in the console
* Understand which resources and requests take longer to load
* Simulate websites on mobile devices

## Day 3: VSCode

**Install Fest completes.** Students should all have VSCode installed. *(If students are having a hard time installing VSCode, that's a sign they are having trouble managing their own machine--Chromebook users will have the hardest time. Those students will require mentoring. It would be a good time to enforce mandatory mentoring sessions.)*

Key concept: Students should realized the relationship between what they see in VSCode and what they see in Finder or Explorer. Students might not realize that the files they create in VSCode are actually files on their machine.

Install Live Server for a gee whiz moment. This will be a good take-away to let them feel like they are learning and making progress. Have students use `h1` and `p` tags to make a simple webpage appear. (HTML is forgiving and won't require `head` or `body` so using html boilerplate is unnecessary.)

**Topics:**

* Discuss the uses of VS Code in Web Development
* Install VS Code on your computer
* Open and close files
* Open an entire folder in VS Code
* Install and use extensions in VS Code.

## Day 4: VSCode

Make sure GitHub Desktop is installed. (This will give you Git and help with setup without using the terminal.) Alternatively, you can have them open the terminal and set up `git --global` manually, but this may require mentoring and it won't be clear to students why they are going through these procedures.

With git installed, we can now use VSCode to open a repo. From an empty VSCode page, click "Clone Git Repository". (Alternatively, you can use `git clone` from the terminal. That will require some initial set up to make `code .` work, which might require working with a mentor.)

Have students clone a repo with and index.html file and a few images. Have students add some `h1` tags `p` tags, and `img` tags in addition to the ones you provide. Make sure they format their code with the auto formatter.

Show how to create a file with `touch` and a directory with `mkdir`. Emphasize how the terminal, VSCode, and Finder/Explorer can be used to create and view files in the file system. Students may not realize they are working in the same space with different tools. (This can also be a Gee Whiz moment.)

* Locate and open the embedded terminal
* Install and use extensions in VS Code.
* Modify editor settings for specific coding languages and global
* Apply formatting to poorly formatted code
* Format code using keyboard shortcut

* Clone from a remote repository using VSCode or GitHub Desktop

## Day 5 Simple Git Usage

This day will be spent learning enough git to be able to turn in assignments next week. We will cover the topics of [Git Power User 1](https://lib.opencomplib.org/software-development/tools/git1.html), but will not delve into the command line.

We will have time during the Git/Deploy week to delve into using git with the command line.

Have students practice how they will turn in assignments next week. They must FORK a repo, then clone the forked repo. Then they commit with the VSCode interface, and sync. (This can all be learned in one day, and there won't be any "clone a repo in a repo" problems.)

Discuss how git and GitHub are ways to show work and credit individual contributors.

**Topics:**

* Discuss the problems that can be solved by source control systems like Git
* Fork a repository in Github
* Differentiate between copies of repositories
* Clone from a remote repository
* Differentiate between local and remote changes
* Open source control panel in VS Code
* Commit changes with a good message
* Sync changes between local and remote repositories
* Discuss the impact of well-written commit messages
