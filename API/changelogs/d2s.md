# 22-Jul-2023
- Configure aux cameras for Aperture
- Face unlock now works fine (In the last update PixelOS switched to AOSPA's face unlock implementation, ParanoidSense)
- Fix Widevine/Netflix (Thanks @Linux4)
- Update kernel to Linux 4.14.320

# 23-Apr-2023
- Compile the kernel without GCC
- Replace libutils-v32 with a shim
- Update blobs from *HWA1/*HWA3
- Update kernel to Linux 4.14.310
- Use linaro BSP

# 23-Feb-2023
- Fix NFC
- Revert SkiaGL stuff (causes lags)
- Disable blur for now (causes lags)

# 22-Feb-2023
- Add manually missing apn configs (4G/LTE and SMS fixed)
- Disable VSync for CPU rendered apps
- Enable zygote critical window 
- Switch to SkiaGL as HWUI renderer
- Update kernel to Linux 4.14.305
- Initial official release

