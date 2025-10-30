# dragningOCR
En transparent och verifierbar utlottning

RÄTTVIST OCH VERIFIERBART LOTTERI – 31 OKTOBER 2025
====================================================

Detta dokument beskriver hur utlottningen genomförs på ett sätt som är öppet, slumpmässigt och omöjligt att fuska med.
All information här publiceras i förväg och sparas automatiskt av GitHub med tidstämpel, så att ingen kan ändra något i efterhand.

----------------------------------------------------
DELTAGARE
----------------------------------------------------
Det finns 178 deltagare i utlottningen, se listan längst ner med namn, som fått lottnummer mellan 0-177.

----------------------------------------------------
SLUMPKÄLLA
----------------------------------------------------
Slumpen bestäms av Bitcoin-blockkedjan, som är en publik och oförutsägbar databas.

Vi använder:
Det första Bitcoin-blocket som bryts efter kl. 20:00:00 UTC den 30 oktober 2025.

När blocket har hittats (och fått minst 6 bekräftelser) tar vi dess blockhash – en lång rad med bokstäver och siffror som är omöjlig att förutse.

Exempel på en blockhash:
00000000000000000000ed7f0593fbeb4f2cc529426bbd6d724e009144f6df9d

----------------------------------------------------
HUR VINNAREN RÄKNAS FRAM
----------------------------------------------------
När blockhashen är känd görs följande steg (alla kan själva göra samma beräkning):

