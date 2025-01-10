# VzBoT UserMods repository

Welcome to the VzBoT UserMods repository, here you may find community mods for the VzBoT 3D-printer.

<a href="https://discord.gg/Jj5C7q4j" target="_blank">![Discord Shield](https://discord.com/api/guilds/829828765512106054/widget.png?style=banner2)</a>

*Remember to update this README when uploading new mod!*

There is a [contributing guide available here](./CONTRIBUTING.md).

## Directory structure

Create a folder containing your name (without spaces) and create a folder for your mod(s).

Suggested directory layout for your mod:
- creator_name/
  - mod_name/
    - README.md with a description, optionally build instructions and required parts
    - stl/ folder with stereolithographical models, oriented correctly for printing
    - cad/ folder with original design files (STEP, F3D, Scad, etc.) (optional)
    - doc/ folder with supported documentation (optional)
    - images/ folder with screen shots/renders/etc.

## Table structure

Update the following table with the information about your mod:
- Your name
- A link to your sub-folder
- A short description of your mod
- The build difficulty:
  - :green_heart: for :green_heart: (Easy)
  - :blue_heart: for :blue_heart: (Intermediate)
  - :heart: for :heart: (Advanced)

like so:
`
| Creator | [Mod title](link) | ✔️/✖️ | ✔️/✖️ | Description | Difficulty `

---

## Mods

| Creator | Mod title | Description | [Vz330](https://github.com/VzBoT3D/VzBoT-Vz330) | [Vz235](https://github.com/VzBoT3D/VzBoT-Vz235) | Difficulty
| --- | --- | --- | --- | --- | --- |
| example    | [Example mod](./creator_here/mod_folder_name)| Example entry for the table | ✔️ | ✔️ | :green_heart::blue_heart::heart: |
| airox    | [VZ235 Tophat](./airox/vz235_tophat)| A tophat for the vz235 | ✖️ | ✔️ | :green_heart: |
| AdderMk2   | [Patch_Cura](./AdderMk2/Patch_Cura) | Updates 2020 Tronxy profiles in Cura | ✔️ | ✔️ | :blue_heart: |
| CapnKrunchy | [Aluminum Z WAGO Mount](./CapnKrunchy/Aluminum_Z_WAGO_Mount) | WAGO mount for Aluminum Z bed assembly | ✔️ | ✖️ | :green_heart: |
| catalinutzz| [Hemera mount](./catalinutzz/hemera-mount) | Hemera mount for the VZ Printhead | ✔️ | ✔️ | :green_heart: |
| ckvsoft    | [CPAP_back_panel_tube_mount_VZ330](./ckvsoft/CPAP_back_panel_tube_mount_VZ330)| CPAP back panel tube mount VZ330. | ✔️ | ✖️ | :green_heart: |
| ckvsoft    | [WaveShare](./ckvsoft/waveshare_5inch_DSI_LCD)| WaveShare 5inch DSI LCD. | ✔️ | ✔️ | :green_heart: |
| der-pw    | [HBVCam-3M2111_corner-mount](./der-pw/HBVCam-3M2111_corner-mount)| HBVCam-3M2111 corner-mount | ✖️ | ✔️ | :green_heart: |
| EduardoMDSousa  | [Vz-Printhead Printed MGN12H](./EduardoMDSousa/Vz-Printhead-Printed-MGN12H) | VzPrinthead Printed MGN12H | ✔️ | ✔️ | :green_heart: |
|                 | [Vz-Printhead-Printed_Standoffs-MGN12](./EduardoMDSousa/Vz-Printhead-Printed_Standoffs-MGN12) | Vz-Printhead-Printed_Standoffs-MGN12 | ✔️ | ✔️ | :green_heart: |
|                 | [Vz-Printhead-Printed-MGN12H-Orbiter-1.5-Mood](./EduardoMDSousa/Vz-Printhead-Printed-MGN12H-Orbiter-1.5-Mood) | Vz-Printhead-Printed-MGN12H-Orbiter-1.5-Mood | ✔️ | ✔️ | :green_heart: |
| | [Vz-Printhead Printed Standoffs MGN12](./EduardoMDSousa/Vz-Printhead-Printed_Standoffs-MGN12) | Vz-Printhead Printed Standoffs MGN12 | ✔️ | ✔️ | :green_heart: |
|Glizzynator | [M4_Spool_Holder](./Glizzynator/M4_Spool_Holder)| Modifies the spool holder to use M4 screws instead of M3 | ✔️ | ✔️ | :green_heart: |
| jpbnto     | [Y endstop](./jpbnto/yendstop) | Y-endstop using the Tronxy XS5A switch | ✔️ | ✖️ | :green_heart: |
| | [VzHextrudort heavy back plate](./jpbnto/vzhextrudort_heavy_back_plate) | Y-endstop using the Tronxy XS5A switch | ✔️ | ✖️ | :green_heart: |
| jurisv      | [SLA CPAP Trihorn](./jurisv/sla_cpap_trihorn)                             | CPAP Trihorn Fan ducts for SLA printers as single piece          | ✔️ | ✖️ | :green_heart: |
| karnadi    | [NF Crazy front face](./karnadi/NF_Crazy_2510_BLTouch) | NF Crazy front face 2510 fan with BLTouch mount | ✔️ | ✔️ | :green_heart: |
|            | [VzHextrudort pneumatic coupler](./karnadi/VzHextrudort_pneumatic_coupler) | VzHextrudort pneumatic PTFE coupler | ✔️ | ✔️ | :green_heart: |
| keefo      | [vent hose adapter](./keefo/vent_hose_adapter) | vent hose adapter | ✔️ | ✖️ | :green_heart: |
| knarfie    | [12mm Linear Rod](./knarfie/12mm_rods) | Mod for 12mm linear rods | ✔️ | ✖️ | :green_heart: |
|            | [Idler Shoulder](./knarfie/shoulder_idler) | Idler mounts with spots for shoulder bolts  | ✔️ | ✖️ | :green_heart: |
|            | [Trihorn](./knarfie/trihorn_duct) | Trihorn duct for the VZ Printhead | ✔️ | ✔️ | :green_heart: |
| MadduxVape | [Vz330 Duet Config](./MadduxVape) | Vz330 AWD Config for Duett board| ✔️ |  ✖️ | :green_heart: |
| marbocub   | [Vz330 Y-Gantry-1515](./marbocub/Vz330_Y-Gantry-1515) | Vz330 Y-Gantry for 1515 size gantry | ✔️ |  ✖️ | :green_heart: |
| mdwasp     | [Swappable Exhaust Tube](./mdwasp/swappable_exhaust_tube) | Hot-swappable exhaust tube | ? | ✔️ | :green_heart: |
| panik988   | [Sherpa + NF Crazy front face (bracket)](./panik988/sherpa_nf_crazy_bracket) | NF Crazy Face Mount with bracket for Sherpa | ✔️ | ✔️ | :green_heart: |
| pbsuper    | [VZTrident](./pbsuper/VZTrident)| Tripple Z for VZbot complete printer. | ✔️ | ✔️ | :blue_heart: |
|            | [Quickdraw](./pbsuper/Quickdraw)| Quickdraw for Alu Printhead. | ✔️ | ✔️ | :green_heart: |
|            | [Brace_Dancer](./pbsuper/Brace_Dancer)| Brace for Dancer so Fanduct can't move sideways. | ✔️ | ✔️ | :green_heart: |
| Polar_Ted  | [VZ HextrudORT mount](./Polar_Ted/VZ_HextrudORT_High_Motor_Mount_for_EVA/) | VZ HextrudORT high motor mount for EVA print head and V6 hot end | ✔️ |  ✔️ | :green_heart: |
|            | [VZ Sexbolt Z Endstop](./Polar_Ted/Sexbolt_Sidepiece_Z_Switch/) | Sexbolt side mounted Z endstop for VZ bed frame  | ✔️ |  ✔️ | :green_heart: |
|            | [VZ 330 Skirt Set](./Polar_Ted/VZ330_skirt/ ) | VZ 3330 SKirt Set with V0 Display | ✔️ | ✖️ | :green_heart: |
|            | [X_Y_Pully_Height_Gauge](./Polar_Ted/X_Y_Pully_Height_Gauge/) | X Y pully height gauge  | ✔️ |  ✔️ | :green_heart: |
|            | [X_Y Motor Support](./Polar_Ted/X_Y_Motor_support/) | Support shelf for X and Y motors  | ✔️ |  ✔️ | :green_heart: |
| Rac        | [MGN9 Gantry](./Rac/MGN9_gantry) | MGN9 gantry | ✔️ | ✔️ | ✖️ | :blue_heart: |
| rilmar     | [X5SA Z](./rilmar/X5SA_Z) | X5SA Z | ✔️ | ✔️ | :green_heart: |
| RODAM 3D   | [180_Hinges](./RODAM_3D/180_Hinges/) | 180 Hinges for full door open  | ✖️ |  ✔️ | :green_heart: |
|            | [2WD_2_COLOR_SCREW_PACK](./RODAM_3D/2WD_2_COLOR_SCREW_PACK/) | 2 color Idler with mod for screw kit  | ✖️ |  ✔️ | :green_heart: |
| SFINAE     | [Rapido HF mount](./SFINAE/Rapido_HF_30mm_fan) | Rapido HF mount for 30mm fan | ✔️ | ✔️ | :green_heart: |
| Skysi      | [Beefy X-Endstop](./Skysi/Beefy%20X-Endstop) | Beefed up Enstop for X | ✔️ | ✔️ | :green_heart: |
| SSerpente  | [Klicky probe](./SSerpente/Klicky%20probe%20Vzbot) | Klicky probe mount | ✔️ | ✔️ | :green_heart: |
| treintjes  | [Skirt](./treintjes/VzBot_Skirt) | Skirt for the VZ-Bot to house electronics under the frame | ✔️ |  ✖️ | :green_heart: |
| MadduxVape | [Vz330_Duet_Config](./MadduxVape) | Vz330 AWD Config for Duett board| ✔️ |  ✖️ | :green_heart: |
| zxzimeng  | [12mm rod aligner](./zxzimeng/12mm_aligner/) | 12mm Z Rod Aligner  | ✖️ |  ✔️ | :green_heart: |
| edsped    | [Bowden Clip Adpater](./edsped/Bowden Adapter/) | Bowden Collet Adapter | | | | | :green_heart:|
---

<sub>Credits to [VoronDesign/VoronUsers](https://github.com/VoronDesign/VoronUsers)</sub>
