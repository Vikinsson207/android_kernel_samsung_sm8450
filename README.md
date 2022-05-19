## Kernel Source for Galaxy S22/+/Ultra, based on S906EXXS2AVDD

## Compile

```
cd android_kernel_samsung_sm8450
git clone https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86 kernel_platform/prebuilts-master/clang/host/linux-x86 --depth=1
./build_kernel_GKI.sh VARIANT

- VARIANT
 + b0q_gbl_openx : S22 Ultra Global
 + g0q_gbl_openx : S22+ Global
 + r0q_gbl_openx : S22 Global

```
