# -GUIDelete
GUICtrlListView_AutoResizeColumn($hForm, $hListView)      GUISetState()      ; Loop until user exits     Do     Until GUIGetMsg() = $GUI_EVENT_CLOSE      GUIDelete() EndFunc   ;==>_Main
