FROM mcr.microsoft.com/dotnet/core/runtime:2.2

COPY bin/Release/netcoreapp2.2/publish/ App/
WORKDIR /App
ENTRYPOINT ["dotnet", "AHeil.RoboticOverlord.App.dll"]