# Corrected BuildingTypes Arrays

- Tiberian Sun
- Red Alert 2
- Yuri's Revenge

Westwood messed up a lot of object arrays in the rules(md).ini. While this proved no problem for them, due to their map editor, which was built to parse the INIs the same way RA2 did, and was actually usable unlike FinalAlert, and their AI Editor, this can cause a lot of problems for modders that write all their scripts by hand.

I have previously posted the corrected Animations array for YR, and now I'm posting the corrected BuildingTypes arrays as well. When you write AI scripts, you can just use the exact number on the left of the building, no need to do funky +1 conversions (131072 in fact does affect the functionality, see ScriptActions#Building Indices). 

## Tiberian Sun

```ini
[BuildingTypes]
0=GAPOWR
1=PROC
2=GASILO
3=GAPILE
4=GAPLUG
5=GACTWR
6=GAVULC
7=GASAND
8=GAFIRE
9=GADEPT
10=GATECH
11=GAWEAP
12=GACNST
13=GAHPAD
14=NAPOWR
15=NATECH
16=NAHAND
17=NAAPWR
18=GAWALL
19=CABHUT
20=NAPULS
21=GAGATE_A
22=GAGATE_B
23=NAWEAP
24=NASTLH
25=GALITE
26=REDLAMP
27=GRENLAMP
28=BLUELAMP
29=YELWLAMP
30=PURPLAMP
31=INORANLAMP
32=INGRNLMP
33=INREDLMP
34=NAWALL
35=INBLULMP
36=NATMPL
37=NAGATE_A
38=NAGATE_B
39=NAWAST
40=NAOBEL
41=NAMISL
42=GAPOWRUP
43=NAPOST
44=NAFNCE
45=NALASR
46=NASAM
47=CITY01
48=CITY02
49=CITY03
50=CITY04
51=CITY05
52=CITY06
53=CITY07
54=CITY08
55=CITY09
56=CITY10
57=CITY11
58=CITY12
59=CITY13
60=CITY14
61=CITY15
62=CITY16
63=CITY17
64=CITY18
65=CAHOSP
66=GASPOT
67=CTDAM
68=NARADR
69=GAROCK
70=INGALITE
71=INYELWLAMP
72=INPURPLAMP
73=GAPLUG1
74=GAPLUG2
75=GAPLUG3
76=GAFSDF
77=GARADR
78=BBOARD01
79=BBOARD02
80=BBOARD03
81=BBOARD04
82=BBOARD05
83=BBOARD06
84=BBOARD07
85=BBOARD08
86=BBOARD09
87=BBOARD10
88=BBOARD11
89=BBOARD12
90=BBOARD13
91=BBOARD14
92=BBOARD15
93=BBOARD16
94=NEGLAMP
95=NEGRED
96=ABAN01
97=ABAN02
98=ABAN03
99=ABAN04
100=ABAN05
101=ABAN06
102=ABAN07
103=ABAN08
104=ABAN09
105=ABAN10
106=ABAN11
107=ABAN12
108=ABAN13
109=ABAN14
110=ABAN15
111=ABAN16
112=ABAN17
113=ABAN18
114=CITY19
115=CITY20
116=CITY21
117=NTPYRA
118=CITY22
119=CTVEGA
120=GADPSA
121=CA0001
122=CA0002
123=CA0003
124=CA0004
125=CA0005
126=CA0006
127=CA0007
128=CA0008
129=CA0009
130=CA0010
131=CA0011
132=CA0012
133=CA0013
134=CA0014
135=CA0015
136=CA0016
137=CA0017
138=CA0018
139=CA0019
140=CA0020
141=CA0021
142=CAARMR
143=GACSAM
144=GATICK
145=CAPYR01
146=CAPYR02
147=CAPYR03
148=CACRSH01
149=CACRSH02
150=CACRSH03
151=CACRSH04
152=CACRSH05
153=CAARAY
154=GAICBM
155=GAOLDCC1
156=GAOLDCC2
157=GAOLDCC3
158=GAOLDCC4
159=GAOLDCC5
160=GAOLDCC6
161=GAARTY
162=TSTLAMP
163=NAHPAD
164=GAKODK
165=NAMNTK
166=UFO
167=AMMOCRAT
168=GAPAVE
169=GAGREEN
```

