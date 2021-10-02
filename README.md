# Notes

The sometimes necessary stuff:

## Clean node on Windows
1. npm cache clean --force
2. npm cache verify
3. Uninstall Node.js program
4. CHECK:
- C:\Program Files (x86)\Nodejs
- C:\Program Files\Nodejs
- C:\Users\{User}\AppData\Roaming\npm or open run and type appdata and click ok and open roaming there you will find npm.
- C:\Users\{User}\AppData\Roaming\npm-cache or open run and type appdata and click ok and open roaming there you will find npm-cache.
- C:\Users\{User}\.npmrc
- C:\Users\{User}\AppData\Local\Temp\npm-*
5. where node

## GIT

- git ls-tree -r <master HEAD> --name-only
- git config -l		//list-all (local repo configuration)
- git --local -l  	^^
- git --system -l		//system configs
- git --global -l		//user configs
- git config -l --show-origin 	//all settings in cwd
- git status -s //short status
- git add <file or pattern>
- git commit -m '...' //commit w/comment
- git rm --cached <file> //remove from staging
- git mv <file> <new file location> //move file
- git log //commit history
- git log --patch <-p> -2 //show last two commits with patch level verbosity 
- git log --stat //abbreviated commits stats
- git log --pretty
- git log --pretty=format:"%H - %an, %ae -- %ar --- %s" //formatted output
    	https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History
- git remote -v //shows all remote servers configured, use -v for URLs of those...  
- git remote show <remote> // repo details
- git remote rename
- git tag -l //lists existing tags
- git tag -a v1.2 -m 'testing tag two again' //annotated tags
- git tag v1.0 //lightweight tag
- git tag -d <tagname> // delete tag
- git config --global alias.<alias name> <command>
/* common to add a 'git last' */
- git config --global alias.last 'log -1 HEAD'
- git checkout master // switching branches
- git checkout -b <branch name> //create new branch and switch to it
- git branch <branch name>
- git branch //list branches
- git branch -v //list branches and last commit of each
- git branch --merged
- git branch --no-merged
- git branch -d <branch name> //delete branch
- git merge //merge branch
- git mergetool //conflict resolution tool
  - git show
