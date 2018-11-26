# signalr-chat
SignalR chat application built on .NET Core 2.1.  Uses simple typescript client.


## Prerequisities

  * [Node](https://nodejs.org/en/download/)
  * [.NET Core 2.1](https://www.microsoft.com/net/download/dotnet-core/2.1)

## Get Started

* Clone the repo
* Navigate to signalr-chat folder, open a terminal:
  - `npm run release`
* This command yields the client-side assets.  Now build and run the .NET app:
  - `dotnet restore`
  - `dotnet build`
  - `dotnet run`
* Open browser, navigate to localhost:5000
* Open another browser session and navigate to same url
* Sending messages from one sessions will be broadcast to the any other connected browsers


## Resources

- https://docs.microsoft.com/en-us/aspnet/core/tutorials/signalr-typescript-webpack?view=aspnetcore-2.1&tabs=netcore-cli
