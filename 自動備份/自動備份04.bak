[General]
SyntaxVersion=2
BeginHotkey=121
BeginHotkeyMod=0
PauseHotkey=0
PauseHotkeyMod=0
StopHotkey=123
StopHotkeyMod=0
RunOnce=1
EnableWindow=
MacroID=3fdd5cc2-5934-4f51-8e26-2020a32d33ff
Description=報復性熊貓
Enable=1
AutoRun=0
[Repeat]
Type=1
Number=1
[SetupUI]
Type=2
QUI=
[Relative]
SetupOCXFile=
[Comment]

[Script]

//先隨便點一下
MoveTo 405, 135
Delay 50
LeftClick 1
Delay 100

//點擊重整
FindPic 533, 118, 580, 163, "C:\Users\hankh\Desktop\foodpanda\update.bmp", 0.8, intX, intY
If intX > 0 And intY > 0 Then 

	MoveTo 552, 141
	Delay 50
	LeftClick 1
	Delay 2000

	//滾輪
//	MoveTo 249,545
//	Delay 200
//	MouseWheel - 1
//	Delay 200

	//執行2次
	For 2
		//	尋找"交換時段"圖片，開搶
		FindColorEx 450,317,569,1057,"AD7F59",0,0.9,intX,intY //模糊找色
		If intX > 0 And intY > 0 Then 
			MoveTo intX+40, intY+5
			Delay 50
			LeftClick 1
			Delay 125
			
			//選時段按鈕
//			MoveTo 403,435
//			Delay 100
//			LeftClick 1
//			Delay 150
			
			//取消按鈕
			MoveTo 174,437
			Delay 100
			LeftClick 1
			Delay 150
	
			//點旁邊跳開，以防沒搶到
			MoveTo 405,135
			Delay 50
			LeftClick 1
			Delay 100
			
			//選完後滑移下滾輪
//			MoveTo 174,437
//			Delay 100
//			MouseWheel - 1
//			Delay 200
		End If
	Next

End If

Delay 300




