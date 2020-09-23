# legendary-updater
A simple batch script that checks for updates on Legendary

## Usage
Before using be sure to have the `Legendary.exe` file in your User account folder Ex. `C:\Users\shapes`. If it isn't in there, move it into there or
1. Clone the repository, either by doing `git clone https://github.com/realshapes/legendary-updater` or downloading it through a zip. 
2. Open `update.bat` thats in the folder and change `cd C:\Users\%username%` to the folder where `Legendary.exe` is located. Then follow [these steps](#compile-into-executable)
## Compile into executable

In order to use this as a non-steam app, or run it at startup, you must Compile it into an Executable.
1. Open `iexpress.exe`
    1. Navigate to `C:\Windows\System32`.
    2. Find `iexpress.exe`.
    3. Run it as an administrator.
2. Setup
    1. Click "Open existing Self Extraction Directive File"
    2. Select the `Legendary Updater.SED` file in the Repository folder.
    3. Click on Create Package, then click Next.
    4. Once it finishes the finished file should be outputted into C:\