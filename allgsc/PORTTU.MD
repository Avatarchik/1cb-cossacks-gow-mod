NAME  Port
MESSAGE ����
ICON Tu_Prt
BUILDING
USERLC 0 port  SHADOW 0 0
LOCKPOINTS 96    2 15  3 14  3 15  3 16  4 13  4 14  4 15  4 16  4 17  5 12  5 13  5 14  5 15  5 16  5 17  5 18  6 11  6 12  6 13  6 14  6 15  6 16  6 17  6 18  6 19  7 10  7 11  7 12  7 13  7 14  7 15  7 16  7 17  7 18  7 19  7 20  8 9  8 10  8 11  8 12  8 13  8 14  8 15  8 16  8 17  8 18  8 19  8 20  9 8  9 9  9 10  9 11  9 12  9 13  9 14  9 15  9 16  9 17  9 18  9 19  10 8  10 9  10 10  10 11  10 12  10 13  10 14  10 15  10 16  10 17  10 18  11 9  11 10  11 11  11 12  11 13  11 14  11 15  11 16  11 17  12 10  12 11  12 12  12 13  12 14  12 15  12 16  13 11  13 12  13 13  13 14  13 15  14 12  14 13  14 14  15 13
BUILDPOINTS 10    1 12  1 13  1 17  3 20  4 9  7 5  7 6  10 5  13 5  14 18
CHECKPOINTS 96    2 15  3 14  3 15  3 16  4 13  4 14  4 15  4 16  4 17  5 12  5 13  5 14  5 15  5 16  5 17  5 18  6 11  6 12  6 13  6 14  6 15  6 16  6 17  6 18  6 19  7 10  7 11  7 12  7 13  7 14  7 15  7 16  7 17  7 18  7 19  7 20  8 9  8 10  8 11  8 12  8 13  8 14  8 15  8 16  8 17  8 18  8 19  8 20  9 8  9 9  9 10  9 11  9 12  9 13  9 14  9 15  9 16  9 17  9 18  9 19  10 8  10 9  10 10  10 11  10 12  10 13  10 14  10 15  10 16  10 17  10 18  11 9  11 10  11 11  11 12  11 13  11 14  11 15  11 16  11 17  12 10  12 11  12 12  12 13  12 14  12 15  12 16  13 11  13 12  13 13  13 14  13 15  14 12  14 13  14 14  15 13
DAMPOINTS  4    3 10  8 3  9 11  13 9
//offset of piture(x,y) sprites/pipture sprite width
SETANMPARAM -144 -114 1 0
//Animation discription:
// #ANIMATION Rotations NFrames FileID_1 frame1 ... FileID_N frameN
#STANDLO    1 2   0 8 0 9 
#BUILDLO_0  1 2   0 0  0 1  
#BUILDLO_1  1 2   0 2  0 3
#BUILDLO_2  1 2   0 4  0 5
#BUILDLO_3  1 2   0 6  0 7  
LINESORT #STANDLO     GROUND LINE 31 123 254 108  
LINESORT #BUILDLO_0   GROUND LINE 31 123 254 108   
LINESORT #BUILDLO_1   GROUND LINE 31 123 254 108     
LINESORT #BUILDLO_2   GROUND LINE 31 123 254 108     
LINESORT #BUILDLO_3   GROUND LINE 31 123 254 108    
//Activepoints for shot
//GEOMETRY Radius1 Radius2 StepSize
GEOMETRY 1 199 32
LOCATION -144 -114 254 167 
LIFE     65000
COST     500 0 0
SHIELD   5
//RANGE AttackRange MaxAttackRange MinAttRange MaxNearRange ActionType VisibilityRadius
RANGE    18 6 22 0 0 9
MAGIC    256
TIME     50
KIND	 1
BUILDSTAGES 500
//Building(Unit) for the concentration of the resources
//RESOURCEBASE 4 WOOD GOLD STONE FOOD
RECTANGLE    0 80 160 160
//ICON  ����������_�����
//burning settings:
//<COMMAND> Max_Born_Probability Amount_of_weapons List_of_weapon
//FOGGING		 100 2 WFOG1UP WFOG2UP
//DESTRUCT     400 2 DARKFOG DARKFOG1
//FIRE         30  2 WFOG1UP WFOG2UP
//DESTRUCT     400 1 DSP2
[END]
