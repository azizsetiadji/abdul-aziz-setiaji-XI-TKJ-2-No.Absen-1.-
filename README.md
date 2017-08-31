# abdul-aziz-setiaji-XI-TKJ-2-No.Absen-1.-
Tugas Pertama membuat program z80


AWAL	LD A,0

	OUT (00H),A
	
	ADD A,1

TAMPIL	OUT (01H),A

	BIT 7,A
	
	JP NZ,AWAL
	
	SLA A
	
	JP TAMPIL
