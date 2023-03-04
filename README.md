Elena@DESKTOP-6F2NBCD MINGW64 ~ (master)
$ pwd
/c/Users/Elena

Elena@DESKTOP-6F2NBCD MINGW64 ~ (master)
$ mkdir ejercicios

Elena@DESKTOP-6F2NBCD MINGW64 ~ (master)
$ cd ejercicios

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$ pwd
/c/Users/Elena/ejercicios

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$ code .

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$ git config --global user.name juan david

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$ git config --global.email juanalbadan3@gmail.com
error: unknown option `global.email'
usage: git config [<options>]

Config file location
    --global              use global config file
    --system              use system config file
    --local               use repository config file
    --worktree            use per-worktree config file
    -f, --file <file>     use given config file
    --blob <blob-id>      read config from given blob object

Action
    --get                 get value: name [value-pattern]
    --get-all             get all values: key [value-pattern]
    --get-regexp          get values for regexp: name-regex [value-pattern]
    --get-urlmatch        get value specific for the URL: section[.var] URL
    --replace-all         replace all matching variables: name value [value-pattern]
    --add                 add a new variable: name value
    --unset               remove a variable: name [value-pattern]
    --unset-all           remove all matches: name [value-pattern]
    --rename-section      rename section: old-name new-name
    --remove-section      remove a section: name
    -l, --list            list all
    --fixed-value         use string equality when comparing values to 'value-pattern'
    -e, --edit            open an editor
    --get-color           find the color configured: slot [default]
    --get-colorbool       find the color setting: slot [stdout-is-tty]

Type
    -t, --type <type>     value is given this type
    --bool                value is "true" or "false"
    --int                 value is decimal number
    --bool-or-int         value is --bool or --int
    --bool-or-str         value is --bool or string
    --path                value is a path (file or directory name)
    --expiry-date         value is an expiry date

Other
    -z, --null            terminate values with NUL byte
    --name-only           show variable names only
    --includes            respect include directives on lookup
    --show-origin         show origin of config (file, standard input, blob, command line)
    --show-scope          show scope of config (worktree, local, global, system, command)
    --default <value>     with --get, use default value when missing entry


Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$ gt config --global use.email juanalbadan3@gmail.com
bash: gt: command not found

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$ git config --global user.email juanalbadan3@gmail.com

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$ git init
Initialized empty Git repository in C:/Users/Elena/ejercicios/.git/

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$ status
bash: status: command not found

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$ git add README.md

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$ git commit -m "version inicial"
[master (root-commit) e5d9cb6] version inicial
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$ git status
On branch master
nothing to commit, working tree clean

Elena@DESKTOP-6F2NBCD MINGW64 ~/ejercicios (master)
$
git remote add origin https://github.com/juanbadan3/aspirantes-mir-ejercicio-1..git
git push -u origin main
git push -u origin main
git remote add origin https://github.com/juanbadan3/aspirantes-mir-ejercicio-1..git
git push -u origin main
git push -u origin main


