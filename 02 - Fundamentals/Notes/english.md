Interpreted language
- Text based code that gets "interpreted" by an interpreter program.

Compiled language
- Text based code that gets "compiled" into Assembly 0s and 1s instructions for a CPU.

Program
- A file of 0s and 1s Assembly instructions for a CPU.

ASCII
- A mapping of numbers to latin characters and common symbols

Unicode
- A set of mappings extending the original ASCII mappings, that can represent any letter symbol or character, for any language. It also has the emoji mappings.

Bit
- A positive electric charge (can also be an on switch), or negative electric charge, representing a 0 or 1 (singular)

Byte
- 8 bits

Binary
- 0s and 1s (plural)

Hexadecimal
- Number system with 16 symbols `0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F`.

RGB
- Three numbers, each number representing a certain amount of Red Green or Blue.


# Trivia 
UTF-8
- Unicode Transform Format 8. Uses 8 bits to represent the most common latin characters.

UTF-16
- Unicode Transform Format 16. Uses 16 bits. Represents 2x more symbols and characters as UTF-8.

UTF-32
- Unicode Transform Format 32. Uses 32 bits.

RGB
- bitmaps as they are used in computer graphics. A bitmap is a picture that uses an RGB value for every pixel. Best explanation of RGB.
http://paulbourke.net/dataformats/bitmaps/

- https://stackoverflow.com/questions/33962331/sdl2-difference-between-rgb888-and-rgb24

- RGB-32 is faster than RGB-24 https://www.animemusicvideos.org/forum/viewtopic.php?t=45357

Memory sizes
http://www.athropolis.com/popup/c-comp2.htm#explanation

