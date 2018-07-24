# Install instructions

```
cd $HOME
```
## get source
```
git clone git@github.com:gvizdyk/vscode.git
```
or
```
git clone https://github.com/gvizdyk/vscode.git
```
## install extensions
### Bash
```
<extensions.list xargs -I % code --install-extension %
```
### Windows cmd
```
for /F "tokens=*" %%A in (extensions.list) do code --install-extension %%A
```