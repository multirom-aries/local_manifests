# local_manifests for xiaomi aries(MI-2S)

```
$cd $(TOP_ANDROID_SRC)
$git clone git@github.com:multirom-aries/local_manifests.git -b cm-14.0-caf .repo/local_manifests
$cd .repo
$ln -s ./local_manifests/roomservice.xml ./local_manifest.xml
$cd .. &&repo sync
```
