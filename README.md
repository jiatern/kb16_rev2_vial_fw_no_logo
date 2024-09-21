# kb16_rev2_vial_fw_no_logo
An expansion on thompson-vii's firmware. https://github.com/thompson-vii/kb16_rev2_vial_fw

Changes from thompson-vii's firmware.
- Added additional macro slots; currently at 64 slots
- Added additional tapdance slots.
- Expanded the memory avaliable to macros
- Disabled qmk features for firmware memory reduction
    - COMBO_ENABLE = 0
    - KEY_OVERRIDE_ENABLE = 0
- Reduced RGB modes for firmware memory reduction
- Added OLED timeout after 1000 ms
- OLED Brightness set to 88

Compiled using the https://github.com/vial-kb/vial-qmk repository.

Compiled firmware for doio's kb16 rev2

Not compatible with via. Must use vial.

Not compatible with rev1

Not compatible with wireless version.

Use qmk toolbox, hold top left key while plugging it in. Pick the bin file and click on flash. After flashing reconnect the usb cable. If everything goes well, you should see RGB pattern.


Credit:

- HorrorTroll: QMK port
- PHSC138: Pin schematic
- Kolloom: Vial port, graphics, layout
