# Kernel for l1e 

### Changes

  * Enabled SELinux
  * Updated SELinux support up to policy 30
  * Changed to XZ compression due to recovery partition size limitation
  * Minor bug fixes

### Config

Architecture: `arm`

Kernel CFlags: `-w`

Configuration File: `l1e-perf_defconfig`

Cross compiler binary: `arm-eabi-`

Perl version: `5.24.1`
