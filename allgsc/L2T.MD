//***************//
//Dog discription//
//***************//
NAME Pikiner_turki
MESSAGE �ᬠ�᪨�_�������
ICON TR_PIK
//USERLC 0 l2ps  SHADOW -63 -89
USERLC 1 l2pg  SHADOW -63 -89
USERLC 2 l2pb   SHADOW -63 -89
USERLC 3 l2pu   SHADOW -63 -89
USERLC 4 l2ph  shadow -63 -89
USERLC 5 l2pP SHADOW -63 -89
//Animation discription:
// #ANIMATION Rotations NFrames FileID_1 frame1 ... FileID_N frameN
#STAND     9 1   5 0
#PSTAND 9 1 5 9   
@MOTION_L  9 1 0 9 
@MOTION_R  9 1 10 19 
@MOTION_LB 9 1 19 10 
@MOTION_RB 9 1 9 0 
@MOTION_L0  9 2 0 9 
@MOTION_R0  9 2 10 19 
@MOTION_LB0 9 2 19 10 
@MOTION_RB0 9 2 9 0 
@ATTACK    9 3 0 13
@PATTACK  9 5 0 9
@UATTACK 9 5 9 0
@DEATH 9 4 0 21
#DEATHLIE1 9 1 4 21
//Activepoints for shot
//GEOMETRY Radius1 Radius2 StepSize
GEOMETRY 1 10 32
DAMAGE   0 9
LIFE     100
RECTANGLE 0 2 32 40
ATTACK_RADIUS 0 35 110
SEARCH_ENEMY_RADIUS 700
DET_RADIUS 0 0 10000
//Matheruals:
//BODY,STONE,WOOD,IRON,AIR
MATHERIAL 1 BODY
CANKILL   2 BODY STENA
PRICE 2 FOOD 55 IRON 2
BUILDSTAGES 150
WEAPONKIND 0 PIKA
VISION 1
SOUND 3 #DEATH DEASE
USAGE LIGHTINFANTRY
STANDGROUND
INFO 0 45
FORCE 10
[END]
