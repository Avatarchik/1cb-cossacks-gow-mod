NAME  MOST
MESSAGE ����
//ICON 
BUILDING
FARM
USERLC 0 MST_K1  SHADOW 0 0
USERLC 1 MostOtr SHADOW 0 0
//offset of piture(x,y) sprites/pipture sprite width
SETANMPARAM -337 -293 1 0
LOCKPOINTS 6    18 46  19 45  19 46  19 47  20 46  20 47
CHECKPOINTS 79    3 13  3 14  3 15  4 12  4 13  4 14  4 15  4 16  5 11  5 12  5 13  5 14  5 15  5 16  5 17  6 10  6 11  6 12  6 13  6 14  6 15  6 16  6 17  6 18  7 9  7 10  7 11  7 12  7 13  7 14  7 15  7 16  7 17  7 18  7 19  8 8  8 9  8 10  8 11  8 12  8 13  8 14  8 15  8 16  8 17  8 18  8 19  9 8  9 9  9 10  9 11  9 12  9 13  9 14  9 15  9 16  9 17  9 18  10 9  10 10  10 11  10 12  10 13  10 14  10 15  10 16  10 17  11 10  11 11  11 12  11 13  11 14  11 15  11 16  12 11  12 12  12 13  12 14  12 15
//Animation discription:
// #ANIMATION Rotations NFrames FileID_1 frame1 ... FileID_N frameN
#STANDLO    1 2   0 0 0 1 
#PATTACK3   1 1 1 0
#DEATHLIE1    1 2   0 0 0 1 
REFLECT #PATTACK3
LINESORT #STANDLO LINE 219 170 617 367 LINE 108 217 506 412
//Activepoints for shot
//GEOMETRY Radius1 Radius2 StepSize
GEOMETRY 1 199 32
LOCATION -337 -292 674 467 
LIFE     65000
SHIELD 400
//RANGE AttackRange MaxAttackRange MinAttRange MaxNearRange ActionType VisibilityRadius
RANGE    18 6 22 0 0 9
BUILDSTAGES 100
RECTANGLE    0 0 0 0
[END]
