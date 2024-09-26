Configure name and email for this repository
```bash
git config user.name "Full Name"
git config user.email "email@provider.com"
```
Configure default text editor
```bash
git config core.editor "nvim"
```
## Options
**`--local`** 
- Configure setting for current git repository.
- Stored in `./.git/config`.
- Default behaviour.
**`--global`**
- Configure setting for current user.
- Stored in `~/.gitconfig` or `$XDG_CONFIG_HOME/git/config`.
**`--system`**
- Configure setting for current system.
- Stored in `/etc/gitconfig`.