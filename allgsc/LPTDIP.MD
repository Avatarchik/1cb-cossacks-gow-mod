//***************//
//Dog discription//
//***************//
NAME Pehota_turki_DIP
MESSAGE ������_���⨭��_(�������)
ICON Lpt
USERLC 2 lptg  SHADOW -62 -90
USERLC 3 lptu   SHADOW -62 -90
USERLC 4 lpth  shadow -62 -90
//Animation discription:
// #ANIMATION Rotations NFrames FileID_1 frame1 ... FileID_N frameN
#STAND      9 1 3 0
@MOTION_L   9 2 0 9 
@MOTION_R   9 2 10 19 
@MOTION_LB  9 2 19 10 
@MOTION_RB  9 2 9 0 
@ATTACK     9 3 0 14
@DEATH      9 4 0 19
#DEATHLIE1  9 1 4 19
//Activepoints for shot
//GEOMETRY Radius1 Radius2 StepSize
GEOMETRY 1 10 32
DAMAGE   0 14
LIFE     75
RECTANGLE 0 2 32 40
ATTACK_RADIUS 0 15 40
DET_RADIUS 0 0 5000
SEARCH_ENEMY_RADIUS 700
//Matheruals:
//BODY,STONE,WOOD,IRON,AIR
MATHERIAL 1 BODY
CANKILL   2 BODY STENA
PRICE 1 GOLD 5
WEAPONKIND 0 MECH
BUILDSTAGES 50
NO_HUNGRY
RESCONSUMER GOLD 3
NAEMNIK
//USAGE VEAC
STANDGROUND
VES 1
INFO 0 48
[END]
