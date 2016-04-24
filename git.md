
# Use cases

## Git detached work tree
```
$ GIT_WORK_TREE=/var/www/www.example.org git checkout -f
```

References:
- http://toroid.org/ams/git-website-howto

## Partial Clone / remove old commits 
 http://stackoverflow.com/questions/2586824/partial-clone-with-git-and-mercurial
git clone --depth <n> <url>
git clone  --single-branch

## different remoes for pull and push
http://stackoverflow.com/questions/2916845/different-default-remote-tracking-branch-for-git-pull-and-git-push
git remote set-url --push
https://technosorcery.net/blog/2011/12/26/how-i-use-different-fetch-and-push-urls-in-git/


# Web server

## gitweb 
* install on ubuntu

- does serve html with correct type
- urls can NOT be used to resolve relative paths in the tree at the same commit

## gitlist
- same dev as gitweb 
- does not serve html type by default - chrome diplays the source




