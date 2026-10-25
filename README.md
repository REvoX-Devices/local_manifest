# local_manifest

## Build

```sh
source build/envsetup.sh
lunch lineage_pdx203-cp2a-userdebug
m evolution
```

## KernelSU

`kernel/sony/sm8250` の `revision` で切り替えます。

| revision | 内容 |
|---|---|
| `cnb` | KernelSU なし |
| `cnb-kernelsu` | KernelSU-Next (legacy) 入り。manager は v3.4.2 (UAPI 5) |

`manifest.xml` は `cnb-kernelsu` です。KernelSU を使わない場合は、`android_kernel_sony_sm8250` の行を `revision="cnb"` に変えて `repo sync` してください。