ASCII
- https://theasciicode.com.ar/ascii-codes.txt
```
ASCII ENCODING

    num  letter/symbol
	0	 NULL	(Null character)			
	1    SOH	(Start of Header)			
	2	 STX	(Start of Text)			
	3	 ETX	(End of Text)			
	4	 EOT	(End of Transmission)			
	5	 ENQ	(Enquiry)			
	6	 ACK	(Acknowledgement)			
	7	 BEL	(Bell)			
	8	 BS	    (Backspace)			
	9	 HT	    (Horizontal Tab)			
	10	 LF	    (Line feed)			
	11	 VT	    (Vertical Tab)			
	12	 FF	    (Form feed)			
	13	 CR	    (Carriage return)			
	14	 SO	    (Shift Out)			
	15	 SI	    (Shift In)			
	16	 DLE	(Data link escape)			
	17	 DC1	(Device control 1)			
	18	 DC2	(Device control 2)			
	19	 DC3	(Device control 3)			
	20	 DC4	(Device control 4)			
	21	 NAK	(Negative acknowledgement)			
	22	 SYN	(Synchronous idle)			
	23	 ETB	(End of transmission block)			
	24	 CAN	(Cancel)			
	25	 EM	    (End of medium)			
	26	 SUB	(Substitute)			
	27	 ESC	(Escape)			
	28	 FS	    (File separator)			
	29	 GS	    (Group separator)			
	30	 RS	    (Record separator)			
	31	 US	    (Unit separator)			
						
	32	 	(space)			
	33	!	(exclamation mark)			
	34	"	(Quotation mark)			
	35	#	(Number sign)			
	36	$	(Dollar sign)			
	37	%	(Percent sign)			
	38	&	(Ampersand)			
	39	'	(Apostrophe)			
	40	(	(round brackets or parentheses)			
	41	)	(round brackets or parentheses)			
	42	*	(Asterisk)			
	43	+	(Plus sign)			
	44	,	(Comma)			
	45	-	(Hyphen)			
	46	.	(Full stop , dot)			
	47	/	(Slash)			
	48	0	(number zero)			
	49	1	(number one)			
	50	2	(number two)			
	51	3	(number three)			
	52	4	(number four)			
	53	5	(number five)			
	54	6	(number six)			
	55	7	(number seven)			
	56	8	(number eight)			
	57	9	(number nine)			
	58	:	(Colon)			
	59	;	(Semicolon)			
	60	<	(Less-than sign )			
	61	=	(Equals sign)			
	62	>	(Greater-than sign ; Inequality) 			
	63	?	(Question mark)			
	64	@	(At sign)			
	65	A	(Capital A )			
	66	B	(Capital B )			
	67	C	(Capital C )			
	68	D	(Capital D )			
	69	E	(Capital E )			
	70	F	(Capital F )			
	71	G	(Capital G )			
	72	H	(Capital H )			
	73	I	(Capital I )			
	74	J	(Capital J )			
	75	K	(Capital K )			
	76	L	(Capital L )			
	77	M	(Capital M )			
	78	N	(Capital N )			
	79	O	(Capital O )			
	80	P	(Capital P )			
	81	Q	(Capital Q )			
	82	R	(Capital R )			
	83	S	(Capital S )			
	84	T	(Capital T )			
	85	U	(Capital U )			
	86	V	(Capital V )			
	87	W	(Capital W )			
	88	X	(Capital X )			
	89	Y	(Capital Y )			
	90	Z	(Capital Z )			
	91	[	(square brackets or box brackets)			
	92	\	(Backslash)			
	93	]	(square brackets or box brackets)			
	94	^	(Caret or circumflex accent)			
	95	_	(underscore , understrike , underbar or low line)			
	96	`	(Grave accent)			
	97	a	(Lowercase  a )			
	98	b	(Lowercase  b )			
	99	c	(Lowercase  c )			
	100	d	(Lowercase  d )			
	101	e	(Lowercase  e )			
	102	f	(Lowercase  f )			
	103	g	(Lowercase  g )			
	104	h	(Lowercase  h )			
	105	i	(Lowercase  i )			
	106	j	(Lowercase  j )			
	107	k	(Lowercase  k )			
	108	l	(Lowercase  l )			
	109	m	(Lowercase  m )			
	110	n	(Lowercase  n )			
	111	o	(Lowercase  o )			
	112	p	(Lowercase  p )			
	113	q	(Lowercase  q )			
	114	r	(Lowercase  r )			
	115	s	(Lowercase  s )			
	116	t	(Lowercase  t )			
	117	u	(Lowercase  u )			
	118	v	(Lowercase  v )			
	119	w	(Lowercase  w )			
	120	x	(Lowercase  x )			
	121	y	(Lowercase  y )			
	122	z	(Lowercase  z )			
	123	{	(curly brackets or braces)			
	124	|	(vertical-bar, vbar, vertical line or vertical slash)			
	125	}	(curly brackets or braces)			
	126	~	(Tilde ; swung dash)			
	127	DEL	(Delete)			
						
	128	Ç	(Majuscule C-cedilla )			
	129	ü	(letter "u" with umlaut or diaeresis ; "u-umlaut")			
	130	é	(letter "e" with acute accent or "e-acute")			
	131	â	(letter "a" with circumflex accent or "a-circumflex")			
	132	ä	(letter "a" with umlaut or diaeresis ; "a-umlaut")			
	133	à	(letter "a" with grave accent)			
	134	å	(letter "a"  with a ring)			
	135	ç	(Minuscule c-cedilla)			
	136	ê	(letter "e" with circumflex accent or "e-circumflex")			
	137	ë	(letter "e" with umlaut or diaeresis ; "e-umlaut")			
	138	è	(letter "e" with grave accent)			
	139	ï	(letter "i" with umlaut or diaeresis ; "i-umlaut")			
	140	î	(letter "i" with circumflex accent or "i-circumflex")			
	141	ì	(letter "i" with grave accent)			
	142	Ä	(letter "A" with umlaut or diaeresis ; "A-umlaut")			
	143	Å	(letter "A"  with a ring)			
	144	É	(Capital letter "E" with acute accent or "E-acute")			
	145	æ	(Latin diphthong "ae")			
	146	Æ	(Latin diphthong "AE")			
	147	ô	(letter "o" with circumflex accent or "o-circumflex")			
	148	ö	(letter "o" with umlaut or diaeresis ; "o-umlaut")			
	149	ò	(letter "o" with grave accent)			
	150	û	(letter "u" with circumflex accent or "u-circumflex")			
	151	ù	(letter "u" with grave accent)			
	152	ÿ	(letter "y" with diaeresis)			
	153	Ö	(letter "O" with umlaut or diaeresis ; "O-umlaut")			
	154	Ü	(letter "U" with umlaut or diaeresis ; "U-umlaut")			
	155	ø	(slashed zero or empty set)			
	156	£	(Pound sign ; symbol for the pound sterling)			
	157	Ø	(slashed zero or empty set)			
	158	×	(multiplication sign)			
	159	ƒ	(function sign ; f with hook sign ; florin sign )			
	160	á	(letter "a" with acute accent or "a-acute")			
	161	í	(letter "i" with acute accent or "i-acute")			
	162	ó	(letter "o" with acute accent or "o-acute")			
	163	ú	(letter "u" with acute accent or "u-acute")			
	164	ñ	(letter "n" with tilde ; enye)			
	165	Ñ	(letter "N" with tilde ; enye)			
	166	ª	(feminine ordinal indicator )			
	167	º	(masculine ordinal indicator)			
	168	¿	(Inverted question marks)			
	169	®	(Registered trademark symbol)			
	170	¬	(Logical negation symbol)			
	171	½	(One half)			
	172	¼	(Quarter or  one fourth)			
	173	¡	(Inverted exclamation marks)			
	174	«	(Guillemets or  angle quotes)			
	175	»	(Guillemets or  angle quotes)			
	176	░				
	177	▒				
	178	▓				
	179	│	(Box drawing character)			
	180	┤	(Box drawing character)			
	181	Á	(Capital letter "A" with acute accent or "A-acute")			
	182	Â	(letter "A" with circumflex accent or "A-circumflex")			
	183	À	(letter "A" with grave accent)			
	184	©	(Copyright symbol)			
	185	╣	(Box drawing character)			
	186	║	(Box drawing character)			
	187	╗	(Box drawing character)			
	188	╝	(Box drawing character)			
	189	¢	(Cent symbol)			
	190	¥	(YEN and YUAN sign)			
	191	┐	(Box drawing character)			
	192	└	(Box drawing character)			
	193	┴	(Box drawing character)			
	194	┬	(Box drawing character)			
	195	├	(Box drawing character)			
	196	─	(Box drawing character)			
	197	┼	(Box drawing character)			
	198	ã	(letter "a" with tilde or "a-tilde")			
	199	Ã	(letter "A" with tilde or "A-tilde")			
	200	╚	(Box drawing character)			
	201	╔	(Box drawing character)			
	202	╩	(Box drawing character)			
	203	╦	(Box drawing character)			
	204	╠	(Box drawing character)			
	205	═	(Box drawing character)			
	206	╬	(Box drawing character)			
	207	¤	(generic currency sign )			
	208	ð	(lowercase "eth")			
	209	Ð	(Capital letter "Eth")			
	210	Ê	(letter "E" with circumflex accent or "E-circumflex")			
	211	Ë	(letter "E" with umlaut or diaeresis ; "E-umlaut")			
	212	È	(letter "E" with grave accent)			
	213	ı	(lowercase dot less i)			
	214	Í	(Capital letter "I" with acute accent or "I-acute")			
	215	Î	(letter "I" with circumflex accent or "I-circumflex")			
	216	Ï	(letter "I" with umlaut or diaeresis ; "I-umlaut")			
	217	┘	(Box drawing character)			
	218	┌	(Box drawing character)			
	219	█	(Block)			
	220	▄				
	221	¦	(vertical broken bar )			
	222	Ì	(letter "I" with grave accent)			
	223	▀				
	224	Ó	(Capital letter "O" with acute accent or "O-acute")			
	225	ß	(letter "Eszett" ; "scharfes S" or "sharp S")			
	226	Ô	(letter "O" with circumflex accent or "O-circumflex")			
	227	Ò	(letter "O" with grave accent)			
	228	õ	(letter "o" with tilde or "o-tilde")			
	229	Õ	(letter "O" with tilde or "O-tilde")			
	230	µ	(Lowercase letter "Mu" ; micro sign or micron)			
	231	þ	(capital letter "Thorn")			
	232	Þ	(lowercase letter "thorn")			
	233	Ú	(Capital letter "U" with acute accent or "U-acute")			
	234	Û	(letter "U" with circumflex accent or "U-circumflex")			
	235	Ù	(letter "U" with grave accent)			
	236	ý	(letter "y" with acute accent)			
	237	Ý	(Capital letter "Y" with acute accent)			
	238	¯	(macron symbol)			
	239	´	(Acute accent)			
	240	¬	(Hyphen)			
	241	±	(Plus-minus sign)			
	242	‗	(underline or underscore)			
	243	¾	(three quarters)			
	244	¶	(paragraph sign or pilcrow)			
	245	§	(Section sign)			
	246	÷	(The division sign ; Obelus)			
	247	¸	(cedilla)			
	248	°	(degree symbol )			
	249	¨	(Diaeresis)			
	250	•	(Interpunct or space dot)			
	251	¹	(superscript one)			
	252	³	(cube or superscript three)			
	253	²	(Square or superscript two)			
	254	■	(black square)			
	255	nbsp	(non-breaking space or no-break space)
```