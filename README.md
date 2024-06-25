# Anything-MPV
My personal configuration files, scripts and shaders that I use for MPV on my Windows machine.

## Installation Guide
1. Download the latest Windows build of **[MPV](https://mpv.io/)** from **[mpv-winbuild](https://github.com/zhongfly/mpv-winbuild/releases/latest/)**
2. If Your CPU supports AVX2 instruction **[AVX2](https://en.wikipedia.org/wiki/Advanced_Vector_Extensions)** (Typically any CPU released since 2015) then download the latest v3 build that should be formated like this `mpv-x86_64-v3-YYYYMMDD-git-abcxyz.7z`
3. After downloading, extract the archive's contents to your preferred location. eg: in my case, `C:\Program Files\MPV`
4. Navigate to the installer folder, right click on the `mpv-install.bat` file and select `Run as administrator`. Follow the on-screen instructions to complete the installation.
5. Now go back to the folder where `mpv.exe` is located. Right click on the `updater.bat` file and select `Run as administrator`.  It will ask you if you also want to download `ffmpeg` and `yt-dlp`. Tap Y for both.
6. From now on, use this `updater.bat` file to update MPV to the latest version. I would also recommend adding the folder where `mpv.exe` is located to the System Environment Variables path so that mpv can be used from CMD/Terminal.

 ## Scripts Used
