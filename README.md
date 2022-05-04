this is just me learning how to create libs in c#


# Steps to do it again

```
mkdir SillyLib
cd SillyLib
dotnet new classlib
# edit some files 
dotnet build
dotnet build  --configuration Release

dotnet pack --configuration Release

export NUGET_KEY=BLABLA

dotnet nuget push bin/Release/SillyLib.1.0.0.nupkg --api-key $NUGET_KEY --source https://api.nuget.org/v3/index.json


# wait like 5m

open https://www.nuget.org/packages/SillyLib/

# wait like 1h 


```



# Links

https://docs.microsoft.com/en-us/nuget/quickstart/create-and-publish-a-package-using-the-dotnet-cli

