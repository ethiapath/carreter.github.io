WHY ARE YOU EVEN READING THIS

## Install 

```sh
# cd to hugo site directory
cd carreterBlog
git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)
```


### Update theme
```sh
git submodule update --remote --merge
```
## Create a new post
```sh
hugo new --kind post posts/postName.md
```
This will use the "post.md" archetype in archetypes/post.md

```sh
hugo new posts/postName.md
```
Also works fine.
