# blitz_ptplayer
Port of Frank Wille's Protracker player as a Blitz Basic library

Blitz Basic function/statement entry points added by idrougge

VBR fix by phx

compiled with vasm 1.8l, with the following options:
vasmm68k_mot.exe -devpac -Fhunkexe -kick1hunks -nosym  ptplayer.asm -o ptplayer.obj

Built with the following configuration flags:

MINIMAL		equ	0

ENABLE_SAWRECT	equ	0

NULL_IS_CLEARED	equ	0
