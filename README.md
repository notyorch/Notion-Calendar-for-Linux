# Notion Calendar for Linux (Electron App)

This project provides an unofficial desktop application for Notion Calendar on Linux. I created this to have a secure and native-like experience for my daily planning, separate from the browser. The app uses the official Notion Calendar web client, ensuring a safe and reliable experience.

## ✨ Features

* **Secure**: Wraps the official Notion Calendar web app, keeping your data safe and sound.
* **Native-like Experience**: Works as a standalone desktop application, making it feel more integrated with your Linux environment.
* **Lightweight**: Focused on performance, providing a smooth user experience without unnecessary features.
* **Customizable**: Built with Electron Forge, allowing for easy customization of app name and icon.

## 🚀 How to Install

Follow these steps to install the Notion Calendar Electron app on your Debian/Ubuntu-based system:

1.  **Download the latest `.deb` package**:
    Go to the [Releases](https://github.com/notyorch/Notion-Calendar-for-Linux/releases) section of this repository and download the most recent `.deb` file.

2.  **Open your terminal**:
    Navigate to the directory where you downloaded the `.deb` file (e.g., `cd ~/Downloads`).

3.  **Install the application**:
    Use `dpkg` to install the package, and `apt-get -f install` to resolve any missing dependencies.

    ```bash
    sudo dpkg -i notion-calendar_1.0.0_amd64.deb # Replace with the actual filename
    sudo apt-get install -f
    ```

4.  **Launch Notion Calendar**:
    Once installed, you can find "Notion Calendar" in your applications menu and launch it like any other desktop application.

## 🛠️ How to Build from Source (for Developers)

If you wish to build the application yourself or contribute, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/notyorch/Notion-Calendar-for-Linux.git](https://github.com/notyorch/Notion-Calendar-for-Linux.git)
    cd Notion-Calendar-for-Linux
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Run the app in development mode**:
    ```bash
    npm start
    ```

4.  **Package the app for distribution (e.g., `.deb`)**:
    ```bash
    npm run make
    ```
    The `.deb` file will be generated in the `out/make/deb` directory.

## 🤝 Contributing

Contributions are welcome! If you have suggestions, bug reports, or want to improve the code, feel free to open an issue or submit a pull request.

## ✉️ Connect with me

<p align="left">
  <a href="https://www.linkedin.com/in/jorgeenriquevp/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
</p>

---

**Disclaimer**: This is an unofficial Electron wrapper for Notion Calendar and is not affiliated with or endorsed by Notion Labs, Inc.
