LG P350 ICS Setup

Copy/paste it WORKING_DIR/.repo/local_manifest.xml

<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <project path="device/lge/msm7x27-common" name="lgics/cm_device_lge_msm7x27-common" remote="github" revision="master" />
  <project path="device/lge/p350" name="lgics/cm_device_lge_p350" remote="github" revision="master" />
  <project path="kernel/lge/msm7x27" name="lgics/lge-kernel-msm7x27" remote="github" revision="ics" />
  <project path="vendor/lge" name="lgics/cm_vendor_lge" remote="github" revision="master" />
</manifest>
