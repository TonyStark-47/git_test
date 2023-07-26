# git_test
Experimenting with GitHub repo !
Hello Odin!

# CheatSheet

## Commands related to a remote repository:

* `git clone git@github.com:USER-NAME/REPOSITORY-NAME.git`
* `git push` or `git push origin main` (Both accomplish the same goal in this context)

## Commands related to the workflow:

* `git add .`
* `git commit -m "A message describing what you have done to make this snapshot different"`

## Commands related to checking status or log history

* `git status`
* `git log`

The basic Git syntax is `program | action | destination`.

For example,

* `git add .` is read as `git | add | .`, where the period represents everything in the current directory;
* `git commit -m "message"` is read as `git | commit -m | "message"`; and
* `git status` is read as `git | status | (no destination)`.
* `git remote -v` (This will display the URL of the repository you created on GitHub, which is the remote for your local copy.)

## NOTE:
You may have also noticed the word origin at the start of the `git remote -v` output, which is the name of your remote connection.
