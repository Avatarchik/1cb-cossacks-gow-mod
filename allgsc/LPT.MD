//***************//
//Dog discription//
//***************//
NAME Pehota_turki
MESSAGE ������_���⨭��
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
DAMAGE   0 6
LIFE     55
RECTANGLE 0 2 32 40
ATTACK_RADIUS 0 15 40
SEARCH_ENEMY_RADIUS 700
DET_RADIUS 0 0 10000
//Matheruals:
//BODY,STONE,WOOD,IRON,AIR
MATHERIAL 1 BODY
CANKILL   2 BODY STENA
PRICE 2 FOOD 35 IRON 1 
BUILDSTAGES 50
WEAPONKIND 0 MECH
VISION 8
SOUND 3 #DEATH DEASE
USAGE LIGHTINFANTRY
STANDGROUND
VES 3
INFO 0 48
FORCE 3
[END]
