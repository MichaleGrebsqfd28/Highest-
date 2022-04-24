# Highest-
 IntLenSort($vInput)      If Not IsArray($vInput) Then $vInput = StringSplit($vInput, Opt("GUIDataSeparatorChar"), $STR_NOCOUNT)      For $i = 0 To UBound($vInput) - 1 Step 1          If $i = 0 Then             Local $iHighest = $vInput[$i]             Local $iLowest = $vInput[$i]         EndIf
