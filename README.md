# local_manifests for msm8226 Motorola devices

LineageOS 23.2 (Android 16) for the Moto G 2013 (**falcon**) and the Moto G
LTE (**peregrine**), on their 3.4 kernel.

```sh
git clone https://github.com/Moto-Legacy/local_manifests -b lineage-23.2 .repo/local_manifests
```

The full build steps, including the patches this needs, are in
[patches](https://github.com/Moto-Legacy/patches#building-for-the-moto-g-2013-falcon--moto-g-lte-peregrine).

## Trees

| Path | Forked from |
|---|---|
| kernel/motorola/msm8226 | [voidanix](https://github.com/voidanix/android_kernel_motorola_msm8226) (lineage-17.1) |
| device/motorola/msm8226-common | [voidanix](https://github.com/voidanix/android_device_motorola_msm8226-common) (lineage-17.1) |
| device/motorola/falcon | [MotoDevelopment](https://github.com/MotoDevelopment/android_device_motorola_falcon) (lineage-16.0) |
| device/motorola/peregrine | [sevenrock](https://github.com/sevenrock/android_device_motorola_peregrine) (lineage-16.0) |
| vendor/motorola | [TheMuppets](https://github.com/TheMuppets/proprietary_vendor_motorola) (lineage-17.1) |

The msm8974 HALs come from
[Oichkatzelesfrettschen](https://github.com/Oichkatzelesfrettschen) and
`dtbtool` from LineageOS 18.1.
