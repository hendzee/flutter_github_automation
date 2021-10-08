# Futter Github Automation(CI/CD)
> This file are used to test and build flutter APK automatically

## Job List
- Testing
- Build release apk

## How to Use
- Copy this yml file to the .github directory so it will looks like
```
.
├── ...
├── .github
│   ├── android_release.yml
└── ...
```
- Create github token, at this link: [https://github.com/settings/tokens](https://github.com/settings/tokens)
- Then, copy token to your "Secret" menu at your repository
- Make tag then upload to the repository, for example:
```
git tag -a "v1.0" -m "My first tag"
```
```
git push origin v1.0
```
- Select action tab at your repository page, you will see automation will be running