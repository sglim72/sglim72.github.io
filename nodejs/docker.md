# NodeJS project in docker container
## All process blow must executed on Windows10, WSL2 Linux, Docker.

## 1. Create express project.
At first, express-generator must be installed in system.  
<span style='color:orange'>**[sudo is important]**</span>

```sh
$sudo npm install express-generator -g
```
And then, generate express project.

```sh
$express [project_name]
```

## 2. Install express module with npm.
```sh
$cd [project_name]
$npm install --no-optional
```

## 3.  Open VSCode
```sh
$cd [project_name]
$npm install --no-optional
```

## 4. Add Dockerfile
Docker extension must be installed on vscode.  
Open the Command Palette (`Ctrl+Shift+P`) and use `Docker: Add Docker Files to Workspace...` command and select `Node.js` and `docker-compose` include. (`yes`) and `select port`. (default 3000)

## 5. Build image
Open the Command Palette (`Ctrl+Shift+P`) and use `Docker Images: Build Image...` command.  
Check out docker image on images in Docker panel

## 6. Run the service container on docker panel [Use right click]
Run the service container on docker panel [Use right click]

## 7. Test run and debug
`http://localhost:3000`