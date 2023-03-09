# assignment-1
assignment
kasak@Kasak MINGW64 ~
$ cd desktop

kasak@Kasak MINGW64 ~/desktop
$ mkdir shopping

kasak@Kasak MINGW64 ~/desktop
$ git init shopping
Initialized empty Git repository in C:/Users/kasak/Desktop/shopping/.git/

kasak@Kasak MINGW64 ~/desktop
$ cd shopping

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ touch yard.txt

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ touch gorceries.txt

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git add .

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git commit -m 'create yard and groceries lists'
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'kasak@Kasak.(none)')

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git config --user.email "kasakgohel39@gmail.com"
error: unknown option `user.email'
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


kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git config --global user.email "kasakgohel39@gmail.com"

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git config -- user.name "kasak"

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git commit -m 'create yard and groceries lists'
[master (root-commit) b0a7ea5] create yard and groceries lists
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 gorceries.txt
 create mode 100644 yard.txt

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git add gorceries.txt

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git commit -m 'add ingredients for tomato soup'
[master 7a25cf8] add ingredients for tomato soup
 1 file changed, 3 insertions(+)

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git add yard.txt

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git commit -m 'add items needed for garden box'
[master ffde3af] add items needed for garden box
 1 file changed, 2 insertions(+)

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git add .

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git commit -m 'add items needed to grow potatoes'
[master e03685c] add items needed to grow potatoes
 2 files changed, 2 insertions(+), 1 deletion(-)

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$ git log
commit e03685c4d7b545c32e90b03cd28358282808c349 (HEAD -> master)
Author: kasak <kasakgohel39@gmail.com>
Date:   Thu Mar 9 18:54:54 2023 +0530

    add items needed to grow potatoes

commit ffde3af9e65cb73dcc2ecd83992482feaf405176
Author: kasak <kasakgohel39@gmail.com>
Date:   Thu Mar 9 18:52:06 2023 +0530

    add items needed for garden box

commit 7a25cf81353d6212417f5c503b9ca7c284c2f335
Author: kasak <kasakgohel39@gmail.com>
Date:   Thu Mar 9 18:50:59 2023 +0530

    add ingredients for tomato soup

commit b0a7ea5ffd99040136f64ddbd2885b6c3e1e028a
Author: kasak <kasakgohel39@gmail.com>
Date:   Thu Mar 9 18:46:38 2023 +0530

    create yard and groceries lists

kasak@Kasak MINGW64 ~/desktop/shopping (master)
$
