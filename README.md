# Talk32
A lightweight unofficial Discord client that uses only Win32, GDI, and GDI+ for rendering instead of Chrome/Electron. To support modern TLS on Windows XP it uses OpenSSL and provides its own root certificates.

This project is compiled with version 7.1 of the Windows SDK.

![Screenshot 1](docs/screenshot1.webp)

![Screenshot 2](docs/screenshot2.webp)

![Server logging](docs/logging_settings.webp)

#### How to run
1. Build or obtain a release
2. If you downloaded a copy of talk32.exe, put it in the repository folder
3. Run talk32.exe
4. Follow the instructions to get your authorization token, paste it in the field, and click "Log in"

#### How to build
1. Open the Windows SDK 7.1 command prompt.
2. Run the command **setenv /xp /x86 /release**
3. Change to the repository folder with **cd [folder path]**
4. Run **build.bat**
5. The result will be a file called talk32.exe

#### Known issues
- Random painting issues