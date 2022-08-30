### add git remote repositories as submodule.
```
# Syntax
 git submodule add <remote_url> <destination_folder>
# Example command
 git submodule add https://github.com/srinivasarao2468/git-submodules.git ./simple/sample/remote
```

### if you want to checkout to latest changes from remote use below command.
```
# Example command
git submodule update --remote
```

### 
```
# Example command
git submodule update --init --recursive
```
![git submodule update](https://github.com/srinivasarao2468/git-submodule-demo/blob/master/git%20submodule%20init.png)