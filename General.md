# Windows Subsystem for Linux

* [Windows Subsystem for Linux Installation Guide for Windows 10](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
* [https://docs.microsoft.com/en-us/windows/wsl/wsl2-install](https://docs.microsoft.com/en-us/windows/wsl/wsl2-install)
* [Development Linux Env on Windows 10](https://www.hanselman.com/blog/SettingUpAShinyDevelopmentEnvironmentWithinLinuxOnWindows10.aspx)
* [WSL Faq](https://msdn.microsoft.com/en-us/commandline/wsl/faq)
* [Files editing warning](https://blogs.msdn.microsoft.com/commandline/2016/11/17/do-not-change-linux-files-using-windows-apps-and-tools/)
* [Configure WSL](https://blogs.msdn.microsoft.com/commandline/2018/02/07/automatically-configuring-wsl/)
* [Fun with WSL](https://blogs.windows.com/buildingapps/2016/07/22/fun-with-the-windows-subsystem-for-linux/)

# Docker on Windows 10

* [Docker for Windows](https://docs.docker.com/docker-for-windows/install/#where-to-go-next)
* [Docker and Linux Containers w/ & w/out Hyper-V](https://www.hanselman.com/blog/DockerAndLinuxContainersOnWindowsWithOrWithoutHyperVVirtualMachines.aspx)

# Pulseaudio in WSL

From this [repo](https://github.com/aseering/wsl_gui_autoinstall/blob/master/wsl_gui_autoinstall.bat)

# Run VSCode in WSL

From this [issue](https://github.com/Microsoft/WSL/issues/2760)

# Terminals in WSL (Windows 10)

From this [blogpost](https://blog.ropnop.com/configuring-a-pretty-and-usable-terminal-emulator-for-wsl/#firstattempts)

## Setup X Server on Windows
1. Download [VCXSRV X Server](https://sourceforge.net/projects/vcxsrv/)
2. Create a link to ```"C:\Program Files\VcXsrv\vcxsrv.exe" :0 -ac -terminate -lesspointer -multiwindow -clipboard -wgl -dpi auto``` to start XServer

## Setup Terminator

1. Open WSL
2. Run ```sudo add-apt-repository ppa:gnome-terminator```
3. Run ```sudo apt-get install terminator```
4. Run ```DISPLAY=:0 terminator &```

## Setup Terminology (slow)

1. Open WSL
2. Run ```sudo add-apt-repository ppa:enlightenment-git/ppa```
3. Run```sudo service dbus start && LIBGL_ALWAYS_INDIRECT=1 DISPLAY=:0 terminology &```