1. Beräkna SHA256-hash av blockhashen. (Med t.ex https://emn178.github.io/online-tools/sha256.html)

2. Gör om resultatet till ett stort tal (ENDAST DE 8 SISTA HEXADECIMALTECKNENA KOMMER ANVÄNDAS DÅ TALET ANNARS BLIR FÖR STORT). (Med t.ex https://www.rapidtables.com/convert/number/hex-to-decimal.html)

3. Dividera talet med 178 och ta resten:
   vinnarnummer = (tal % 178)

4. Personen med det numret i listan vinner.

----------------------------------------------------
VARFÖR DET ÄR RÄTTVIST
----------------------------------------------------
- Blockhashen är helt slumpmässig och offentlig.
- Listan över deltagare publiceras innan blocket finns.
- Formeln är enkel och går att kontrollera av vem som helst.
- GitHub visar exakt när denna fil skapades och om den skulle ändras i efterhand.

Detta gör att dragningen är helt transparent, reproducerbar och rättvis.

----------------------------------------------------
EFTER DRAGNINGEN
----------------------------------------------------
När blocket efter kl. 20:00:00 UTC den 31 oktober 2025 har skapats, publiceras:
- Det använda blockets hash och blocknummer
- Den beräknade SHA256-hashen
- Vinnarnumret och vinnarnamnet

Alla kan själva kontrollera resultatet med hjälp av den öppna formeln ovan.

Nedan följer namnen på deltagarna

0	Alexander Fil
1	Alexandra Lun
2	Alisa Pla
3	Alvin Kje
4	Amanda Ste
5	Andreas Öbe
6	Andreas Sve
7	Anibal Oro
8	Anna Dju
9	Anna Erl
10	Anna Mol
11	Annika Eek
12	Aron Kin
13	Billy Joh
14	Björn Ric
15	Carolina Joh
16	Cecilia Ode
17	Charlotte Di
18	Christofer Tre
19	Cladam Eng
20	Clara sta
21	Daniel Eks
22	Daniel KIn
23	Daniel Kla
24	Daniel Ott
25	Daniel Res
26	David Bus
27	David Jon
28	Ebba
29	Ebbe Ber
30	Elias Erd
31	Elias lac
32	Elin Lju
33	Elin Lun
34	Ella Jac
35	Ellinor Vas
36	Emelie Hor
37	Emma Åda
38	Emma Dah
39	Emma Eri
40	Emma Fri
41	Eric ekb
42	Erik Joh
43	Ewelina Sve
44	Freddan
45	Fredric mar
46	Fredrik Kli
47	Fredrik Ste
48	Frida Ekm
49	Frida Hag
50	Gabriel Til
51	Göran Ack
52	Hans Löf
53	Hasse Bri
54	Hendrik Ger
55	Henric And
56	Henrik Gus
57	Isabella Nil
58	Jacob Maa
59	Jakob Son
60	Jan-Erik Lun
61	Jan-Erik Nau
62	Jenny Bor
63	Jesper Wah
64	Jimmy Alg
65	Joakim Lyd
66	Johan Bon
67	Johan Häg
68	Johan kin
69	Johan Lil
70	Johan Sve
71	Johanna Ber
72	Johanna Edl
73	Johanna Eri
74	Johannes Lar
75	Jonas Ahl
76	Jonas Joh
77	Jonas lar
78	Jonny Wol
79	Juan Mal
80	Kajsa Ask
81	Kalle Eke
82	Karin For
83	Karolina sta
84	Kenny Kar
85	Kim Lin
86	Kim Wal
87	Kristofer Ber
88	Krystian Aff
89	Lena Kov
90	Lill Thu
91	Lillian Bje
92	Linda Dig
93	Linda Sve
94	Linnea Ste
95	Linus Fal
96	Liv Fos
97	Louise Nil
98	Louise Ran
99	Madeleine Lar
100	Magnus Fra
101	Magnus Mar
102	Maja Eng
103	Majlis Lar
104	Malin Beg
105	Marcus Bo
106	Marcus Lil
107	Maria Car
108	Maria Doy
109	Maria Hol
110	Maria Joh
111	Marianna Lan
112	Markus Hol
113	Markus Til
114	Märta Pau
115	Martin A A
116	Martin Joh
117	Martin Jon
118	Martin Nil
119	Mathias san
120	Mattias fri
121	Mattias Ham
122	Mattias Lin
123	Michael Gus
124	Mikael Ros
125	Mikael Stå
126	Mikaela Zer
127	Mio For
128	Miranda Joh
129	Nanny Kin
130	Niklas Ald
131	Niklas Mal
132	Nina kri
133	Nova Lac
134	Ola Ced
135	Ola Per
136	Olle Axe
137	Olof Edl
138	Olov Wes
139	Örjan And
140	Oscar nil
141	Patrik Joh
142	Paulina Dah
143	Per Jäg
144	Peter Eri
145	Pia kin
146	PO Fag
147	Pontus Dym
148	Pontus Gus
149	Ralf Isb
150	Rasmus Hol
151	Rasmus Joh
152	Rickard Han
153	Rickard Sko
154	Rikard Roi
155	Robert Jir
156	Robert Per
157	Said And
158	Sara Arv
159	Sara Bäc
160	Siri Eng
161	Sofie Hel
162	Staffan Wen
163	Sven Joh
164	Sven M
165	Therese Eli
166	Thomas Ris
167	Tindra Axt
168	Tini Kje
169	Tobias Alf
170	Tobias Han
171	Tommy Bod
172	Toril Egn
173	Vahid Hag
174	Vanja Kar
175	Victor Joh
176	Vilhelm Dic
177	Willy For


Resultat!

Block hash från block utvunnet 20:01:36 UTC https://blockexplorer.one/bitcoin/mainnet/blockHash/0000000000000000000119124678c7031b6aeb77467991a8d92b97b943c38bbe
0000000000000000000119124678c7031b6aeb77467991a8d92b97b943c38bbe

SHA256 av 0000000000000000000119124678c7031b6aeb77467991a8d92b97b943c38bbe ger
4ce1746cb97f83075523a292c6eb5e9f629e7876d1b3a04e7e3387b96d6b854b

8 sista hexadecimaltecknena
6d6b854b

Hex to Dec ger
1835763019

1835763019 % 178 ger 69.

Vinnare är Johan Lil
