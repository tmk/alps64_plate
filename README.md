AEK Plate for Alps64 PCB
========================
Two DXF files are available for Apple Exteded Keyboard layout. The difference is just spacebar part and other parts are identical.

Also check the first post of [Alps64 PCB thread](https://geekhack.org/index.php?topic=69740.0) at geekhack.org.

### alps64_plate_aek_flip_spacebar.dxf
Its dimensions is 95x285mm and total length of all paths is 4492mm for reference.
This supports 'flipped' and Dutch AEK spacebar in addition to US. This is preferable in most cases.
![](https://raw.githubusercontent.com/tmk/alps64_plate/plate_aek_flip_spacebar/alps64_plate_aek_flip_spacebar.png)

### alps64_plate_aek.dxf
Its dimensions is 95x285mm and total length of all paths is 4423mm for reference.
This is plain design for US AEK.
![](https://raw.githubusercontent.com/tmk/alps64_plate/plate_aek_flip_spacebar/alps64_plate_aek.png)



Revisions
---------
2020/04 Removed dimension drawings from alps64_plate_aek.dxf
2018/04 AEK plate with flipped spacebar support
2016/07 AEK plate



Export DXF
----------
### kicadpcb2dxf
how to launch:

    python kicadpcb2dxf.py -f alps64.kicad_pcb

- https://github.com/easyw/kicadpcb2dxf
- https://forum.kicad.info/t/dxf-exporter-for-mechanical-layers-of-kicad-pcb-board/2885


### Plot on KiCad Pcbnew
This seems to work with disabling 'Plot all layers in outline (polygon) mode' of DXF options.



Export Image
------------
Image file for reference can be created by 'export as image' of LibreCAD or 'Bitmap Export' of QCAD.



CAD Software
------------
### LibreCAD
https://librecad.org/

### QCAD
https://www.qcad.org/en/
