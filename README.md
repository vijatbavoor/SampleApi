# Sample API

Sample API is an application created using commands from vs code.

Pre requisits
1. Install [Visual Studio Code](https://code.visualstudio.com/)

    To setup VS code with recomended extensions please refer [Setup VS Code](#setup-vs-code)
2. Install latest [.NET Core SDK](https://dotnet.microsoft.com/en-us/download)
3. Install postmen to test
4. Install [Git Hub CLI](https://cli.github.com/)

## Create Sample API application

1. Verify is the latest .net core sdk is installed or not

    `dotnet --version`
2. Create an apllication

    `dotnet new webapi --name SampleApi`
3. Run the application

    `dontnet run`
4. Make application folder as repository

    `cd SampleApi`

    `git init`
5. Login to git hub to push the branch to origin

    `gh auth login`
6. Push repo git hub

    `gh repo create my-project --private --source=. --remote=upstream`

    `gh repo create SampleApi --public --source=. --remote=upstream`

## Setup VS Code
1. Add vs code extection 
