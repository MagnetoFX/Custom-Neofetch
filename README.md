Custom Neofetch Configuration
This repository contains a custom configuration for Neofetch, tailored to display system information alongside an ASCII Tux Penguin logo. This configuration emphasizes aesthetics and clear organization of system specs.

Features
* A clean, organized layout for system information.
* Custom ASCII Tux Penguin logo.
* Displays:
   - Distro
   -Kernel
   -Installed Packages
   -Hostname
   -CPU
   -GPU
   -Screen Resolution
   -Memory Usage
  -System Uptime

Preview
https://i.imgur.com/opX65IB.png

Installation
Follow these steps to install and use this configuration:

1. Install Neofetch
Ensure Neofetch is installed on your system. Use the appropriate command for your distribution:

bash
Copy code
# Debian/Ubuntu
sudo apt update && sudo apt install neofetch

# Fedora
sudo dnf install neofetch

# Arch Linux
sudo pacman -S neofetch

# macOS (via Homebrew)
brew install neofetch
2. Clone This Repository
Clone the repository to your local system:

bash
Copy code
git clone https://github.com/your-username/neofetch-custom-config.git
cd neofetch-custom-config
3. Backup Your Existing Configuration
If you already have a Neofetch configuration, back it up before proceeding:

bash
Copy code
mv ~/.config/neofetch/config.conf ~/.config/neofetch/config.conf.bak
4. Install the Custom Configuration
Copy the provided configuration file into Neofetch's config directory:

bash
Copy code
mkdir -p ~/.config/neofetch
cp config.conf ~/.config/neofetch/config.conf
Usage
Run Neofetch to see the custom configuration in action:

bash
Copy code
neofetch
Troubleshooting
If the custom ASCII logo does not display correctly, ensure your terminal supports ASCII art rendering.
If Neofetch does not detect your hardware correctly, try running it with sudo for elevated permissions:
bash
Copy code
sudo neofetch
Contributing
Feel free to open an issue or submit a pull request if you'd like to suggest improvements or report bugs.

License
This project is licensed under the MIT License.
