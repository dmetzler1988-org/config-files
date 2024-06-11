# Infos

Idea for this folder is from https://github.com/dbb/githome.

This folder is referenced in `.zshrc` file with this code:

```shell
## source external files
ext_dir="$HOME/.zsh"
for file in "$ext_dir"/*; do
  if [ -f "$file" ] && [ "$file" != "$ext_dir/info.md" ]; then
    source ${file}
  fi
done
```

## Example Repositories

- https://github.com/caarlos0/dotfiles
- https://github.com/holman/dotfiles
