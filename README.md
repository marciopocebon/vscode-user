# vscode-user
Personal settings for vscode's User folder.

## Usage
- backup your folder:
  ```shell
  mkdir -p /tmp/.config/Code/User
  cp -R $HOME/.config/Code/User /tmp/.config/Code/User
  ```
- remove the folder:
  ```shell
  rm -rf $HOME/.config/Code/User
  ```
- clone this repo:
  ```shell
  git@github.com:marioluan/vscode-user
  ```
- rename it:
  ```shell
  mv vscode-user User
  ```
- move it to vscode context:
  ```shell
  mv User $HOME/.config/Code/User
  ```
