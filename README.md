# code-style
My common code style files

## Install

```
# clone the repo to /tmp
git clone https://github.com/englercj/code-style.git /tmp/code-style &&

# copy the dotfiles over (but not .git, readme, or the folder itself)
find /tmp/code-style/ ! \( -path "*.git" -o -path "*.git/*" -o -name "README.md" -o -path "/tmp/code-style/" \) -exec cp {} . \; &&

# remove the cloned folder
rm -rf /tmp/code-style/
```
