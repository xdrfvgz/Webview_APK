# Webview_APK

**Webview_APK** is an Android application that uses a WebView component to display web content within the app.

## Steps to Customize and Build Your APK

Follow these instructions to fork the repository, make custom edits, and build your APK using GitHub Actions.

### 1. Fork the Repository

- Navigate to the [Webview_APK repository](https://github.com/xdrfvgz/Webview_APK/).
- Click on **"Fork"** in the top-right corner to create a copy of the repository in your GitHub account.

### 2. Edit the Application Name

- Open the `strings.xml` file located in `app/src/main/res/values/`.
- Modify the `<string name="app_name">` value to change the name of the application.

### 3. Edit the URL

- Open `MainActivity.java`.
- Change the URL in the code to point to the web address you want the app to display.

### 4. Trigger GitHub Actions for Build Process

- Commit and push your changes to your forked repository.
- Go to the **"Actions"** tab in your repository.
- Select the workflow that builds the APK and wait for the build process to complete.

### 5. Download the APK

- Once the build process finishes, click on the most recent completed workflow run.
- Scroll down to the **"Artifacts"** section.
- Download the APK file from the available artifact link.

## Installation

- Transfer the downloaded APK to your Android device.
- Open the APK on your device to install the app.

## License

This project is licensed under the [MIT License](LICENSE).
