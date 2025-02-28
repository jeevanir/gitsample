"# gitsample" 
# gitsample

rhari@Jeeva MINGW64 ~
$ git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   restore    Restore working tree files
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   diff       Show changes between commits, commit and working tree, etc
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   backfill   Download missing objects in a partial clone
   branch     List, create, or delete branches
   commit     Record changes to the repository
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   reset      Reset current HEAD to the specified state
   switch     Switch branches
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

rhari@Jeeva MINGW64 ~
$ cd gitsample

rhari@Jeeva MINGW64 ~/gitsample (main)
$ ir
bash: ir: command not found

rhari@Jeeva MINGW64 ~/gitsample (main)
$ dir
another.txt  gitsample  README.md

rhari@Jeeva MINGW64 ~/gitsample (main)
$ git init
Reinitialized existing Git repository in C:/Users/rhari/gitsample/.git/

rhari@Jeeva MINGW64 ~/gitsample (main)
$ git clone https://github.com/jeevanir/gitsample
fatal: destination path 'gitsample' already exists and is not an empty directory.

rhari@Jeeva MINGW64 ~/gitsample (main)
$ echo "# gitsample" >> README.md

rhari@Jeeva MINGW64 ~/gitsample (main)
$

rhari@Jeeva MINGW64 ~/gitsample (main)
$ git init
Reinitialized existing Git repository in C:/Users/rhari/gitsample/.git/

rhari@Jeeva MINGW64 ~/gitsample (main)
$ git commit -m "first commit"
[main (root-commit) 8cd2faf] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

rhari@Jeeva MINGW64 ~/gitsample (main)
$ git branch -M main

rhari@Jeeva MINGW64 ~/gitsample (main)
$ git remote add origin https://github.com/jeevanir/gitsample.git
error: remote origin already exists.

rhari@Jeeva MINGW64 ~/gitsample (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 223 bytes | 111.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/jeevanir/gitsample.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

rhari@Jeeva MINGW64 ~/gitsample (main)
$ 
rhari@Jeeva MINGW64 ~/gitsample (main)
$ git pull origin main
From https://github.com/jeevanir/gitsample
 * branch            main       -> FETCH_HEAD
Already up to date.

rhari@Jeeva MINGW64 ~/gitsample (main)
$ git checkout main
M       README.md
Already on 'main'
Your branch is up to date with 'origin/main'.

rhari@Jeeva MINGW64 ~/gitsample (main)
$ $ cd "C:\samplerhari@Jeeva MINGW64 ~
$ rhari@Jeeva MINGW64 ~/gitsample (main)
  $git clone https://github.com/jeevanir/gitsample
bash: clone: command not found

rhari@Jeeva MINGW64 ~/gitsample (main)
$ cd gitsample

rhari@Jeeva MINGW64 ~/gitsample/gitsample (main)
$ git clone https://github.com/jeevanir/gitsample
Cloning into 'gitsample'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

rhari@Jeeva MINGW64 ~/gitsample/gitsample (main)
$ it clone --branch
bash: it: command not found

rhari@Jeeva MINGW64 ~/gitsample/gitsample (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.
/////////////
C:\Users\rhari\gitsample
/////////
The most similar command is