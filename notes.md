
-> directory
    -> file.md

    git add <filename>

    git commit -m "Message."

GitHUb is the remote repository, while VSC or whatever is local repository.


Git Flow
    STAGE, COMMIT, PUSH == cycle. will probably go through stage & commit steps several times.



git status = checks status of dir


stage = watch and monitors files in directory, tracks changes, but doesn't save
    git add notes.md
    anytime you make changes to a file, must git add . --- (STAGE)

commit = SAVES CHANGES
    git commit -m "Adds notes."    -m is a message


push =  pushing to remote repository
    git push origin master (master is branch)

to check what remote repositories are linked to local
    git remote -v



initialize git repo
    git init
    git add . or file name
    git commit - m "first commit"
    git remote