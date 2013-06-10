tmp
===

查看RMBP显示器型号
===
ioreg -lw0 | grep \"EDID\" | sed "/[^<]*</s///" | xxd -p -r | strings -6
 
 
LPXXXXX-XXXX -> LG 屏幕

LSXXXXX-XXXX -> Samsung 屏幕