## Red Alert 2

```ini
[BuildingTypes]
0=GAPOWR
1=GAREFN
2=GACNST
3=GAPILE
4=GASAND
5=GADEPT
6=GATECH
7=GAWEAP
8=CALAB
9=NAPOWR
10=NATECH
11=NAHAND
12=GAWALL
13=NARADR
14=NAWEAP
15=NAREFN
16=NAWALL
17=CAHSE07
18=NAPSIS
19=NAWAST
20=NALASR
21=NASAM
22=GARADR
23=GAYARD
24=NAIRON
25=NACNST
26=NADEPT
27=GACSPH
28=GADUMY
29=GAWEAT
30=CABHUT
31=GALITE
32=REDLAMP
33=GRENLAMP
34=BLUELAMP
35=YELWLAMP
36=PURPLAMP
37=INORANLAMP
38=INGRNLMP
39=INREDLMP
40=INBLULMP
41=CITY01
42=CITY02
43=CITY03
44=CITY04
45=CITY05
46=CITY06
47=CAHOSP
48=INGALITE
49=INYELWLAMP
50=INPURPLAMP
51=NEGLAMP
52=NEGRED
53=TESLA
54=NAMISL
55=ATESLA
56=CAARMR
57=TSTLAMP
58=NAHPAD
59=AMMOCRAT
60=GAGREEN
61=NAYARD
62=GASPYSAT
63=GAGAP
64=GTGCAN
65=NANRCT
66=GAPILL
67=NAFLAK
68=CAOUTP
69=CATHOSP
70=CAAIRP
71=CAOILD
72=NACLON
73=GAOREP
74=CACITY01
75=CACITY02
76=CACITY03
77=CACITY04
78=CANEWY01
79=CANEWY04
80=CANEWY05
81=CASWST01
82=CATECH01
83=CATEXS01
84=CATEXS02
85=CAWASH01
86=CAFARM01
87=CAFARM02
88=CALIT01E
89=CALIT01N
90=CALIT01S
91=CALIT01W
92=CAMISC01
93=CAMISC02
94=CAMISC03
95=CAMISC04
96=CAPOL01E
97=CAPOL01N
98=CAPOL01S
99=CAPOL01W
100=CASIN01E
101=CASIN01N
102=CASIN01S
103=CASIN01W
104=CAPARS01
105=GAAIRC
106=CAFRMA
107=CAFRMB
108=CAWASH05
109=CAWASH04
110=CAWASH03
111=CAWASH07
112=CAWASH11
113=CAWSH12
114=CAWASH14
115=CAWASH09
116=CAWASH10
117=CAWASH13
118=CAARMY01
119=CAUSFGL
120=CAWASH08
121=CALIT03E
122=CALIT03N
123=CALIT03S
124=CALIT03W
125=CALIT02L
126=CALIT02R
127=CAHSE01
128=CAWT01
129=CATS01
130=CABARN02
131=CAWA2A
132=CAWA2B
133=CAWA2C
134=CAWA2D
135=AMRADR
136=CAPRS03
137=CAGARD01
138=CARUS01
139=CAMIAM01
140=CAEURO01
141=CAMIAM02
142=CANWY05
143=MAYAN
144=CAEUR1
145=CAEUR2
146=CAEUR04
147=CAMEX01
148=CARUS02A
149=CARUS02B
150=CARUS02C
151=CARUS02D
152=CARUS02E
153=CARUS02F
154=CANEWY06
155=CANEWY07
156=CANEWY08
157=CAPARS02
158=CAPARS08
159=CAPARS09
160=CARUS03
161=CANEWY10
162=CANEWY11
163=CANEWY12
164=CANEWY13
165=CANEWY14
166=CANEWY15
167=CANEWY16
168=CANEWY17
169=CANEWY18
170=CAPARS04
171=CAPARS05
172=CAPARS06
173=CAPARS07
174=CAWASH15
175=CAPARS10
176=CAPARS13
177=CAPARS14
178=CAGAS01
179=CAPARS11
180=CAPARS12
181=CAFARM06
182=CAMIAM04
183=NAPSYB
184=NAPSYA
185=CAIND01
186=CACOLO01
187=CANWY09
188=CANWY22
189=CANWY23
190=CANWY24
191=CANWY25
192=CANWY26
193=CATEXS03
194=CATEXS04
195=CATEXS05
196=CARUS02G
197=CACHIG04
198=CAMIAM03
199=CARUS07
200=CATEXS06
201=CATEXS07
202=CATEXS08
203=CACHIG01
204=CACHIG02
205=CACHIG03
206=CAWASH16
207=CAWASH17
208=CACHIG05
209=CAWASH19
210=CARUS08
211=CARUS09
212=CARUS10
213=CARUS11
214=CANEWY20
215=CANEWY21
216=CARUS04
217=CARUS05
218=CARUS06
219=CAMSC01
220=CAMSC02
221=CAMSC03
222=CAMSC04
223=CAMSC05
224=CAMSC06
225=CAMSC07
226=CAWASH18
227=CAEURO05
228=CAPARK01
229=CAPARK02
230=CAPARK03
231=CAHSE02
232=CAHSE03
233=CAHSE04
234=CASTRT01
235=CASTRT02
236=CASTL01
237=CASTL02
238=CASTL03
239=CASTL04
240=CAHSE05
241=CAHSE06
242=CAMIAM05
243=CAMIAM06
244=CAMIAM07
245=CAFNCB
246=CAFNCW
247=CAMEX02
248=CAMEX03
249=CAMEX04
250=CAMEX05
251=CACHIG06
252=CAMSC08
253=CAMSC09
254=CAARMY02
255=CAARMY03
256=CAARMY04
257=TEMMORLAMP
258=TEMDAYLAMP
259=TEMDUSLAMP
260=TEMNITLAMP
261=SNOMORLAMP
262=SNODAYLAMP
263=SNODUSLAMP
264=SNONITLAMP
265=CAKRMW
266=CARUFGL
267=CAFRFGL
268=CAIRSFGL
269=CACUFGL
270=CASKFGL
271=CALBFGL
272=CAMIAM08
273=CAMISC05
274=CAMISC06
275=CASTL05A
276=CASTL05B
277=CASTL05C
278=CASTL05D
279=CASTL05E
280=CASTL05F
281=CASTL05G
282=CASTL05H
283=CAMSC10
284=CAGEFGL
285=CAUKFGL
286=CAWASH06
287=CAMSC11
288=CAMSC12
289=CAMSC13
290=CAPOFGL
291=CAMSC12A
292=CAMOV01
293=CAMOV02
294=CABUNK01
295=CABUNK02
296=CAFNCP
297=CASTRT03
298=CASTRT04
299=CASTRT05
```

