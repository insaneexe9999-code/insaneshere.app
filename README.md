# INSANE SHARE — Android Build Project

This is a GitHub Actions-ready Android Studio project for **INSANE SHARE**.

## Build the APK online with GitHub Actions

1. Create a new GitHub repository.
2. Upload the entire contents of this project.
3. Open **Actions**.
4. Choose **Build INSANE SHARE APK**.
5. Run the workflow.
6. When it finishes, open the workflow run and download the APK from **Artifacts**.

The app is a WebView wrapper around the INSANE SHARE web interface and includes Internet access for the PeerJS/WebRTC connection.

## Important

The app needs an internet connection for peer discovery/signaling. The file transfer is intended to happen peer-to-peer through WebRTC where the network allows it.

Do not upload the ZIP itself into the repository. Upload the project files/folders so GitHub can see `.github/workflows/build-apk.yml` and `app/`.
