# AMD BC-250 Kernel Patch

This repository provides a custom kernel patch for **AMD BC-250 boards**, modifying the default GPU frequency limits to unlock additional performance.

## ⚙️ Patch Details

- **Max GPU Frequency**:  
  - Default kernel limit: **2000 MHz**  
  - Patched limit: **2230 MHz** (actual hardware maximum)

- **Min GPU Frequency**:  
  - Default kernel limit: **1000 MHz**  
  - Patched limit: **350 MHz** (allows deeper idle states)

This patch simply aligns the frequency range with what the hardware natively supports.

## ©️ Credits

  - [ViRazY](https://discord.com/channels/1315924807128449065/1398316687165624412)
