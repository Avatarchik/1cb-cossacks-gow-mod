NAME Gusar_NEW
MESSAGE ����
ICON Add11
USERLC 0 gsns  SHADOW -65 -90
USERLC 2 gsnn   SHADOW -65 -90
USERLC 4 gsnu   SHADOW -65 -90
USERLC 5 gsnh  shadow -95 -121
@REST 9 0 0 15    
#STAND 9 1 0 0

@MOTION_L   9 2 0 5 
@MOTION_LB  9 2 5 0                     

@MOTION_L0  9 2 0 5 
@MOTION_LB0 9 2 5 0                     
@MOTION_L1  9 2 5 10
@MOTION_LB1 9 2 10 5

@MOTION_R0  9 2 10 15 
@MOTION_RB0 9 2 15 10                     
#MOTION_R1  9 5 2 15 2 16 2 17 2 18 2 19 2 0
#MOTION_RB1 9 5 2 0  2 19 2 18 2 17 2 16 2 15
@ATTACK 9 4 0 15   
@DEATH 9 5 0 23
#DEATHLIE1 9 1 5 23
GEOMETRY 1 15 96
DAMAGE   0 8
LIFE     250
RECTANGLE 0 2 32 40
ATTACK_RADIUS 0 25 70
DET_RADIUS 0 0 200
SEARCH_ENEMY_RADIUS 700
DET_RADIUS 0 0 10000
MATHERIAL 1 BODY
CANKILL   2 BODY STENA
PRICE 3 FOOD 110 IRON 3 GOLD 5
BUILDSTAGES 325
WEAPONKIND 0 PIKA
VISION 8
SOUND 2 #ATTACK SABRE1
SOUND 2 #DEATH MANHOR
SOUND 1 #MOTION_L0 RIS
SOUND 4 #MOTION_L1 RIS
FASTUNIT 1
USAGE FASTHORSE
STANDGROUND
VES 35
INFO 0 67
FORCE 15
[END]
