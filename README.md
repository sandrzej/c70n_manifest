# c70n_manifest
Local manifest file for building LineageOS 15.1 for LG Spirit 4G LTE


### Initialize the LineageOS source repository

Enter the following to initialize the repository:
```
cd ~/android/system/
repo init -u git://github.com/LineageOS/android.git -b cm-14.1
```
### Get the required local manifest

```
mkdir -p ~/android/system/.repo/local_manifests
curl https://raw.githubusercontent.com/sandrzej/c70n_manifest/cm-14.1/local_manifest.xml > .repo/local_manifests/local_manifest.xml
