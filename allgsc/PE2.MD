NAME Pik_evro_rus
MESSAGE �������_18�
ICON PE2
USERLC 1 Pe2g  SHADOW -63 -91
USERLC 2 pe2b   SHADOW -63 -91
USERLC 3 Pe2u   SHADOW -63 -91
USERLC 4 Pe2h  shadow -63 -91
USERLC 5 Pe2P SHADOW -63 -91
//Animation discription:
// #ANIMATION Rotations NFrames FileID_1 frame1 ... FileID_N frameN
#STAND      9 1   5 0
#PSTAND     9 1   5 9
@MOTION_L   9 1 0 9  
@MOTION_R   9 1 10 19 
@MOTION_RB  9 1 19 10
@MOTION_LB  9 1 9 0
@MOTION_L0  9 2 0 9 
@MOTION_R0  9 2 10 19 
@MOTION_LB0 9 2 19 10 
@MOTION_RB0 9 2 9 0 
@ATTACK     9 3 0 9 
@PATTACK    9 5 0 9
@UATTACK    9 5 9 0
@DEATH      9 4 0 23
#DEATHLIE1  9 1 4 23
//Activepoints for shot
//GEOMETRY Radius1 Radius2 StepSize
GEOMETRY 1 10 32
DAMAGE   0 10
LIFE     85
RECTANGLE 0 2 32 40
ATTACK_RADIUS 0 45 100
ATTACK_PAUSE 0 1
SEARCH_ENEMY_RADIUS 700
DET_RADIUS 0 0 10000
//Matheruals:
//BODY,STONE,WOOD,IRON,AIR
MATHERIAL 1 BODY
CANKILL   2 BODY STENA
PRICE 2 FOOD 15 GOLD 1
WEAPONKIND 0 PIKA 
BUILDSTAGES 25
VISION 1
SOUND 3 #DEATH DEASE
USAGE LIGHTINFANTRY
STANDGROUND
INFO 0 20
FORCE 10
[END]
