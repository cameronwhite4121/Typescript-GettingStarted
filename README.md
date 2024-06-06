# Github Practice
This repository's purpose is to help me practice using source
control with github and coding with Typescript using vscode.

## Getting Started

### Installing Typescript
Typescript is exactly like Javascript, except it has strict data types. This can be useful when you are trying to be more exact with your code, but getting started can be a little clunky. I'm using vscode so these instructions are for that, but they may work in other IDE's.

- First, you'll need Node.js installed. You can find that here: [Node.js](https://nodejs.org/en)
- In the vscode's terminal (view -> terminal), run the command: `npm install -g typescript`
- Verify that Typescript installed correctly by running this command: `-tsc`

### Compiling Typescript
Once you have Typescript installed, there are a few handy options you can enable, one being the watch option. Enabling the watch option will automatically compile your typescript for you so you won't have to do it manually, saving time while being hassle free! 

- To accomplish this, run this command: `tsc --watch`

### Changing Execution Policy
You may encounter a problem when trying to run the watch script and you'll see this error appear `cannot
be loaded because running scripts is disabled on
this system. For more information, see
about_Execution_Policies at
https:/go.microsoft.com/fwlink/?LinkID=135170.` To bypass this, you need to set you execution policy to `RemoteSigned`. Open Windows Powershell as an administrator, run this command, `Set-ExecutionPolicy RemoteSigned
`, and the problem should be fixed!
