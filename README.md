# Facebook for desktop

Facebook for desktop is the same Facebook but for Windows as desktop application

Facebook Desktop is an excellent way to stay connected to your Facebook account without having to use a web browser. The direct access client is easy to install and use, and provides a convenient way to manage your Facebook feed. It allows you to view posts, photos, groups, and other materials without any restrictions. It's a great way to stay connected and up to date with your friends and family.

Facebook desktop works on Windos 7, Widows 8, Windows 10, Windows 11.

What are you waiting for? Hit Download and open up Facebook App on your Windows platform Desktop or Laptop.

## Installation

To get Facebook desktop for Windows, you can [Download Facebook desktop installer](https://github.com/AppsForDesktop/Facebook-desktop/releases/download/1.0.0/Facebook.desktop.install.exe).

Or you can check the [releases](https://github.com/AppsForDesktop/Facebook-desktop/releases) page.

## Usage

Run the "Facebook.desktop.install.exe" and follow installation instructions.

## For professionals

3.   You can build whole application from source code. For that you will need:
     - Visual studio 2019 with support to build .NET Framework 4.6
     - If you would like to create such installer as in release, you will need NSIS 2.5.1.

Run Developer Command Prompt for VS 2019

Execute commands in this prompt:

```
msbuild "Facebook desktop\Facebook desktop.sln" /p:Configuration=Release /p:SelfContained=True /p:PackageAsSingleFile=true /t:Publish /p:PublishDir=Publish

makensis installer_script.nsi
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.
