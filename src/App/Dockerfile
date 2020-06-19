FROM mcr.microsoft.com/dotnet/core/runtime:3.1

COPY bin/Release/netcoreapp2.2/publish/ App/
WORKDIR /App
ENTRYPOINT ["dotnet", "AHeil.RoboticOverlord.App.dll"]