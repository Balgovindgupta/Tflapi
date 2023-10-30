# uk.tfl.app

Check london road status using Transport for London Unified API

## Target Framework

 Framework `.Net 6.0` (.Net Core Console Application)

## How to build the code

Run `dotnet build` on the command prompt window opened at the location path of "uk.tfl.app.sln" solution file

## How to run the output

Open Powershell window at the location path of "uk.tfl.app.sln" solution file and run below command
1. Run `dotnet publish -o ./deploy` 
2. Run `cd deploy` 
3. Run `.\uk.tfl.console a2` 
4. Run `echo $lastexitcode`
5. Run `.\uk.tfl.console a233` 
5. Run `echo $lastexitcode`

## How to run any tests that you have written

Run `dotnet test` on the command prompt window opened at the location path of "uk.tfl.app.sln" solution file

## any assumptions that you’ve made



## anything else you think is relevant


## configure your application to use a different App ID and API key

App ID, API key and BaseUrl can be configure in `appsettings.json` under project `uk.tfl.apiclient`





