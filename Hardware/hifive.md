---
riscv_hardware: true
cmake_plat: hifive
xcompiler_arg: -DRISCV64
platform: HiFive Unleashed
arch: RISC-V, RISCV64
virtualization: "No"
iommu: "No"
simulation_target: false
Status: "Unverified"
Contrib: "Data61"
Maintained: "Data61"
soc: SiFive Freedom U540 SoC
cpu:  U54-MC
---

# HiFive Unleashed

Using the U-Boot bootloader.

{% include risc-v.md %}

## Building seL4test

{% include sel4test.md %}
 