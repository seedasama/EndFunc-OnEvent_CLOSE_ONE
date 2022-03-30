# EndFunc-OnEvent_CLOSE_ONE
  WEnd     $iExitLoop = 0     GUIDelete($hGUIParent2) EndFunc   ;==>Example2   Func OnEvent_CLOSE_ONE()     ConsoleWrite('- Func OnEvent_CLOSE_ONE()' &amp; @CRLF)     $iExitLoop = 1 EndFunc   ;==>OnEvent_CLOSE_ONE  Func OnEvent_CLOSE_TWO()     ConsoleWrite('- Func OnEvent_CLOSE_TWO()' &amp; @CRLF)
