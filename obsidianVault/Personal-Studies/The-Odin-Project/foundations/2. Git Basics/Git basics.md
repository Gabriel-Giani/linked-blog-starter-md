[Cheatsheet](https://www.theodinproject.com/lessons/foundations-git-basics#cheatsheet)
This is a reference list of the most commonly used Git commands. (You might consider bookmarking this handy page.) Try to familiarize yourself with the commands so that you can eventually remember them all:

- Commands related to a remote repository:
    - `git clone git@github.com:USER-NAME/REPOSITORY-NAME.git`
    - `git push` or `git push origin main` (Both accomplish the same goal in this context)
- Commands related to the workflow:
    - `git add .`
    - `git commit -m "A message describing what you have done to make this snapshot different"`
- Commands related to checking status or log history
    - `git status`
    - `git log`

The basic Git syntax is `program | action | destination`.

For example,

- `git add .` is read as `git | add | .`, where the period represents everything in the current directory;
- `git commit -m "message"` is read as `git | commit -m | "message"`; and
- `git status` is read as `git | status | (no destination)`.

### [Git best practices](https://www.theodinproject.com/lessons/foundations-git-basics#git-best-practices)

There’s a lot to learn about using Git. But it is worth taking the time to highlight some best practices so that you can be a better collaborator. Git is not only helpful when collaborating with others. It’s also useful when working independently. You will be relying more and more on your own commit history in the future when revisiting old code.

Two helpful best practices to consider are **atomic commits** and leveraging those atomic commits to make your commit messages more useful to future collaborators.

An atomic commit is a commit that includes changes related to only one feature or task of your program. There are two main reasons for doing this: first, if something you change turns out to cause some problems, it is easy to revert the specific change without losing other changes; and second, it enables you to write better commit messages. You’ll learn more about what a good commit message looks like in a future lesson!

###

### [Changing the Git commit message editor](https://www.theodinproject.com/lessons/foundations-git-basics#changing-the-git-commit-message-editor)

If you are using _Visual Studio Code_ (and you should be if you’re following this curriculum), there’s a way to ensure that if you use `git commit` without the message flag (`-m`), you won’t get stuck writing your commit message in [Vim](https://en.wikipedia.org/wiki/Vim_(text_editor)).

Changing the default message editor is a good idea in case you accidentally omit the flag, unless you prefer using Vim. There is no downside to changing it, because you will have the option to write your commit messages in the terminal or in the comfort of VS Code.

The following command will set this configuration. Type (or copy & paste) this command into your terminal and hit Enter.

```bash
git config --global core.editor "code --wait"
```

There will be no confirmation or any output on the terminal after entering this command.

With that done, you can now choose to use either `git commit -m "your message here"` or `git commit` to type your message with Visual Studio Code!

To make a commit with Visual Studio Code as the text editor, just type `git commit`. After you hit Enter a new tab in VS Code will open for you to write your commit message. You may provide more details on multiple lines as part of your commit message. After typing your commit message, save it Ctrl + S (Mac: Cmd + S) and close the tab. If you return to the command line, you will see your commit message and a summary of your changes.

###