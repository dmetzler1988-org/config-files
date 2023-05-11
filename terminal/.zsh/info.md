# Infos

Idea for this folder is from https://github.com/dbb/githome.

This folder is referenced in `.zshrc` file with this code:

```shell
## source external files
ext_dir="$HOME/.zsh"
ext_files=( c-configs c-plugins c-variables c-aliases c-functions c-keys c-prompts c-exports )
for file in $ext_files; do
    [[ -f ${ext_dir}/${file} ]] && source ${ext_dir}/${file}
done
```

## Example Repositories

- https://github.com/caarlos0/dotfiles
- https://github.com/holman/dotfiles
