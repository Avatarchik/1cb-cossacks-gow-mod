//***************//
//Dog discription//
//***************//
NAME Pushka
MESSAGE ��誠
ICON PUSH
USERLC 2 pusg  SHADOW -74 -101
USERLC 4 push  shadow -74 -101
USERLC 1 pusall  shadow -74 -101
MOTIONSTYLE SLOWROTATE
//Animation discription:
// #ANIMATION Rotations NFrames FileID_1 frame1 ... FileID_N frameN
#STAND     129 1 1 0   
@MOTION_L  9 2 0 13 
@MOTION_R  9 2 0 13
@MOTION_LB 9 2 13 0
@MOTION_RB 9 2 13 0 
#DEATH     9 18  4 0 4 0 4 0 4 1 4 1 4 1 4 2 4 2 4 2 4 3 4 3 4 3 4 4 4 4 4 5 4 5 4 5 4 6 4 6 4 6
#DEATHLIE1 9 1 4 6
#ATTACK   129 5 1 0 1 0 1 0 1 0 1 0
#ATTACK1  129 5 1 0 1 0 1 0 1 0 1 0
//Activepoints for shot
SETACTIVEPOINT #ATTACK 4 73 93 73 94 72 93 71 93 70 93 70 93 69 93 68 93 68 93 67 93 66 93 66 93 65 93 65 92 64 92 64 93 63 92 63 92 62 92 62 92 61 92 61 92 60 92 60 92 59 92 59 92 58 91 58 91 57 91 57 91 56 91 56 91 55 90 55 90 54 90 54 90 54 89 54 89 53 88 53 88 53 88 52 88 51 88 51 88 51 88 50 87 50 87 50 86 50 86 50 85 50 85 50 84 50 84 50 84 50 84 50 84 50 84 49 83 49 83 49 82 49 82 49 82 49 81 49 81 49 81 49 80 49 80 49 80 49 80 49 79 49 79 49 79 49 79 49 78 49 78 50 77 50 77 50 77 51 76 51 76 51 76 51 76 51 76 52 75 52 75 52 74 52 73 53 73 53 73 54 73 54 73 55 72 55 72 55 72 55 72 56 72 56 72 56 71 57 71 57 71 59 70 59 70 59 70 59 69 60 69 61 69 61 69 62 69 62 69 63 69 63 69 64 69 64 69 65 69 66 68 66 68 67 68 67 68 68 68 69 68 69 68 70 68 71 68 72 68 72 68 73 68 73 68 73 68 73 68 
SETACTIVEPOINT #ATTACK1 4 73 93 73 94 72 93 71 93 70 93 70 93 69 93 68 93 68 93 67 93 66 93 66 93 65 93 65 92 64 92 64 93 63 92 63 92 62 92 62 92 61 92 61 92 60 92 60 92 59 92 59 92 58 91 58 91 57 91 57 91 56 91 56 91 55 90 55 90 54 90 54 90 54 89 54 89 53 88 53 88 53 88 52 88 51 88 51 88 51 88 50 87 50 87 50 86 50 86 50 85 50 85 50 84 50 84 50 84 50 84 50 84 50 84 49 83 49 83 49 82 49 82 49 82 49 81 49 81 49 81 49 80 49 80 49 80 49 80 49 79 49 79 49 79 49 79 49 78 49 78 50 77 50 77 50 77 51 76 51 76 51 76 51 76 51 76 52 75 52 75 52 74 52 73 53 73 53 73 54 73 54 73 55 72 55 72 55 72 55 72 56 72 56 72 56 71 57 71 57 71 59 70 59 70 59 70 59 69 60 69 61 69 61 69 62 69 62 69 63 69 63 69 64 69 64 69 65 69 66 68 66 68 67 68 67 68 68 68 69 68 69 68 70 68 71 68 72 68 72 68 73 68 73 68 73 68 73 68 
//GEOMETRY Radius1 Radius2 StepSize
GEOMETRY 1 15 20
DAMAGE   0 1800
LIFE     25000
//RANGE AttackRange MaxAttackRange MinAttRange MaxNearRange ActionType VisibilityRadius
RANGE    2 1 4 0 0 9
PRICE 5  WOOD 200 STONE 450 IRON 300 GOLD 450 COAL 255
SHIELD 90
//Matheruals:
//BODY,STONE,WOOD,IRON,AIR
MATHERIAL 1 IRON
RECTANGLE 0 2 32 40
WEAPON 0 PPOINTT
WEAPON 1 PSMPOINTTPUS
ATTACK_ANGLES		0 -255 255
ATTACK_RADIUS		0 550 2000
DET_RADIUS       0 550 10000
ATTACK_RADIUS		1 0 550
DET_RADIUS       1 0 550
ADD_ATTACK_RADIUS	0 32
ATTACK_PAUSE		0 350
ATTACK_PAUSE		1 1400
SEARCH_ENEMY_RADIUS 550
CANKILL   6 BODY WOOD STONE IRON  BUILDING STENA
EXPLMEDIA WOOD 25
ZPOINTS   30 30
WEAPONKIND 0 IADRO
WEAPONKIND 1 IADROMOR
BUILDSTAGES 8000
SHOWDELAY
RASTRATA_NA_VISTREL2 0 1 2 IRON 24 COAL 21
CAPTURE
NO_HUNGRY
VISION 8
RESCONSUMER GOLD 500
TURNOFF
//COSTPERCENT 105
RAZBROS 250
//SOUND 2 #ATTACK PUSVIS1
//SOUND 2 #ATTACK1 PUSKAR1
SOUND 2 #DEATH PUSDEZ1
ROTATE 1
USAGE PUSHKA
STANDGROUND
VES 50
INFO 1 1
FORCE 1
ARTPODGOTOVKA
MAXINDEPO 0 5
[END]
