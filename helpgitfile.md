
Bishnupriya@Bishnupriya-PC MINGW64 ~
$ git
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

Bishnupriya@Bishnupriya-PC MINGW64 ~
$ pwd
/c/Users/Bishnupriya

Bishnupriya@Bishnupriya-PC MINGW64 ~
$ mkdir projects/helloworld
mkdir: cannot create directory ‘projects/helloworld’: No such file or directory

Bishnupriya@Bishnupriya-PC MINGW64 ~
$ mkdir -p projects/helloworld

Bishnupriya@Bishnupriya-PC MINGW64 ~
$ cd projects

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects
$ ls
helloworld/

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects
$ git clone https://github.com/AnandaRPnew/helloworld.git

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects
$ ls
helloworld/

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects
$ rm -rf helloworld/

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects
$ ls

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects
$ git clone https://github.com/AnandaRPnew/helloworld.git
Cloning into 'helloworld'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects
$ git status
fatal: Not a git repository (or any of the parent directories): .git

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects
$ cd helloworld/

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        helloworld.html

nothing added to commit but untracked files present (use "git add" to track)

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$ git add -A

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   helloworld.html


Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$ git commit -m "Created first helloworld in git"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: empty ident name (for <(null)>) not allowed

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$ git config --global user.email "anandaroop.bera@gmail.com"

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$ git config --global user.name "Ananda"

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$ git commit -m "Created first helloworld in git"
[master 4220bb8] Created first helloworld in git
 1 file changed, 9 insertions(+)
 create mode 100644 helloworld.html

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
nothing to commit, working tree clean

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$ git
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$ git branch -vv
* master 4220bb8 [origin/master: ahead 1] Created first helloworld in git

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$ git push origin master
Logon failed, use ctrl+c to cancel basic credential prompt.
Username for 'https://github.com/': AnandaRPnew
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 377 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/AnandaRPnew/helloworld.git
   812e8bd..4220bb8  master -> master

Bishnupriya@Bishnupriya-PC MINGW64 ~/projects/helloworld (master)
$