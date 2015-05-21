# android_device_motorola_surnia

Device tree for Surnia (Moto E 2015 LTE) and its variants.



```
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
     <remove-project name="platform/external/libxml2" />
    <!-- Motorola Surnia -->

    <project path="external/libxml2" name="CyanogenMod/android_external_libxml2" groups="pdk-cw-fs" revision="cm-12.1" />
    <project path="device/motorola/surnia" name="Motorola-CyanogenMod/android_device_motorola_surnia" remote="github" revision="aosp-5.1" />
    <project path="kernel/motorola/surnia" name="Motorola-CyanogenMod/android_kernel_motorola_msm8916" remote="github" revision="cm-12.1" />
    <project path="vendor/motorola/surnia" name="Motorola-CyanogenMod/android_vendor_motorola_surnia" remote="github" revision="cm-12.1" />
    <project name="CyanogenMod/android_device_qcom_common" path="device/qcom/common" remote="github" revision="cm-12.1" />
    <project name="CyanogenMod/android_hardware_qcom_fm" path="hardware/qcom/fm" remote="github" revision="cm-12.1" />
    <project name="CyanogenMod/android_hardware_qcom_audio" path="hardware/qcom/audio-caf/msm8916" remote="github" revision="cm-12.1-caf-8916" />
    <project name="CyanogenMod/android_hardware_qcom_display" path="hardware/qcom/display-caf/msm8916" remote="github" revision="cm-12.1-caf-8916" />
    <project name="CyanogenMod/android_hardware_qcom_media" path="hardware/qcom/media-caf/msm8916" remote="github" revision="cm-12.1-caf-8916" />

</manifest>

```
