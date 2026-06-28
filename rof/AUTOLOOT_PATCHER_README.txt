AutoLoot client patch payload with explicit EQUI.xml include.

Install paths are relative to the EQ client root:
- dinput8.dll
- uifiles/default/EQUI.xml
- uifiles/default/EQUI_NativeAutoLootWnd.xml
- uifiles/default/EQUI_Animations.xml
- uifiles/default/EQUI_Templates.xml
- uifiles/default/nal_pieces07.tga
- uifiles/default/nal_pieces11.tga

This version includes uifiles/default/EQUI.xml with:
<Include>EQUI_NativeAutoLootWnd.xml</Include>

Players already in game need /loadskin default 1 or a full client restart after patching.
