# GrassiOsc Bill of Materials (BOM)

To build just follow the order in the BOM.

When soldering the ICs (U2->U8), solder in the equivalent sockets instead.

Solder the panel components (jacks and pots) last, on the opposite side of the board to the other parts.

| Reference				| Quantity	| Part	| Notes |
| --------------------------------------- | -------------- | ------- | -------- |
| R15,R23,R34,R41,R51,R54			|6	| 100R	| |
| R9,R28,R45				|3	| 1k	| LED protection resistors |
| R20,R21,R37,R40,R52,R53			|6	| 10k	| |
| R3,R7,R22,R24,R26,R42,R55		|7	| 100k	| |
| R12,R13,R31,R32,R48,R49			|3	| 1M	| |
| R25,R43,R58				|3	| 2.2k	| |
| R6					|1	| 22k	| |
| R14,R33,R50				|3	| 220k	| |
| R10,R11,R29,R30,R46,R47			|6	| 2.2M	| |
| R1,R2,R4,R5				|4	| 47k	| |
| R16,R17,R18,R19,R35,R36,R38,R39,R56,R57,R59,R60	| 12	| Choose your own (see build note)	| DAC resistors |
| R8,R27,R44				|3	| Choose your own (see build note)	| DAC amplifier resistors |
| D1					|1	| 1N4001	| Reverse polarity protection diode |
| D3,D6,D9				|3	| 3mm LED	| Standard brightness |
| D2,D5,D8				|3 	| 1N4148	 | |
| D4,D7,D10,D11,D12,D13			|6	| BAT85	| Negative voltage protection diodes |
| Q1,Q3,Q5				|3	| BC547 TO92	 | |
| Q2,Q4,Q6				|3	| BC557 TO92	 | |
| C3,C4					|2	| 10uF electrolytic	| Power conditioning caps |
| C8,C11,C15				|3	| 100nF mylar	| Oscillator AC coupling cap.  Can substitute MLCC |
| C10,C13,C17				|3	| 470nF electrolytic	| Oscillator timing cap: control rate |
| C5,C6					|2	| 1uF electrolytic	| MIDO voltage conditioning cap.  Can substitute MLCC |
| C1,C2,C7,C14				|4	| 100nF ceramic disc	| IC decoupling capacitors |
| C9,C12,C16				|3	| 22nF mylar	| Oscillator timing cap: audio rate |
| U1					|1	| L78L09 TO92	| Power regulator |
| U2					|1	| CD40106	| |
| U3					|1	| CD4066	 | |
| U4,U5					|2	| TL074	| Or TL084 | |
| U6					|1	| LM324	| DO NOT use TL074 or TL084 | |
| U7,U8					|2	| CD4015	| |
| SW1,SW2,SW3				|3	| SPDT miniature switch 2.54mm pitch |
| RV1,RV2,RV3,RV4,RV5,RV6			|6	| 10k 9mm potentiometer |
| J1					|1	| Eurorack 2x5 shrouded male |
| J2,J3,J4,J5,J6,J7,J8,J9,J10,J11,J12,J13	|12	| Thonkiconn 3.5mm mono socket |
| IC socket 14 pin	DIP-14_W7.62mm_Socket	|5	| DIP 14 pin socket |
| IC socket 16 pin	DIP-16_W7.62mm_Socket	|2	| DIP 16 pin socket |