## Yuri's Revenge

```ini
[BuildingTypes]
0=GAPOWR
1=GAREFN
2=GACNST
3=GAPILE
4=GASAND
5=GADEPT
6=GATECH
7=GAWEAP
8=CALAB
9=NAPOWR
10=NATECH
11=NAHAND
12=GAWALL
13=NARADR
14=NAWEAP
15=NAREFN
16=NAWALL
17=CAHSE07
18=NAPSIS
19=CASYDN01
20=NALASR
21=NASAM
22=CASYDN02
23=GAYARD
24=NAIRON
25=NACNST
26=NADEPT
27=GACSPH
28=GADUMY
29=GAWEAT
30=CABHUT
31=GALITE
32=REDLAMP
33=GRENLAMP
34=BLUELAMP
35=YELWLAMP
36=PURPLAMP
37=INORANLAMP
38=INGRNLMP
39=INREDLMP
40=INBLULMP
41=CITY01
42=CITY02
43=CITY03
44=CITY04
45=CITY05
46=CITY06
47=CAHOSP
48=INGALITE
49=INYELWLAMP
50=INPURPLAMP
51=NEGLAMP
52=NEGRED
53=TESLA
54=NAMISL
55=ATESLA
56=CAMACH
57=TSTLAMP
58=CASYDN03
59=AMMOCRAT
60=GAGREEN
61=NAYARD
62=GASPYSAT
63=GAGAP
64=GTGCAN
65=NANRCT
66=GAPILL
67=NAFLAK
68=CAOUTP
69=CATHOSP
70=CAAIRP
71=CAOILD
72=NACLON
73=GAOREP
74=CACITY01
75=CACITY02
76=CACITY03
77=CACITY04
78=CANEWY01
79=CANEWY04
80=CANEWY05
81=CASWST01
82=CATECH01
83=CATEXS01
84=CATEXS02
85=CAWASH01
86=CAFARM01
87=CAFARM02
88=CALIT01E
89=CALIT01N
90=CALIT01S
91=CALIT01W
92=CAMISC01
93=CAMISC02
94=CAMISC03
95=CAMISC04
96=CAPOL01E
97=CAPOL01N
98=CAPOL01S
99=CAPOL01W
100=CASIN01E
101=CASIN01N
102=CASIN01S
103=CASIN01W
104=CAPARS01
105=GAAIRC
106=CAFRMA
107=CAFRMB
108=CAWASH05
109=CAWASH04
110=CAWASH03
111=CAWASH07
112=CAWASH11
113=CAWSH12
114=CAWASH14
115=CAWASH09
116=CAWASH10
117=CAWASH13
118=CAARMY01
119=CAUSFGL
120=CAWASH08
121=CALIT03E
122=CALIT03N
123=CALIT03S
124=CALIT03W
125=CALIT02L
126=CALIT02R
127=CAHSE01
128=CAWT01
129=CATS01
130=CABARN02
131=CAWA2A
132=CAWA2B
133=CAWA2C
134=CAWA2D
135=AMRADR
136=CAPRS03
137=CAGARD01
138=CARUS01
139=CAMIAM01
140=CATRAN01
141=CAMIAM02
142=CANWY05
143=MAYAN
144=CAEUR1
145=CAEUR2
146=CAEUR04
147=CAMEX01
148=CARUS02A
149=CARUS02B
150=CARUS02C
151=CARUS02D
152=CARUS02E
153=CARUS02F
154=CANEWY06
155=CANEWY07
156=CANEWY08
157=CAPARS02
158=CAPARS08
159=CAPARS09
160=CARUS03
161=CANEWY10
162=CANEWY11
163=CANEWY12
164=CANEWY13
165=CANEWY14
166=CANEWY15
167=CANEWY16
168=CANEWY17
169=CANEWY18
170=CAPARS04
171=CAPARS05
172=CAPARS06
173=CAPARS07
174=CAWASH15
175=CAPARS10
176=CAPARS13
177=CAPARS14
178=CAGAS01
179=CAPARS11
180=CAPARS12
181=CAFARM06
182=CAMIAM04
183=NAPSYB
184=NAPSYA
185=CAIND01
186=CACOLO01
187=CANWY09
188=CANWY22
189=CANWY23
190=CANWY24
191=CANWY25
192=CANWY26
193=CATEXS03
194=CATEXS04
195=CATEXS05
196=CARUS02G
197=CACHIG04
198=CAMIAM03
199=CARUS07
200=CATEXS06
201=CATEXS07
202=CATEXS08
203=CACHIG01
204=CACHIG02
205=CACHIG03
206=CAWASH16
207=CAWASH17
208=CACHIG05
209=CAWASH19
210=CARUS08
211=CARUS09
212=CARUS10
213=CARUS11
214=CANEWY20
215=CANEWY21
216=CARUS04
217=CARUS05
218=CARUS06
219=CAMSC01
220=CAMSC02
221=CAMSC03
222=CAMSC04
223=CAMSC05
224=CAMSC06
225=CAMSC07
226=CAWASH18
227=CAEURO05
228=CAPARK01
229=CAPARK02
230=CAPARK03
231=CAHSE02
232=CAHSE03
233=CAHSE04
234=CASTRT01
235=CASTRT02
236=CASTL01
237=CASTL02
238=CASTL03
239=CASTL04
240=CAHSE05
241=CAHSE06
242=CAMIAM05
243=CAMIAM06
244=CAMIAM07
245=CAFNCB
246=CAFNCW
247=CAMEX02
248=CAMEX03
249=CAMEX04
250=CAMEX05
251=CACHIG06
252=CAMSC08
253=CAMSC09
254=CAARMY02
255=CAARMY03
256=CAARMY04
257=TEMMORLAMP
258=TEMDAYLAMP
259=TEMDUSLAMP
260=TEMNITLAMP
261=SNOMORLAMP
262=SNODAYLAMP
263=SNODUSLAMP
264=SNONITLAMP
265=CAKRMW
266=CARUFGL
267=CAFRFGL
268=CATRAN02
269=CACUFGL
270=CASKFGL
271=CALBFGL
272=CAMIAM08
273=CAMISC05
274=CAMISC06
275=CASTL05A
276=CASTL05B
277=CASTL05C
278=CASTL05D
279=CASTL05E
280=CASTL05F
281=CASTL05G
282=CASTL05H
283=CAMSC10
284=CAGEFGL
285=CAUKFGL
286=CAWASH06
287=CAMSC11
288=CAMSC12
289=CAMSC13
290=CAPOFGL
291=CAMSC12A
292=CAMOV01
293=CAMOV02
294=CABUNK01
295=CABUNK02
296=CAFNCP
297=CASTRT03
298=CASTRT04
299=CASTRT05
300=YACNST
301=YAPOWR
302=YABRCK
303=YAWEAP
304=YAYARD
305=YADEPT
306=YATECH
307=GAFWLL
308=YAGGUN
309=YAPSYT
310=NAINDP
311=YAGRND
312=YAGNTC
313=CASLAB
314=CATIME
315=YAPPET
316=CALOND04
317=CALOND05
318=CALOND06
319=CAMOON01
320=CATRAN03
321=CAEAST01
322=CAEGYP01
323=CAEGYP02
324=CAEGYP03
325=CALA01
326=CALA02
327=CALA03
328=CALA04
329=CALA05
330=CALOND01
331=CALOND02
332=CALOND03
333=CAMORR01
334=CAMORR02
335=CAMORR03
336=CASANF01
337=CASANF02
338=CASANF03
339=CASANF04
340=CASANF05
341=CASEAT01
342=NATBNK
343=GAGATE_A 
344=CASANF09
345=CASANF10
346=CASANF11
347=CASANF12
348=CASANF13
349=CASANF14
350=CASANF06
351=CASANF07
352=CASANF08
353=CASEAT02
354=YACOMD
355=YAPPPT
356=GAROBO
357=YAREFN
358=YAROCK
359=NABNKR
360=CASANF15
361=CASANF16
362=CASANF17
363=CASANF18
364=CASIN03E
365=CASIN03S
366=CAURB01
367=CAURB02
368=CAURB03
369=CAPOWR
370=CALA07
371=CAEGYP06
372=CALA08
373=CAEAST02
374=CABARR01
375=CABARR02
376=CAMORR04
377=CAMORR05
378=CALA09
379=CAEGYP04
380=CAEGYP05
381=CALA06
382=CAMORR06
383=CAMORR07
384=CAMORR08
385=CAMORR09
386=CAMORR10
387=CATIME01
388=CATIME02
389=CALA10
390=CALA11
391=CALA12
392=CALA13
393=CAPARK04
394=CAPARK05
395=CAPARK06
396=CALA14
397=CALA15
398=CABUNK03
399=CABUNK04
400=CALUNR01
401=CALUNR02
```