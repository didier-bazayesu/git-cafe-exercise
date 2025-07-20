# git-cafe-exercise


# Bundle 5 exercises 2

s


    Directory: C:\Users\user\Documents\git-cafe-exercise


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         7/20/2025   9:06 PM                bat
d-----         7/20/2025   9:06 PM                css
d-----         7/20/2025   9:06 PM                images
d-----         7/20/2025   9:06 PM                js
-a----         7/20/2025   9:06 PM          12989 index-1.html
-a----         7/20/2025   9:06 PM          11385 index-2.html
-a----         7/20/2025   9:06 PM           9958 index-3.html
-a----         7/20/2025   9:06 PM          10486 index-4.html
-a----         7/20/2025   9:08 PM          16945 index.html
-a----         7/20/2025   9:06 PM             21 README.md


PS C:\Users\user\Documents\git-cafe-exercise> git add .\index.html
PS C:\Users\user\Documents\git-cafe-exercise> git commit -m "feat : change welcome message"
[main a221f61] feat : change welcome message
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\user\Documents\git-cafe-exercise> git push 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 325 bytes | 325.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/didier-bazayesu/git-cafe-exercise.git
   d1d3f9c..a221f61  main -> main
PS C:\Users\user\Documents\git-cafe-exercise> git checkout -b f 


# Bundle 6 exercise 1
git checkout -b ft/menu-page
Switched to a new branch 'ft/menu-page'
PS C:\Users\user\Documents\git-cafe-exercise> echo > main.html

cmdlet Write-Output at command pipeline position 1
Supply values for the following parameters:
InputObject[0]:
PS C:\Users\user\Documents\git-cafe-exercise> git add --all
PS C:\Users\user\Documents\git-cafe-exercise> git commit -m "feat: adding main.html"
[ft/menu-page e94496b] feat: adding main.html
 2 files changed, 57 insertions(+)
 create mode 100644 main.html
PS C:\Users\user\Documents\git-cafe-exercise> git push -u origin ft/menu-page
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.05 KiB | 1.05 MiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/menu-page' on GitHub by visiting:
remote:      https://github.com/didier-bazayesu/git-cafe-exercise/pull/new/ft/menu-page
remote:
To https://github.com/didier-bazayesu/git-cafe-exercise.git
 * [new branch]      ft/menu-page -> ft/menu-page
branch 'ft/menu-page' set up to track 'origin/ft/menu-page'.
PS C:\Users\user\Documents\git-cafe-exercise> git add .\menu.html
PS C:\Users\user\Documents\git-cafe-exercise> git commit -b "fix : change main to menu"
error: unknown switch `b'
usage: git commit [-a | --interactive | --patch] [-s] [-v] [-u[<mode>]] [--amend]
                  [--dry-run] [(-c | -C | --squash) <commit> | --fixup [(amend|reword):]<commit>]
                  [-F <file> | -m <msg>] [--reset-author] [--allow-empty]
                  [--allow-empty-message] [--no-verify] [-e] [--author=<author>]
                  [--date=<date>] [--cleanup=<mode>] [--[no-]status]
                  [-i | -o] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                  [(--trailer <token>[(=|:)<value>])...] [-S[<keyid>]]
                  [--] [<pathspec>...]

    -q, --[no-]quiet      suppress summary after successful commit
    -v, --[no-]verbose    show diff in commit message template

Commit message options
    -F, --[no-]file <file>
                          read message from file
    --[no-]author <author>
                          override author for commit
    --[no-]date <date>    override date for commit
    -m, --[no-]message <message>
                          commit message
    -c, --[no-]reedit-message <commit>
                          reuse and edit message from specified commit
    -C, --[no-]reuse-message <commit>
                          reuse message from specified commit
    --[no-]fixup [(amend|reword):]commit
                          use autosquash formatted message to fixup or amend/reword specified commit
    --[no-]squash <commit>
                          use autosquash formatted message to squash specified commit
    --[no-]reset-author   the commit is authored by me now (used with -C/-c/--amend)
    --trailer <trailer>   add custom trailer(s)
    -s, --[no-]signoff    add a Signed-off-by trailer
    -t, --[no-]template <file>
                          use specified template file
    -e, --[no-]edit       force edit of commit
    --[no-]cleanup <mode> how to strip spaces and #comments from message
    --[no-]status         include status in commit message template
    -S, --[no-]gpg-sign[=<key-id>]
                          GPG sign commit

Commit contents options
    -a, --[no-]all        commit all changed files
    -i, --[no-]include    add specified files to index for commit
    --[no-]interactive    interactively add files
    -p, --[no-]patch      interactively add changes
    -o, --[no-]only       commit only specified files
    -n, --no-verify       bypass pre-commit and commit-msg hooks
    --verify              opposite of --no-verify
    --[no-]dry-run        show what would be committed
    --[no-]short          show status concisely
    --[no-]branch         show branch information
    --[no-]ahead-behind   compute full ahead/behind values
    --[no-]porcelain      machine-readable output
    --[no-]long           show status in long format (default)
    -z, --[no-]null       terminate entries with NUL
    --[no-]amend          amend previous commit
    --no-post-rewrite     bypass post-rewrite hook
    --post-rewrite        opposite of --no-post-rewrite
    -u, --[no-]untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements are separated with NUL character

PS C:\Users\user\Documents\git-cafe-exercise> git commit -m "fix : change main to menu"
[ft/menu-page 71e371f] fix : change main to menu
 1 file changed, 13 insertions(+)
 create mode 100644 menu.html
PS C:\Users\user\Documents\git-cafe-exercise> git push -u origin ft/menu-page
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 251 bytes | 251.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/didier-bazayesu/git-cafe-exercise.git
   e94496b..71e371f  ft/menu-page -> ft/menu-page
branch 'ft/menu-page' set up to track 'origin/ft/menu-page'.
PS C:\Users\user\Documents\git-cafe-exercise> 


  # Bundle 6 exercise 2

  

