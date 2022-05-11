# -hBitmap
$hBitmap = _GDIPlus_BitmapCreateFromGraphics($iWidth, $iHeight, $hScreenGraphics) $hGraphics = _GDIPlus_ImageGetGraphicsContext($hBitmap) GUISetState() GUISetOnEvent(-3, "_Exit") Global $iLoopCurrent = 0 AdlibRegister("_FPS", 1000)
