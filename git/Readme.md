# Description
- Initial Git setup is available at the [official documentation](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
- Setting up `git hist` alias is done by the command
```shell
git config --global alias.hist 'log --graph --abbrev-commit --decorate --all --format=format:"%C(bold blue)%h%C(reset) - %C(bold green) (%ar)%C(reset) %C(white) %s%C(reset) %C(dim white) - %an%C(reset) %C(auto) %d%C(reset)"'
```
- Setting up a global `.gitignore` file is described in the [article](https://sebastiandedeyne.com/setting-up-a-global-gitignore-file)
