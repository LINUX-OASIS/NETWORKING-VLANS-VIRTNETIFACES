# 🌐 Virtual Network Interface & VLAN Manager  VLANs-VIRTNETIFACES

<p align="center">
  <img src="https://raw.githubusercontent.com/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES/main/.github/VIRTUAL-NIC-VLAN-MANAGER.png" alt="Project Banner" width="600"/>
</p>

<p align="center">
  A powerful Bash script with a friendly `whiptail` TUI to automate the creation, deletion, and management of virtual network interfaces on Linux.
</p>

<p align="center">
  <!-- License -->
  <a href="https://github.com/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES?style=for-the-badge&color=blue" alt="License">
  </a>
  <!-- Issues -->
  <a href="https://github.com/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES/issues">
    <img src="https://img.shields.io/github/issues/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES?style=for-the-badge&color=brightgreen" alt="Issues">
  </a>
  <!-- Pull Requests -->
  <a href="https://github.com/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES/pulls">
    <img src="https://img.shields.io/github/issues-pr/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES?style=for-the-badge&color=9cf" alt="Pull Requests">
  </a>
  <!-- Stars -->
  <a href="https://github.com/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES/stargazers">
    <img src="https://img.shields.io/github/stars/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES?style=for-the-badge&color=gold" alt="Stars">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-Bash-4EAA25.svg?style=flat-square&logo=gnu-bash&logoColor=white" alt="Made with Bash">
  <img src="https://img.shields.io/badge/OS-Linux-blue?style=flat-square&logo=linux" alt="Linux OS">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-green.svg?style=flat-square" alt="Maintained">
</p>

---

## ✨ About The Project

Ever needed to use a single Wi-Fi adapter in multiple modes simultaneously, like being connected to a network while also running a monitor-mode interface for packet sniffing? Or perhaps you need to quickly spin up a VLAN for network segmentation? This script is your solution!

`NETWORKING-VLANS-VIRTNETIFACES` provides an easy-to-use, menu-driven terminal interface to manage virtual network devices without memorizing complex `ip` and `iw` commands.

### 🚀 Key Features

*   **Create Virtual Interfaces**:
    *   Create virtual **Wi-Fi** interfaces (`managed`, `monitor`, `AP`).
    *   Create virtual **Ethernet** interfaces like VLANs or MACVLANs. *(Ethernet creation is a planned feature)*.
*   **Delete Interfaces**: Cleanly remove any network interface, virtual or physical.
*   **Rename Interfaces**: Easily rename network interfaces to something more memorable.
*   **Check Wi-Fi Capabilities**: Inspect your wireless adapter to see what interface combinations and modes it supports (e.g., AP + Station).
*   **Dependency Auto-Installer**: Automatically checks for and installs required packages.
*   **Colorful TUI**: A visually organized `whiptail` interface for a smooth user experience.

---

## 🖥️ Compatibility

This script is designed for Debian-based Linux distributions that use the `apt` package manager. It has been tested and is expected to work on:

<p align="left">
  <a href="https://www.debian.org/" target="_blank"><img src="https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white" alt="Debian"></a>
  <a href="https://ubuntu.com/" target="_blank"><img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu"></a>
  <a href="https://linuxmint.com/" target="_blank"><img src="https://img.shields.io/badge/Linux%20Mint-87CF3E?style=for-the-badge&logo=linuxmint&logoColor=white" alt="Linux Mint"></a>
  <a href="https://www.kali.org/" target="_blank"><img src="https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white" alt="Kali Linux"></a>
</p>

...and other Debian derivatives.

---

## 🛠️ Prerequisites & Dependencies

The script relies on a few core command-line tools.

*   `lshw` - To list hardware, including network devices.
*   `iw` - For managing wireless devices.
*   `whiptail` - To display dialog boxes from shell scripts.

Don't worry about checking for them yourself! The script will automatically detect any missing dependencies and prompt you to install them.

---

## ⚙️ Installation & Usage

Getting started is simple. Just clone the repository and run the script with `sudo`.

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES.git
    ```

2.  **Navigate to the directory:**
    ```sh
    cd NETWORKING-VLANS-VIRTNETIFACES
    ```

3.  **Make the script executable:**
    ```sh
    chmod +x custom-NETWORKING-VLANS-VIRTNETIFACES.sh
    ```

4.  **Run the script with root privileges:**
    > **Note:** `sudo` is required for installing dependencies and managing network interfaces.
    ```sh
    sudo ./custom-NETWORKING-VLANS-VIRTNETIFACES.sh
    ```
    
    You will then be greeted by the main menu. Follow the on-screen prompts to manage your network interfaces!

---

## 💬 Contributing

Pull requests, issues, and feature suggestions are warmly welcomed! We believe in the power of community collaboration to make this tool even better.

For major changes, please open an issue first to discuss what you would like to change. See **CONTRIBUTING.md** for detailed guidelines.

---

## 🌐 Links

*   [**Open an Issue**](https://github.com/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES/issues)
*   [**View Pull Requests**](https://github.com/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES/pulls)
*   [**See Releases**](https://github.com/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES/releases)
*   [**Project Wiki**](https://github.com/LINUX-OASIS/NETWORKING-VLANS-VIRTNETIFACES/wiki)

---

## 📜 License

This project is distributed under the **GNU General Public License v3.0**. See `LICENSE` for more information.

---

## 🧙‍♂️ Maintainer

This project is proudly maintained by:

[**LINUX-OASIS**](https://github.com/LINUX-OASIS)

<p align="center">Made with ❤️ and a lot of coffee.</p>
