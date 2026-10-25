# local_manifest

Evolution X (Android 17) for Xperia 1 II (pdx203) 用の local manifest です (branch `cnb`)。

```sh
git clone -b cnb https://github.com/REvoX-Devices/local_manifest .repo/local_manifests
repo sync -c -j6 --force-sync --no-clone-bundle --no-tags
```

`vendor_sony_so51a` は private のため、GitHub の認証が必要です。
