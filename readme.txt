0: LOAD A 
1: LOAD B
2: LOAD C
3: STORE C
4: SET A
5: SET B
6: SET C
7: CALC C:
	0: A+B
	1: A-B
	2: !A
	3: !B
	4: A<<B
	5: A>>B
	6: A<<<B
	7: A>>>B
	8: A and B
	9: A or B
	A: A xor B
	B: A nand B
	C: A nor B
	D: A nxor B
	E: A
	F: B
8: POINTER:
	0: C-8
	*: X-8
9: POINTER MARK
A: POINTER GOTO
B: IF:
	0: A==B JUMP
	1: A!=B JUMP
	2: A<B JUMP
	3: A>B JUMP
	4: A<=B JUMP
	5: A>=B JUMP
	6: A==0 JUMP
	7: B==0 JUMP
	8: C==0 JUMP
	9: A!=0 JUMP
	A: B!=0 JUMP
	B: C!=0 JUMP
C: INPUT
	0: KEYPRESS > A (0: Nothing, 1: Right, 2: Down, 3: Left, 4: Up; 5: Space; 6: Enter)
	1: RANDOM (0 or 1) > A
	2: RANDOM (0-15) > A
D: DRAW (AT X:A Y:B):
	0: SET BLACK
	1: SET WHITE
	2: SET GREY
	3: CLEAR BLACK
	4: CLEAR WHITE
	5: CLEAR GREY
	6: AT X,Y > A (BLACK=0, GREY=8, WHITE=F)