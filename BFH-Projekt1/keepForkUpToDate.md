### 1. Clone your fork:

    git clone git@github.com:YOUR-USERNAME/YOUR-FORKED-REPO.git

### 2. Add remote from original repository in your forked repository: 

    cd into/cloned/fork-repo
    git remote add upstream git://github.com/ORIGINAL-DEV-USERNAME/REPO-YOU-FORKED-FROM.git
    git fetch upstream

### 3. Updating your fork from original repo to keep up with their changes:

    git pull upstream master
    
### 4. Push your fork to the github repositry
    
    git push
    git push --tags
    
### Neuer Branch erstellen aus tag

    git branch newbranch v0.x.y.xy
    git push -u origin <branch>

#### Vorgehen beim Projekt

    Der master des forkes wird nicht verändert. Wir werden einen eigenen MasterBFH erstellen und diesen mit 
    dem neusten update tag (v0.x.y.xy) des syncthing Projekts mergen.
    Der MasterBFH ist ein branch des tag v0.14.51. Alle weiteren branchs sollen vom MasterBFH branch erstellt werden.
