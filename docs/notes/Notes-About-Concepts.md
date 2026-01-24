# Notes

These are just general notes

- When routing `USB Differential pairs`, try to keep the length UNDER `10mm`
- When routing signals, ALWAYS have a ground plane underneath, it cannot be broken up
- When jumping between planes for signals, use `Transfer Vias` to keep the vertical via coupled to ground
- When doing a 4-Layer board, note about `Copper Imbalance`, basically just do a copper pour on L1
    - For the clearance, make sure it's around `3x` the L1 Dielectric thickness. Around `0.35 - 0.4mm` is okay