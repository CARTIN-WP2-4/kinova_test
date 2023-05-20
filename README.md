# Kinova-Setup
Testing Kinova Installation and basic C++ coding.

## Table of Contents

## Getting Started

### Setup
#### Visual Studio Community
Download and install Visual Studio Community 2019. For the current version (2022) or older versions (< 2019), please refer to this <a href="https://visualstudio.microsoft.com/downloads/">link</a>.

#### CMake
Refere to the instructions <a href="https://cmake.org/install/">here</a> to install CMake depending on the platform you are using. For Windows users, please make sure that you select the option of adding CMake to the system PATH as shown below.

![Add to PATH](./data/CMake_Windows_install_path.png)

(Check if it can be updated to the latest version 3.26.4.)

#### GCC Compiler
To install GCC 5.4 on Linux platform
```sh
sudo apt-get install build-essential
```

To install GCC 5.4 on Windows platform
Since GCC is not coded for the Windows OS, a GCC port of MinGW-w64 is required. The '-w64' suffix indicates that it can support both 32-bit and 64-bit environments.

The steps to install it are as follows:
1. Download the MinGW-w64 executable file from the folder above.
2. Start the installer and click **Next >** until you reach the installation options page
3. Here, ensure that the options look exactly like the image below.

![GCC Windows](./data/GCC_Windows_install_settings.png)

4. Click **Next >**. You might run into an error that says **The file has been downloaded incorrectly.** In this case, click **OK** and **Finish** to close the installation window.
5. To solve the installation error, we need to add the path of the bin directory to the system path to make all the MinGW commands and tools available system wide. For this, follow the steps as shown in the video.

(Check if file has to be downloaded from folder or website.)

<p align="right">(<a href="#readme-top">🔼 back to top</a>)</p>

### Build

### Run

## Contributing

## License


