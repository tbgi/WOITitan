WOITitan
========
Global $Paused
HotKeySet("{PAUSE}", "TogglePause")
hotkeyset("{F11}", "Term")

$win_title = "Titanwoi"

WinActivate($win_title, "")
WinSetOnTop($win_title, "", 0)

$mob_found = 0
$mob_alive = 0
$char_alive = 0
$width = 250
$height = 28
;colorVariance zahl zwischen 5 und 15
$colourVariance = 0
$step = 1
;farbe vom Mob
$color = 0x9465ce
Sleep(5000)
$message = "DMG Buff Route TitanThron 2Mann"
$height = 38
update_splash()
Sleep(500)

While 1
  Sleep(Int(Random(500,1000)))
	maus()
	Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 1"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 1 lebt"
    update_splash()
	Sleep(600)
	WEnd
 EndIf

BU()

   maus2()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 2"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 2 lebt"
    update_splash()
	Sleep(600)
	WEnd
EndIf

	maus3()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 3"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 3 lebt"
    update_splash()
	Sleep(600)
	WEnd
EndIf

BU()

	maus4()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 4"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 4 lebt"
    update_splash()
	Sleep(600)
	WEnd
EndIf


	maus5()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 5"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 5 lebt"
    update_splash()
	Sleep(600)
	WEnd
EndIf

BU()

	maus6()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 6"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 6 lebt"
    update_splash()
	Sleep(600)
	WEnd
 EndIf

 maus7()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 7"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 7 lebt"
    update_splash()
	Sleep(600)
	WEnd
 EndIf

BU()

 maus8()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 8"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 8 lebt"
    update_splash()
	Sleep(600)
	WEnd
	EndIf

	maus9()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 9"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 9 lebt"
    update_splash()
	Sleep(600)
	WEnd
    EndIf

BU()

    maus10()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 10"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 10 lebt"
    update_splash()
	Sleep(600)
	WEnd
    EndIf


	maus11()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 11"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 11 lebt"
    update_splash()
	Sleep(600)
	WEnd
EndIf

BU()

maus12()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 12"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 12 lebt"
    update_splash()
	Sleep(600)
	WEnd
    EndIf

maus13()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 13"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 13 lebt"
    update_splash()
	Sleep(600)
	WEnd
    EndIf

BU()

maus14()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 14"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 14 lebt"
    update_splash()
	Sleep(600)
	WEnd
    EndIf

maus15()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 15"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 15 lebt"
    update_splash()
	Sleep(600)
	WEnd
    EndIf

BU()

maus16()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 16"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 16 lebt"
    update_splash()
	Sleep(600)
	WEnd
    EndIf

maus17()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 17"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 17 lebt"
    update_splash()
	Sleep(600)
	WEnd
    EndIf

BU()

maus18()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 18"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 18 lebt"
    update_splash()
	Sleep(600)
	WEnd
    EndIf

maus19()
   Sleep(30000)
	FindMob()
	If $mob_found = 1 Then
	$message = "mob da 19"
    update_splash()
	Sleep(500)
	MobLiving()
 While $mob_alive = 1
	MobLiving()
   	$message = "mob 19 lebt"
    update_splash()
	Sleep(600)
	WEnd
    EndIf

WEnd

Func RightClick()
MouseDown("right")
Sleep(100)
MouseUp("right")
EndFunc

Func LeftClick()
MouseDown("left")
Sleep(100)
MouseUp("left")
EndFunc


 Func BU()
   Sleep(300)
   MouseMove(901,938)
   Sleep(300)
   RightClick()
   Sleep(300)
   MouseMove(861,938)
   Sleep(300)
   RightClick()
   Sleep(300)
   EndFunc

Func maus()
 Sleep(15000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("60")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("165")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

autokampf()

Func maus2()
 Sleep(15000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("28")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("162")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus3()
 Sleep(15000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("31")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("202")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus4()
 Sleep(15000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("54")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("200")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus5()
 Sleep(15000)
 MouseMove(896,937)
 Sleep(100)
 RightClick()
 Sleep(100)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("66")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("220")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus6()
 Sleep(15000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("29")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("218")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus7()
 Sleep(15000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("32")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("277")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus8()
 Sleep(15000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("59")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("274")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus9()
 Sleep(15000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("105")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("275")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus10()
 Sleep(15000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("211")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("266")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus11()
 Sleep(5000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("277")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("274")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus12()
 Sleep(5000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("238")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("258")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus13()
 Sleep(5000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("248")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("229")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus14()
 Sleep(5000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("279")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("223")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus15()
 Sleep(5000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("269")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("191")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus16()
 Sleep(5000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("279")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("155")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus17()
 Sleep(5000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("243")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("194")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus18()
 Sleep(5000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("135")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("175")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func maus19()
 Sleep(15000)
Send ("m")
Sleep(100)
MouseMove(1104,298)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("114")
Sleep(100)
MouseMove(1154,297)
Sleep(100)
LeftClick()
Sleep(100)
Opt ("SendKeyDowndelay" , 300)
Send("180")
Sleep(100)
MouseMove(1102,327)
Sleep(100)
LeftClick()
Sleep(100)
MouseMove(1193,277)
Sleep(100)
LeftClick()
Sleep(100)
EndFunc

Func TogglePause()
    $Paused = NOT $Paused
    While $Paused
        sleep(100)
        ToolTip('Script is "Paused"',0,0)
    WEnd
    ToolTip("")
EndFunc

Func FindMob()
	;Send ("{TAB}")
    ;Sleep(100)
	$check_pix = PixelGetColor( 818 , 63 )
	$mob_found = 0
	;MouseMove(818,63)
	;Sleep(2000)
	;MsgBox(0,"The color is", ($check_pix))
	If ($check_pix) == 4867369 Then
	$mob_found = 1
	;Opt ("SendKeyDowndelay" , 200)
	;Send ("1")
	Sleep(200)
	EndIf
EndFunc

Func MobLiving()
	$check_pix = PixelGetColor( 818 , 63 )
	$mob_alive = 0
	;MouseMove(505,62)
	;Sleep(2000)
    ;MsgBox(0,"The color is", ($check_pix))
	If ($check_pix) == 4867369 Then
	$mob_alive = 1
	Sleep(500)
	EndIf
EndFunc

func Term ()
   exit
endfunc

func update_splash ()
   SplashTextOn( "", $message , $width , $height ,310 ,0 , 17)
endfunc

