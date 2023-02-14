# Chimera Linux WSL Reference Implementation
## Introduction 
The goal of this repo  is to get chimera working on wsl2 for as little work possible, so that it can be used to quickly test new versions and a proper setup script can grow over time.

## Getting Started
1. Generate a test certificate:
   1. In Visual Studio, open `DistroLauncher-Appx/MyDistro.appxmanifest`
   2. Select the Packaging tab
   3. Select "Choose Certificate"
   4. Click the Configure Certificate drop down and select Create test certificate.

2. Download the latest x86 core ROOTFS from this link https://repo.chimera-linux.org/live/latest/

3.  Name it install.tar.gz and place it in x64 folder

4. With the project open in Visual Studio, right click Solution 'DistroLauncher' and click deploy

5. Launch 'Chimera' from the start menu

6. (Optional) Run wsl --set-version chimeralinuxunofficial 2 in powershell to convert the distro to wsl2

## Using Chimera
Chimera lacks a lot of features at the time of writing. 
Check out https://chimera-linux.org/docs/
