# OpenCV Installation Bash Script

This script automates the installation of OpenCV 4.x.x on Raspberry Pi 4 with a 64-bit OS. The script installs the necessary dependencies, downloads OpenCV and the contrib modules, configures, and installs them.

## Usage

1. Open your terminal.
2. Download the script and make it executable:

    ```bash
    wget -O install_opencv.sh https://raw.githubusercontent.com/KaanErgun/raspberry_pi_scripts/main/install_opencv.sh
    chmod +x install_opencv.sh
    ```

3. Run the script:

    ```bash
    ./install_opencv.sh 4.x.x
    ```

## Script Overview

The script performs the following steps:

1. Installs necessary dependencies.
2. Downloads OpenCV and opencv_contrib modules.
3. Configures and installs OpenCV.
4. Cleans up after installation.

For more information and the full content of the script, please refer to the [install_opencv.sh](https://raw.githubusercontent.com/KaanErgun/raspberry_pi_scripts/main/install_opencv.sh) file.
