# Infos

Idea for this folder is from https://github.com/dbb/githome.

This folder is referenced in `.zshrc` file with this code:

```shell
## source external files
ext_dir="$HOME/.zsh"
ext_files=( c-plugins c-aliases c-functions c-keys c-prompts )
for file in $ext_files; do
    [[ -f ${ext_dir}/${file} ]] && source ${ext_dir}/${file}
done
```
