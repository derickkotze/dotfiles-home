# macOS fresh install

## Git-free install

```bash
cd ~
curl -#L https://github.com/derickkotze/dotfiles-home.git/tarball/main | tar -xzv --strip-components=1
./.macos <preferred_host_name>
./brew_check
./brew_install
# rm README.md
```
