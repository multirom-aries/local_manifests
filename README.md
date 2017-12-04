# local_manifests for xiaomi aries(MI-2S)

# Use ssh to sync it (You have to add ssh pub_key to github.com account)
```
$cd $(TOP_ANDROID_SRC)
$git clone git@github.com:sancao2/local_manifests.git -b lineage-15.0 .repo/local_manifests
$repo sync
```

# use https to sync it 
```
$cd $(TOP_ANDROID_SRC)
$git clone https://github.com/sancao2/local_manifests.git -b lineage-15.0 .repo/local_manifests
$repo sync
```
