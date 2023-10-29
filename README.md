# SnapEnhanceModGen

This repository contains a GitHub Actions workflow for generating a Snapchat APK by using the [SnapEnhance Module](https://github.com/rhunk/SnapEnhance) and creating a public release.

## How to get MOD APK link
1. Install the latest [Snapchat MOD apk](https://github.com/hamzaharoon1314/SnapEnhanceModGen/releases)
2. Install the latest [SnapEnhance apk](https://github.com/rhunk/SnapEnhance/releases/latest)
   - (If you don't know what version (armv8 or armv7) to download, check out [this app](https://play.google.com/store/apps/details?id=com.abs.cpu_z_advance&hl=de&gl=US) and go into the CPU tab it will show you which version your phone supports)
4. Done - ~have fun.
![MOD APK Image](REDME_IMG/modapk.png)   

## Instructions for own Setup

1. **Fork this Repository**: Click the "Fork" button to create your copy of this repository.

2. **Push Trigger**: The workflow is triggered when you push changes to your repository in a file named `push-here.md`. You can adjust this path in the workflow configuration (`on` section).

3. **Download the Release**: After the workflow completes, you can find the modified APK under the "Releases" tab.
![MOD APK Image](REDME_IMG/modapk.png) 
## Customization

- You can customize the release tag and name by editing the `.github/workflows/main.yml` file.
- Modify the `tag_name` and `release_name` values in the "Create Release" step.

## Contributing

You can feel free to contribute to this project by opening issues and pull requests.

