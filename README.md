# Excel-Hacks

1. Transpose every 5 or n rows from one column to multiple columns with formula: 
>=INDEX($A:$A,ROW(A1)*5-5+COLUMN(A1))

![image](https://user-images.githubusercontent.com/51813161/227701024-ba8b269a-c3d5-4b3c-be2b-94bbab9898b2.png)

2.Extracting Data with the LEFT, RIGHT, FIND and LEN Functions
>=LEFT(A1, FIND(",",A1)-1)

![image](https://user-images.githubusercontent.com/51813161/227701388-68f338d5-23d2-4fca-8dc9-fcda01ac0fed.png)

>=RIGHT(A1,LEN(A1)-FIND(",",A1))

![image](https://user-images.githubusercontent.com/51813161/227701450-6071d8c7-c94f-4dfd-979a-ac8f07c7f4bf.png)


