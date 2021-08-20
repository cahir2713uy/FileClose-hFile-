# FileClose-hFile-
$hFile = FileOpen($sFileName, $FO_BINARY)
$bContent[17] = 'a'    ; Obviously this doesn't work.
$bContent[18] = 'b'
$bContent[19] = 'c'
