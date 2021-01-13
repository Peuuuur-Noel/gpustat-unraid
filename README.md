# gpustat-unraid
An UnRAID plugin for displaying GPU status

## Manual Installation
    - Verify you have Unraid-Nvidia Build 6.7.1+ Installed
    - Within UnRAID Web UI navigate to Plugins -> Install Plugin
    - Enter https://raw.githubusercontent.com/b3rs3rk/gpustat-unraid/master/gpustat.plg
    - Select Install
    - Navigate to Settings -> GPU Statistics and select vendor (only choice is NVIDIA at this time)
    - Select Done
    - Navigate to Dashboard and look at the top of the leftmost panel for the GPU widget

If any issues occur, visit the support thread [here](https://forums.unraid.net/topic/89453-plugin-gpu-statistics/ "[PLUGIN] GPU Statistics").

## Current Support

    NVIDIA:
        - GPU/Memory Utilization
        - GPU/Memory Clocks
        - Encoder/Decoder Utilization
        - PCI Bus Throughput
        - Temperature
        - Fan Utilization
        - Power Draw
        - Power State
        - Throttled (Y/N) and Reason for Throttle
        - Active Process Count

    Intel:
        - 3D Render Engine Utilization
        - Blitter Engine Utilization
        - Video Engine Utilization
        - VideoEnhance Engine Utilization
        - IMC Bandwidth Throughput
        - Power Draw and Power Demand (rc6 slider)
        - GPU Clock
        - Interrupts per Second

The bulk of this code was adapted from/inspired by @realies and @CyanLabs corsairpsu-unraid project!

## Contributor Thanks

    * Thanks to @mlapaglia for his work on UI slider bars!
    * Thanks to @ich777 for his help with iGPU testing setup!
