# SnapEnhanceModGen

This repository contains a GitHub Actions workflow for generating a modified Snap-360-lspatched APK and creating a public release.

## How to get MOD APK link
1. Go to the Release tab and download/install the mod apk
2. Install the latest SnapEnhance apk
3. Done - ~have fun
![MOD APK Image](REDME_IMG/modapk.png)   

## Instructions for own Setup

1. **Fork this Repository**: Click the "Fork" button to create your copy of this repository.

2. **Set up Secrets**: In your forked repository, go to "Settings" > "Secrets" and add the following secrets:

   - `SNAP_ENHANCE_APK_URL`: The URL for the SnapEnhance APK. https://github.com/rhunk/SnapEnhance
   - `SNAP_APK_URL`: The URL for the Snap APK. https://www.apkmirror.com/apk/snap-inc/snapchat/
     ![SNAP APK Image](REDME_IMG/snapapk.png)  
   - You need to provide the direct link of apks so you can upload the Snapchat.apk on GitHub released tab and than use that link

3. **Trigger the Workflow**: Any push to your repository will trigger the GitHub Actions workflow. The workflow will download the required files, run the `java -jar lspatch.jar` command, and create a public release with the modified APK.

4. **Download the Release**: After the workflow completes, you can find the modified APK under the "Releases" tab.
![MOD APK Image](REDME_IMG/modapk.png) 
## Customization

- You can customize the release tag and name by editing the `.github/workflows/main.yml` file.
- Modify the `tag_name` and `release_name` values in the "Create Release" step.

## Contributing

You can feel free to contribute to this project by opening issues and pull requests.

