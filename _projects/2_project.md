---
layout: page
title: Run RISC-V core on FPGA evalutation board 
description: what? you mean FPGA can run another standalone soft core? 
img: assets/img/HBSoC/evb.png
importance: 2
category: work
giscus_comments: true
---

Project Overview:
Ported an open-source RISC-V soft-core microprocessor onto the Xilinx FPGA development platform, successfully extending the computational capabilities of a parent-child development board. Optimized the collaboration between the soft-core and onboard resources to ensure stable system operation.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/HBSoC/hbsoc.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    System schematic view
</div>


Engineered the porting of an open-source RISC-V soft-core microprocessor onto a Xilinx FPGA platform, unlocking additional computational power on a parent-child development board while finely tuning the synergy between the soft-core and onboard resources for rock-solid performance. Overcame complex hardware compatibility challenges by optimizing bus configurations, synchronizing clocks, and integrating Xilinx IP cores (DMA, AXI-GPIO, AXI-BRAM) for flawless peripheral communication. 


Verified the system’s integrity using oscilloscopes, multimeters, and JTAG debugging, successfully running C-language executables on the soft-core and laying the groundwork for advanced heterogeneous system development. This project not only formalized a reliable methodology for FPGA-based RISC-V soft-core deployment but also demonstrated scalable, high-performance embedded system design in practice. 