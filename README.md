# Web-editor
#### Created a sample application using Angular and Monaco editor for a Custom Language Server
##### Setting Up the Angular Project
First, create a new Angular project using Angular CLI. Then go inside the newly created project folder
```bash
ng new web-editor
```
```bash
cd web-editor
```
##### Installing Monaco Language Client
The latest version of Monaco Language Client at the time of writing this article is version 8.4.0. With this version, the development team (TypeFox) suggests using their wrapper for the editor instead of directly using the Monaco Editor.
```bash
npm i monaco-languageclient vscode-ws-jsonrpc monaco-editor-wrapper
```
##### Starting Client and Server
Starting the Language Server
```bash
java -jar target/hellols-0.0.1-SNAPSHOT.jar
```
Starting the Web Editor
```bash
ng serve
```
