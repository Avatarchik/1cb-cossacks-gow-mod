NAME  Dom_Ispain
MESSAGE �����_���
ICON AU_Dom
BUILDING
FARM
USERLC 0 doi  SHADOW 0 0
USERLC 1 doidez SHADOW 0 0
LOCKPOINTS 106    16 39  16 40  16 41  17 38  17 39  17 40  17 41  17 42  18 37  18 38  18 39  18 40  18 41  18 42  18 43  19 36  19 37  19 38  19 39  19 40  19 41  19 42  19 43  20 36  20 37  20 38  20 39  20 40  20 41  20 42  20 43  21 36  21 37  21 38  21 39  21 40  21 41  21 42  21 43  21 44  22 36  22 37  22 38  22 39  22 40  22 41  22 42  22 43  22 44  22 45  23 36  23 37  23 38  23 39  23 40  23 41  23 42  23 43  23 44  23 45  23 46  24 36  24 37  24 38  24 39  24 40  24 41  24 42  24 43  24 44  24 45  24 46  25 37  25 38  25 39  25 40  25 41  25 42  25 43  25 44  25 45  25 46  26 38  26 39  26 40  26 41  26 42  26 43  26 44  26 45  26 46  27 39  27 40  27 41  27 42  27 43  27 44  27 45  28 40  28 41  28 42  28 43  28 44  29 41  29 42  29 43
BUILDPOINTS 21    14 39  14 41  15 37  15 43  17 35  17 45  19 34  19 46  21 34  21 47  23 34  23 48  25 34  25 48  27 36  27 48  29 38  29 46  31 40  31 42  31 44
CHECKPOINTS 106    16 39  16 40  16 41  17 38  17 39  17 40  17 41  17 42  18 37  18 38  18 39  18 40  18 41  18 42  18 43  19 36  19 37  19 38  19 39  19 40  19 41  19 42  19 43  20 36  20 37  20 38  20 39  20 40  20 41  20 42  20 43  21 36  21 37  21 38  21 39  21 40  21 41  21 42  21 43  21 44  22 36  22 37  22 38  22 39  22 40  22 41  22 42  22 43  22 44  22 45  23 36  23 37  23 38  23 39  23 40  23 41  23 42  23 43  23 44  23 45  23 46  24 36  24 37  24 38  24 39  24 40  24 41  24 42  24 43  24 44  24 45  24 46  25 37  25 38  25 39  25 40  25 41  25 42  25 43  25 44  25 45  25 46  26 38  26 39  26 40  26 41  26 42  26 43  26 44  26 45  26 46  27 39  27 40  27 41  27 42  27 43  27 44  27 45  28 40  28 41  28 42  28 43  28 44  29 41  29 42  29 43
DAMPOINTS  1    22 35
FIRES 15 374 293  380 295  385 298  391 301  396 305  401 305  409 304  421 288  426 286  357 276  349 275  342 275  319 277  314 277  308 277  
SMOKE 13   380 295    391 301  396 305  401 305  409 304  421 288  426 286  357 276  349 275  342 275  319 277  314 277  308 277  
//offset of piture(x,y) sprites/pipture sprite width
SETANMPARAM -369 -357 1 0
LOCATION -369 -357 500 405 
//Animation discription:
// #ANIMATION Rotations NFrames FileID_1 frame1 ... FileID_N frameN
#STANDLO    1 2   0 8 0 9 
#BUILDLO_0  1 2   0 0  0 1  
#BUILDLO_1  1 2   0 2  0 3
#BUILDLO_2  1 2   0 4  0 5
#BUILDLO_3  1 2   0 6  0 7  
#DEATHLIE1  1 2   1 0  1 1
#DEATHLIE2  1 2   1 2  1 3
LINESORT #STANDLO     GROUND LINE 275 345 458 348
LINESORT #BUILDLO_0   GROUND LINE 275 345 458 348
LINESORT #BUILDLO_1   GROUND LINE 275 345 458 348
LINESORT #BUILDLO_2   GROUND LINE 275 345 458 348
LINESORT #BUILDLO_3   GROUND LINE 275 345 458 348
LINESORT #DEATHLIE1   GROUND LINE 288 366 461 361
LINESORT #DEATHLIE2   GROUND LINE 288 366 461 361
DESTRUCT 16000 13 obl16 obl23 obl38 obl16 obl23 obl38 obl16 obl23 obl38 PU4 PU2 PU6 PU6
//Activepoints for shot
//GEOMETRY Radius1 Radius2 StepSize
GEOMETRY 1 199 32
LIFE     4200
PRICE 2 WOOD 50 STONE 50
//RANGE AttackRange MaxAttackRange MinAttRange MaxNearRange ActionType VisibilityRadius
RANGE    18 6 22 0 0 9
MATHERIAL 1 BUILDING
RECTANGLE    0 80 160 160
EXPLMEDIA BUILDING 5
BUILDBAR   10 40  35 42
BUILDSTAGES 100
3DBARS 1 287 331 101 69 60  
COSTPERCENT 103
CAPTURE
USAGE FARM
SLOWDEATH
INFO 3 1
VES 100
[END]
