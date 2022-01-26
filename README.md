# nvm-installation-guide-for-windows-10

- Step:1 Download the nvm by running the following command in git bash terminal:~
```js
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```
- Step:2 Run the followwing command in git bash terminal:~
 ```js
    export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
 ```
 - Step:3 Run the followwing command in git bash terminal:~
  ```js
      [ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh"
  ```
  - Step:4 To verify the installation run the following command, if everything is installed correctly, it will give you the nvm version:~
  ```js
    command -v nvm
  ```
 - Step:5 To change the version of NodeJS version:~
  ```js
    nvm install <node_version>
  ```
   - Step:6 To use the installed version of node, run the following command:~
  ```js
    nvm use <node_version>
  ```
  
