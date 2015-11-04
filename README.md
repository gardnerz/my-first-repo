# my-first-repo
CSE231-Honors Lab8

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu (master)
$ git config --global user.name "John Doe"

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu (master)
$ git config --global user.email johndoe@example.com

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu (master)
$ mkdir my-first-repo

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu (master)
$ ls
my-first-repo/

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu (master)
$ cd my-first-repo

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$ vim helloworld.py

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$ python3helloworld.py
bash: python3helloworld.py: command not found

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$ git init
Initialized empty Git repository in C:/Users/Zanijah/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo/.git/

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$ git add helloworld.py
warning: LF will be replaced by CRLF in helloworld.py.
The file will have its original line endings in your working directory.

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$ git remote add origin git@github.com:your git profile name/my-first-repo.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=<push|fetch>]
                          set up remote as a mirror to push to or fetch from

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$ git add helloworld.py

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$ git commit -m"add text"
[master (root-commit) 61b9bfb] add text
warning: LF will be replaced by CRLF in helloworld.py.
The file will have its original line endings in your working directory.
 1 file changed, 1 insertion(+)
 create mode 100644 helloworld.py

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$ git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$ git  commit -m"add text"
On branch master
nothing to commit, working directory clean

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$ git config --get remote.origin.url

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$ git remote show origin
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$ git remote add origin2
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=<push|fetch>]
                          set up remote as a mirror to push to or fetch from


Zanijah@Zanijah-PC MINGW64 ~/ssh gardnerz@adriatic.cse.msu.edu/my-first-repo (master)
$
