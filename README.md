# Instagram for desktop

Instagram for desktop is the same Instagram but for Windows as desktop application

Instagram windows is a free photo and video sharing app available on desktop PC.

1.   You can: 
     - upload photos or videos
     - share them with their followers or with a select group of friends
     - view, comment and like posts shared by their friends posts on Instagram

Anyone can create an account by registering an email address and selecting a username.

2.   Perks of having Instagram windows App:
     - An icon on your quick access spots
     - One-click launch
     - No need for an open browser tab

Instagram desktop works on Windos 7, Widows 8, Windows 10, Windows 11.

What are you waiting for? Hit Download and open up Instagram App on your Windows platform Desktop or Laptop.

## Installation

You can install Instagram desktop on Windows by running the installer of latest [release](https://github.com/AppsForDesktop/Instagram-desktop/releases/download/1.0.0/Instagram.desktop.install.exe).

## Usage

Run the "Instagram.desktop.install.exe" and follow installation instructions.

## For professionals

3.   You can build whole application from source code. For that you will need:
     - Visual studio 2019 with support to build .NET Framework 4.6
     - If you would like to create such installer as in release, you will need NSIS 2.5.1.

Run Developer Command Prompt for VS 2019

Execute commands in this prompt:

```
msbuild "Instagram desktop\Instagram desktop.sln" /p:Configuration=Release /p:SelfContained=True /p:PackageAsSingleFile=true /t:Publish /p:PublishDir=Publish

makensis installer_script.nsi
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.
