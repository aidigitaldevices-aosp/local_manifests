 Refer to http://source.android.com/source/downloading.html

```shell
repo init -u https://android.googlesource.com/platform/manifest --depth=1 -b android-16.0.0_r4
git clone git@github.com:aidigitaldevices-aosp/local_manifests.git .repo/local_manifests -b master
repo sync
```