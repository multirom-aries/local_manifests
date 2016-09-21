# local_manifests for xiaomi aries(MI-2S)

# Use ssh to sync it (You have to add ssh pub_key to github.com account)
```
$cd $(TOP_ANDROID_SRC)
$git clone git@github.com:multirom-aries/local_manifests.git -b cm-14.0-caf-new .repo/local_manifests
$repo sync
```

# use https to sync it 
```
$cd $(TOP_ANDROID_SRC)
$git clone https://github.com/multirom-aries/local_manifests.git -b cm-14.0-caf-new .repo/local_manifests
$repo sync
```
