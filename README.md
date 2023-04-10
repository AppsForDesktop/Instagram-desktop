# Instagram for desktop

Instagram for desktop is the same Instagram but for Windows as desktop application

## Installation

You can install Instagram desktop on Windows by running the installer of latest [release](https://github.com/AppsForDesktop/Instagram-desktop/releases/download/1.0.0/Instagram.desktop.install.exe).

## Usage

Run the "Instagram.desktop.install.exe" and follow installation instructions.

## For professionals

You can build whole application from source code. For that you will need:

Visual studio 2019 with support to build .NET Framework 4.6

If you would like to create such installer as in release, you will need NSIS 2.5.1.

Run Developer Command Prompt for VS 2019

Execute commands in this prompt:

```
msbuild "Instagram desktop\Instagram desktop.sln" /p:Configuration=Release /p:SelfContained=True /p:PackageAsSingleFile=true /t:Publish /p:PublishDir=Publish

makensis installer_script.nsi
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.
