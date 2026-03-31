Assignment 1 – Regular Expressions (CBS4DH 2026)
Antonia Schmid, 11915531
Task 1 
a.)	CHAPTER\s+[IVXLCDM]+\.
Explanation: 
•	The word CHAPTER
•	One or more spaces
•	A Roman numeral
•	A period at the end
 Strengths
•	Simple and easy to understand
•	Works well for the original text format
Limitations
•	Only matches uppercase format
•	Requires a period
Matches:
match_num,content,group_num,group_name,start_pos,end_pos
0,CHAPTER II.,0,null,40008,40019
1,CHAPTER III.,0,null,44436,44448
2,CHAPTER IV.,0,null,54214,54225
3,CHAPTER V.,0,null,60239,60249
4,CHAPTER VI.,0,null,65666,65677
5,CHAPTER VII.,0,null,78898,78910
6,CHAPTER VIII.,0,null,90319,90332
7,CHAPTER IX.,0,null,101463,101474
8,CHAPTER X.,0,null,111288,111298
9,CHAPTER XI.,0,null,123996,124007
10,CHAPTER XII.,0,null,132999,133011
11,CHAPTER XV.,0,null,153092,153103
12,CHAPTER XVI.,0,null,162938,162950
13,CHAPTER XVII.,0,null,182210,182223
14,CHAPTER XVIII.,0,null,189544,189558
15,CHAPTER XIX.,0,null,218947,218959
16,CHAPTER XX.,0,null,229673,229684
17,CHAPTER XXI.,0,null,238973,238985
18,CHAPTER XXII.,0,null,250400,250413
19,CHAPTER XXIII.,0,null,260638,260652
20,CHAPTER XXIV.,0,null,270080,270093
21,CHAPTER XXV.,0,null,280969,280981
22,CHAPTER XXVI.,0,null,289759,289772
23,CHAPTER XXVII.,0,null,302816,302830
24,CHAPTER XXVIII.,0,null,310120,310135
25,CHAPTER XXIX.,0,null,318606,318619
26,CHAPTER XXX.,0,null,332350,332362
27,CHAPTER XXXI.,0,null,339628,339641
28,CHAPTER XXXII.,0,null,348434,348448
29,CHAPTER XXXIII.,0,null,357061,357076
30,CHAPTER XXXIV.,0,null,367507,367521
31,CHAPTER XXXV.,0,null,379604,379617
32,CHAPTER XXXVI.,0,null,396642,396656
33,CHAPTER XXXVII.,0,null,408612,408627
34,CHAPTER XXXVIII.,0,null,416554,416570
35,CHAPTER XXXIX.,0,null,422666,422680
36,CHAPTER XL.,0,null,431517,431528
37,CHAPTER XLI.,0,null,440927,440939
38,CHAPTER XLII.,0,null,454111,454124
39,CHAPTER XLIII.,0,null,464840,464854
40,CHAPTER XLIV.,0,null,492419,492432
41,CHAPTER XLV.,0,null,505975,505987
42,CHAPTER XLVII.,0,null,533240,533254
43,CHAPTER XLVIII.,0,null,555765,555780
44,CHAPTER XLIX.,0,null,568660,568673
45,CHAPTER L.,0,null,581323,581333
46,CHAPTER LI.,0,null,593933,593944
47,CHAPTER LII.,0,null,605264,605276
48,CHAPTER LIII.,0,null,622665,622678
49,CHAPTER LIV.,0,null,638867,638879
50,CHAPTER LV.,0,null,647869,647880
51,CHAPTER LVI.,0,null,660923,660935
52,CHAPTER LVII.,0,null,676457,676470
53,CHAPTER LVIII.,0,null,685992,686006
54,CHAPTER LIX.,0,null,699799,699811
55,CHAPTER LX.,0,null,713484,713495
56,CHAPTER LXI.,0,null,722277,722289

b.)	^CHAPTER\s+[IVXLCDM]+\.
Explanation: 
•	The match occurs at the start of a line
 Strengths
•	More precise
•	Avoids matching text inside sentences
Limitations
•	Only works if headings are actually at the beginning of a line
Matches:
match_num,content,group_num,group_name,start_pos,end_pos
0,CHAPTER II.,0,null,40008,40019
1,CHAPTER III.,0,null,44436,44448
2,CHAPTER IV.,0,null,54214,54225
3,CHAPTER V.,0,null,60239,60249
4,CHAPTER VI.,0,null,65666,65677
5,CHAPTER VII.,0,null,78898,78910
6,CHAPTER VIII.,0,null,90319,90332
7,CHAPTER IX.,0,null,101463,101474
8,CHAPTER X.,0,null,111288,111298
9,CHAPTER XI.,0,null,123996,124007
10,CHAPTER XII.,0,null,132999,133011
11,CHAPTER XV.,0,null,153092,153103
12,CHAPTER XVI.,0,null,162938,162950
13,CHAPTER XVII.,0,null,182210,182223
14,CHAPTER XVIII.,0,null,189544,189558
15,CHAPTER XIX.,0,null,218947,218959
16,CHAPTER XX.,0,null,229673,229684
17,CHAPTER XXI.,0,null,238973,238985
18,CHAPTER XXII.,0,null,250400,250413
19,CHAPTER XXIII.,0,null,260638,260652
20,CHAPTER XXIV.,0,null,270080,270093
21,CHAPTER XXV.,0,null,280969,280981
22,CHAPTER XXVI.,0,null,289759,289772
23,CHAPTER XXVII.,0,null,302816,302830
24,CHAPTER XXVIII.,0,null,310120,310135
25,CHAPTER XXIX.,0,null,318606,318619
26,CHAPTER XXX.,0,null,332350,332362
27,CHAPTER XXXI.,0,null,339628,339641
28,CHAPTER XXXII.,0,null,348434,348448
29,CHAPTER XXXIII.,0,null,357061,357076
30,CHAPTER XXXIV.,0,null,367507,367521
31,CHAPTER XXXV.,0,null,379604,379617
32,CHAPTER XXXVI.,0,null,396642,396656
33,CHAPTER XXXVII.,0,null,408612,408627
34,CHAPTER XXXVIII.,0,null,416554,416570
35,CHAPTER XXXIX.,0,null,422666,422680
36,CHAPTER XL.,0,null,431517,431528
37,CHAPTER XLI.,0,null,440927,440939
38,CHAPTER XLII.,0,null,454111,454124
39,CHAPTER XLIII.,0,null,464840,464854
40,CHAPTER XLIV.,0,null,492419,492432
41,CHAPTER XLV.,0,null,505975,505987
42,CHAPTER XLVII.,0,null,533240,533254
43,CHAPTER XLVIII.,0,null,555765,555780
44,CHAPTER XLIX.,0,null,568660,568673
45,CHAPTER L.,0,null,581323,581333
46,CHAPTER LI.,0,null,593933,593944
47,CHAPTER LII.,0,null,605264,605276
48,CHAPTER LIII.,0,null,622665,622678
49,CHAPTER LIV.,0,null,638867,638879
50,CHAPTER LV.,0,null,647869,647880
51,CHAPTER LVI.,0,null,660923,660935
52,CHAPTER LVII.,0,null,676457,676470
53,CHAPTER LVIII.,0,null,685992,686006
54,CHAPTER LIX.,0,null,699799,699811
55,CHAPTER LX.,0,null,713484,713495
56,CHAPTER LXI.,0,null,722277,72228

c.)	CHAPTER\s+[IVXLCDM]+\.?
Description
•	Makes the period optional
 Strengths
•	More robust to formatting variations
•	Works even if punctuation is inconsistent
Limitations
•	May produce false positives in less structured text
Matches:
 match_num,content,group_num,group_name,start_pos,end_pos
0,CHAPTER II.,0,null,40008,40019
1,CHAPTER III.,0,null,44436,44448
2,CHAPTER IV.,0,null,54214,54225
3,CHAPTER V.,0,null,60239,60249
4,CHAPTER VI.,0,null,65666,65677
5,CHAPTER VII.,0,null,78898,78910
6,CHAPTER VIII.,0,null,90319,90332
7,CHAPTER IX.,0,null,101463,101474
8,CHAPTER X.,0,null,111288,111298
9,CHAPTER XI.,0,null,123996,124007
10,CHAPTER XII.,0,null,132999,133011
11,CHAPTER XIII,0,null,136984,136996
12,CHAPTER XIV,0,null,146520,146531
13,CHAPTER XV.,0,null,153092,153103
14,CHAPTER XVI.,0,null,162938,162950
15,CHAPTER XVII.,0,null,182210,182223
16,CHAPTER XVIII.,0,null,189544,189558
17,CHAPTER XIX.,0,null,218947,218959
18,CHAPTER XX.,0,null,229673,229684
19,CHAPTER XXI.,0,null,238973,238985
20,CHAPTER XXII.,0,null,250400,250413
21,CHAPTER XXIII.,0,null,260638,260652
22,CHAPTER XXIV.,0,null,270080,270093
23,CHAPTER XXV.,0,null,280969,280981
24,CHAPTER XXVI.,0,null,289759,289772
25,CHAPTER XXVII.,0,null,302816,302830
26,CHAPTER XXVIII.,0,null,310120,310135
27,CHAPTER XXIX.,0,null,318606,318619
28,CHAPTER XXX.,0,null,332350,332362
29,CHAPTER XXXI.,0,null,339628,339641
30,CHAPTER XXXII.,0,null,348434,348448
31,CHAPTER XXXIII.,0,null,357061,357076
32,CHAPTER XXXIV.,0,null,367507,367521
33,CHAPTER XXXV.,0,null,379604,379617
34,CHAPTER XXXVI.,0,null,396642,396656
35,CHAPTER XXXVII.,0,null,408612,408627
36,CHAPTER XXXVIII.,0,null,416554,416570
37,CHAPTER XXXIX.,0,null,422666,422680
38,CHAPTER XL.,0,null,431517,431528
39,CHAPTER XLI.,0,null,440927,440939
40,CHAPTER XLII.,0,null,454111,454124
41,CHAPTER XLIII.,0,null,464840,464854
42,CHAPTER XLIV.,0,null,492419,492432
43,CHAPTER XLV.,0,null,505975,505987
44,CHAPTER XLVII.,0,null,533240,533254
45,CHAPTER XLVIII.,0,null,555765,555780
46,CHAPTER XLIX.,0,null,568660,568673
47,CHAPTER L.,0,null,581323,581333
48,CHAPTER LI.,0,null,593933,593944
49,CHAPTER LII.,0,null,605264,605276
50,CHAPTER LIII.,0,null,622665,622678
51,CHAPTER LIV.,0,null,638867,638879
52,CHAPTER LV.,0,null,647869,647880
53,CHAPTER LVI.,0,null,660923,660935
54,CHAPTER LVII.,0,null,676457,676470
55,CHAPTER LVIII.,0,null,685992,686006
56,CHAPTER LIX.,0,null,699799,699811
57,CHAPTER LX.,0,null,713484,713495
58,CHAPTER LXI.,0,null,722277,722289

Documentation: 
Regular expressions were used to extract chapter headings from the text, which follow the pattern “CHAPTER + Roman numeral”. Three approaches were implemented: a basic pattern, a line-anchored pattern for higher precision, and a flexible pattern allowing optional punctuation. The results show that stricter patterns are more precise, while flexible patterns capture more variations but may introduce incorrect matches.



Task 2 
a.)	“([^”]+)”
Explanation
•	“ → opening quotation mark
•	([^”]+) → capture everything inside (Group 1)
•	” → closing quotation mark
Strengths
•	Simple and effective
•	Captures clean dialogue
Limitations
•	Only works with curly quotes (“ ”)
•	Fails if quotes are missing or inconsistent

Matches: ( I didn’t include all matches because I would have about 400 pages at this point) 
match_num,content,group_num,group_name,start_pos,end_pos 0,“loving by allowance”,0,null,2631,2652 0,loving by allowance,1,null,2632,2651 1,“loving with personal love.”,0,null,2657,2685 1,loving with personal love.,1,null,2658,2684 2,“by allowance”,0,null,2985,2999 2,by allowance,1,null,2986,2998 3,"“Mr. Spectator,”",0,null,9376,9392 3,"Mr. Spectator,",1,null,9377,9391 4,“he admires your_ Spectators _mightily”,0,null,10744,10783 4,he admires your_ Spectators _mightily,1,null,10745,10782 5,“cynicism”,0,null,10971,10981 5,cynicism,1,null,10972,10980 6,“cynical”,0,null,11104,11113 6,cynical,1,null,11105,11112 7,"“the other side,”",0,null,11370,11387 7,"the other side,",1,null,11371,11386 8,"“the accepted hells beneath,”",0,null,11401,11430 8,"the accepted hells beneath,",1,null,11402,11429 9,"“metaphor has been exhausted in depicting the perfection of it, combined with the narrowness of her field;”",0,null,12180,12287 9,"metaphor has been exhausted in depicting the perfection of it, combined with the narrowness of her field;",1,null,12181,12286 10,“narrow”,0,null,12690,12698 10,narrow,1,null,12691,12697 11,“absolute.”,0,null,14394,14405 11,absolute.,1,null,14395,14404 12,“while Mrs. Bennet was stirring the fire”,0,null,15045,15086 12,while Mrs. Bennet was stirring the fire,1,null,15046,15085 13,"“brought his coffee-cup back_ himself,”",0,null,15163,15202 13,"brought his coffee-cup back_ himself,",1,null,15164,15201 14,“taller by the breadth of my nail”,0,null,15250,15284 14,taller by the breadth of my nail,1,null,15251,15283 15,"“metals, semi-metals, and distinguished philosophers.”",0,null,15957,16011 15,"metals, semi-metals, and distinguished philosophers.",1,null,15958,16010 16,"“miniature,”",0,null,16535,16547 16,"miniature,",1,null,16536,16546 17,“impropriety”,0,null,18053,18066 17,impropriety,1,null,18054,18065 18,"“My dear, do not give way to such gloomy thoughts. Let us hope for better things. Let us flatter ourselves that_ I _may be the survivor;”",0,null,18894,19031 18,"My dear, do not give way to such gloomy thoughts. Let us hope for better things. Let us flatter ourselves that_ I _may be the survivor;",1,null,18895,19030 19,"“May I ask whether these pleasing attentions proceed from the impulse of the moment, or are the result of previous study?”",0,null,19166,19288 19,"May I ask whether these pleasing attentions proceed from the impulse of the moment, or are the result of previous study?",1,null,19167,19287 20,“one of Mr. Philips’s clerks.”,0,null,20415,20445 20,one of Mr. Philips’s clerks.,1,null,20416,20444 21,"“scratches,”",0,null,24252,24264 21,"scratches,",1,null,24253,24263 22,“New Woman”,0,null,25850,25861 22,New Woman,1,null,25851,25860 23,“new”,0,null,25913,25918 23,new,1,null,25914,25917 24,"“impudent and mannish grown,”",0,null,26105,26134 24,"impudent and mannish grown,",1,null,26106,26133 25,“He came down to see the place”,0,null,28171,28202 25,He came down to see the place,1,null,28172,28201 26,“I hope Mr. Bingley will like it”,0,null,28319,28352 26,I hope Mr. Bingley will like it,1,null,28320,28351 27,“I’m the tallest”,0,null,28393,28410 27,I’m the tallest,1,null,28394,28409 28,“He rode a black horse”,0,null,28467,28490 28,He rode a black horse,1,null,28468,28489 29,“When the party entered”,0,null,28541,28565 29,When the party entered,1,null,28542,28564 30,“She is tolerable”,0,null,28615,28633 30,She is tolerable,1,null,28616,28632 31,“Without once opening his lips”,0,null,28837,28868 31,Without once opening his lips,1,null,28838,28867 32,“The entreaties of several”,0,null,29059,29086 32,The entreaties of several,1,null,29060,29085 33,“A note for Miss Bennet”,0,null,29133,29157 33,A note for Miss Bennet,1,null,29134,29156 34,“Cheerful prognostics”,0,null,29207,29229 34,Cheerful prognostics,1,null,29208,29228 35,“The apothecary came”,0,null,29281,29302 35,The apothecary came,1,null,29282,29301 36,“Covering a screen”,0,null,29355,29374 36,Covering a screen,1,null,29356,29373 37,“Mrs. Bennet and her two youngest girls”,0,null,29429,29469 37,Mrs. Bennet and her two youngest girls,1,null,29430,29468 38,"“No, no; stay where you are”",0,null,29577,29605 38,"No, no; stay where you are",1,null,29578,29604 39,“Piling up the fire”,0,null,29651,29671 39,Piling up the fire,1,null,29652,29670 40,“Protested that he never read novels”,0,null,29947,29984 40,Protested that he never read novels,1,null,29948,29983 41,“The officers of the ----shire”,0,null,30169,30200 41,The officers of the ----shire,1,null,30170,30199 42,“Delighted to see their dear friend again”,0,null,30243,30285 42,Delighted to see their dear friend again,1,null,30244,30284 43,“Such very superior dancing is not often seen”,0,null,30391,30437 43,Such very superior dancing is not often seen,1,null,30392,30436 44,“To assure you in the most animated language”,0,null,30465,30510 44,To assure you in the most animated language,1,null,30466,30509 45,“They entered the breakfast-room”,0,null,30613,30646 45,They entered the breakfast-room,1,null,30614,30645 46,“Walked back with them”,0,null,30761,30784 46,Walked back with them,1,null,30762,30783 47,“So much love and eloquence”,0,null,30909,30937 47,So much love and eloquence,1,null,30910,30936 48,“Protested he must be entirely mistaken”,0,null,30983,31023 48,Protested he must be entirely mistaken,1,null,30984,31022 49,“Whenever she spoke in a low voice”,0,null,31057,31092 49,Whenever she spoke in a low voice,1,null,31058,31091 50,“Offended two or three young ladies”,0,null,31279,31315 50,Offended two or three young ladies,1,null,31280,31314 51,“Will you come and see me?”,0,null,31353,31380 51,Will you come and see me?,1,null,31354,31379 52,“On the stairs”,0,null,31427,31442 52,On the stairs,1,null,31428,31441 53,“At the door”,0,null,31501,31514 53,At the door,1,null,31502,31513 54,“In conversation with the ladies”,0,null,31575,31608 54,In conversation with the ladies,1,null,31576,31607 55,"“Lady Catherine,”",0,null,31649,31666 55,"Lady Catherine,",1,null,31650,31665 56,“you have given me a treasure”,0,null,31677,31707 56,you have given me a treasure,1,null,31678,31706 57,“He never failed to inform them”,0,null,31797,31829 57,He never failed to inform them,1,null,31798,31828 58,“The gentlemen accompanied him”,0,null,31871,31902 58,The gentlemen accompanied him,1,null,31872,31901 59,“Accompanied by their aunt”,0,null,32093,32120 59,Accompanied by their aunt,1,null,32094,32119 60,“On looking up”,0,null,32167,32182 60,On looking up,1,null,32168,32181 61,“Hearing herself called”,0,null,32315,32339 61,Hearing herself called,1,null,32316,32338 62,“Meeting accidentally in town”,0,null,32463,32493 62,Meeting accidentally in town,1,null,32464,32492 63,“His parting obeisance”,0,null,32537,32560 63,His parting obeisance,1,null,32538,32559 64,“Dawson”,0,null,32611,32619 64,Dawson,1,null,32612,32618 65,“The elevation of his feelings”,0,null,32685,32716 65,The elevation of his feelings,1,null,32686,32715 66,“They had forgotten to leave any message”,0,null,32759,32800 66,They had forgotten to leave any message,1,null,32760,32799 67,“How nicely we are crammed in!”,0,null,32833,32864 67,How nicely we are crammed in!,1,null,32834,32863 68,“I am determined never to speak of it again”,0,null,32981,33025 68,I am determined never to speak of it again,1,null,32982,33024 69,“When Colonel Miller’s regiment went away”,0,null,33055,33097 69,When Colonel Miller’s regiment went away,1,null,33056,33096 70,“Tenderly flirting”,0,null,33129,33148 70,Tenderly flirting,1,null,33130,33147 71,“Conjecturing as to the date”,0,null,33277,33306 71,Conjecturing as to the date,1,null,33278,33305 72,“To make herself agreeable to all”,0,null,33425,33459 72,To make herself agreeable to all,1,null,33426,33458 73,“Engaged by the river”,0,null,33499,33521 73,Engaged by the river,1,null,33500,33520 74,“I have not an instant to lose”,0,null,33647,33678 74,I have not an instant to lose,1,null,33648,33677 75,“The first pleasing earnest of their welcome”,0,null,33721,33766 75,The first pleasing earnest of their welcome,1,null,33722,33765 76,“To whom I have related the affair”,0,null,33869,33904 76,To whom I have related the affair,1,null,33870,33903 77,“But perhaps you would like to read it”,0,null,34017,34056 77,But perhaps you would like to read it,1,null,34018,34055 78,“The spiteful old ladies”,0,null,34091,34116 78,The spiteful old ladies,1,null,34092,34115 79,“With an affectionate smile”,0,null,34165,34193 79,With an affectionate smile,1,null,34166,34192 80,“I am sure she did not listen”,0,null,34239,34269 80,I am sure she did not listen,1,null,34240,34268 81,“Mr. Darcy with him”,0,null,34313,34333 81,Mr. Darcy with him,1,null,34314,34332 82,“Jane happened to look round”,0,null,34387,34416 82,Jane happened to look round,1,null,34388,34415 83,“Mrs. Long and her nieces”,0,null,34461,34487 83,Mrs. Long and her nieces,1,null,34462,34486 84,"“Lizzy, my dear, I want to speak to you”",0,null,34535,34575 84,"Lizzy, my dear, I want to speak to you",1,null,34536,34574 85,“After a short survey”,0,null,34683,34705 85,After a short survey,1,null,34684,34704 86,“But now it comes out”,0,null,34757,34779 86,But now it comes out,1,null,34758,34778 87,“The efforts of his aunt”,0,null,34831,34856 87,The efforts of his aunt,1,null,34832,34855 88,“Unable to utter a syllable”,0,null,34905,34933 88,Unable to utter a syllable,1,null,34906,34932 89,“The obsequious civility”,0,null,34979,35004 89,The obsequious civility,1,null,34980,35003 90,"“My dear Mr. Bennet,”",0,null,35639,35660 90,"My dear Mr. Bennet,",1,null,35640,35659 91,“have you heard that Netherfield Park is let at last?”,0,null,35691,35745 91,have you heard that Netherfield Park is let at last?,1,null,35692,35744 92,"“But it is,”",0,null,35784,35796 92,"But it is,",1,null,35785,35795 93,"“for Mrs. Long has just been here, and she told me all about it.”",0,null,35811,35876 93,"for Mrs. Long has just been here, and she told me all about it.",1,null,35812,35875 94,“Do not you want to know who has taken it?”,0,null,35906,35949 94,Do not you want to know who has taken it?,1,null,35907,35948 95,"“_You_ want to tell me, and I have no objection to hearing it.”",0,null,35980,36043 95,"_You_ want to tell me, and I have no objection to hearing it.",1,null,35981,36042 96,“He came down to see the place”,0,null,36061,36092

b.)	[“"]([^”"]+)[”"]
Explanation
•	[“"] → opening quote (curly OR straight)
•	([^”"]+) → text inside
•	[”"] → closing quote
Strengths
•	Works with different quote styles
•	More robust for messy text
Limitations
•	Still fails with nested quotes
•	Cannot distinguish opening vs closing quotes perfectly



MatchesAgain not all matches):
match_num,content,group_num,group_name,start_pos,end_pos 0,“loving by allowance”,0,null,2631,2652 0,loving by allowance,1,null,2632,2651 1,“loving with personal love.”,0,null,2657,2685 1,loving with personal love.,1,null,2658,2684 2,“by allowance”,0,null,2985,2999 2,by allowance,1,null,2986,2998 3,"“Mr. Spectator,”",0,null,9376,9392 3,"Mr. Spectator,",1,null,9377,9391 4,“he admires your_ Spectators _mightily”,0,null,10744,10783 4,he admires your_ Spectators _mightily,1,null,10745,10782 5,“cynicism”,0,null,10971,10981 5,cynicism,1,null,10972,10980 6,“cynical”,0,null,11104,11113 6,cynical,1,null,11105,11112 7,"“the other side,”",0,null,11370,11387 7,"the other side,",1,null,11371,11386 8,"“the accepted hells beneath,”",0,null,11401,11430 8,"the accepted hells beneath,",1,null,11402,11429 9,"“metaphor has been exhausted in depicting the perfection of it, combined with the narrowness of her field;”",0,null,12180,12287 9,"metaphor has been exhausted in depicting the perfection of it, combined with the narrowness of her field;",1,null,12181,12286 10,“narrow”,0,null,12690,12698 10,narrow,1,null,12691,12697 11,“absolute.”,0,null,14394,14405 11,absolute.,1,null,14395,14404 12,“while Mrs. Bennet was stirring the fire”,0,null,15045,15086 12,while Mrs. Bennet was stirring the fire,1,null,15046,15085 13,"“brought his coffee-cup back_ himself,”",0,null,15163,15202 13,"brought his coffee-cup back_ himself,",1,null,15164,15201 14,“taller by the breadth of my nail”,0,null,15250,15284 14,taller by the breadth of my nail,1,null,15251,15283 15,"“metals, semi-metals, and distinguished philosophers.”",0,null,15957,16011 15,"metals, semi-metals, and distinguished philosophers.",1,null,15958,16010 16,"“miniature,”",0,null,16535,16547 16,"miniature,",1,null,16536,16546 17,“impropriety”,0,null,18053,18066 17,impropriety,1,null,18054,18065 18,"“My dear, do not give way to such gloomy thoughts. Let us hope for better things. Let us flatter ourselves that_ I _may be the survivor;”",0,null,18894,19031 18,"My dear, do not give way to such gloomy thoughts. Let us hope for better things. Let us flatter ourselves that_ I _may be the survivor;",1,null,18895,19030 19,"“May I ask whether these pleasing attentions proceed from the impulse of the moment, or are the result of previous study?”",0,null,19166,19288 19,"May I ask whether these pleasing attentions proceed from the impulse of the moment, or are the result of previous study?",1,null,19167,19287 20,“one of Mr. Philips’s clerks.”,0,null,20415,20445 20,one of Mr. Philips’s clerks.,1,null,20416,20444 21,"“scratches,”",0,null,24252,24264 21,"scratches,",1,null,24253,24263 22,“New Woman”,0,null,25850,25861 22,New Woman,1,null,25851,25860 23,“new”,0,null,25913,25918 23,new,1,null,25914,25917 24,"“impudent and mannish grown,”",0,null,26105,26134 24,"impudent and mannish grown,",1,null,26106,26133 25,“He came down to see the place”,0,null,28171,28202

c.)	“(.*?)”
Explanation
•	.*? → match as little as possible (non-greedy)
•	Prevents overmatching across multiple quotes
 Strengths
•	Handles multiple quotes in one line
•	More flexible
 Limitations
•	Can still break with nested dialogue
•	Depends on correct quote pairing

Matchen (Not all) : 
match_num,content,group_num,group_name,start_pos,end_pos 0,“loving with personal love.”,0,null,2657,2685 0,loving with personal love.,1,null,2658,2684 1,"“Mr. Spectator,”",0,null,9376,9392 1,"Mr. Spectator,",1,null,9377,9391 2,“he admires your_ Spectators _mightily”,0,null,10744,10783 2,he admires your_ Spectators _mightily,1,null,10745,10782 3,“cynicism”,0,null,10971,10981 3,cynicism,1,null,10972,10980 4,“cynical”,0,null,11104,11113 4,cynical,1,null,11105,11112 5,"“the other side,”",0,null,11370,11387 5,"the other side,",1,null,11371,11386 6,“narrow”,0,null,12690,12698 6,narrow,1,null,12691,12697 7,“absolute.”,0,null,14394,14405 7,absolute.,1,null,14395,14404 8,"“miniature,”",0,null,16535,16547 8,"miniature,",1,null,16536,16546 9,“impropriety”,0,null,18053,18066 9,impropriety,1,null,18054,18065 10,“one of Mr. Philips’s clerks.”,0,null,20415,20445 10,one of Mr. Philips’s clerks.,1,null,20416,20444 11,"“scratches,”",0,null,24252,24264 11,"scratches,",1,null,24253,24263 12,“New Woman”,0,null,25850,25861 12,New Woman,1,null,25851,25860 13,“new”,0,null,25913,25918 13,new,1,null,25914,25917 14,"“impudent and mannish grown,”",0,null,26105,26134 14,"impudent and mannish grown,",1,null,26106,26133 15,“He came down to see the place”,0,null,28171,28202 15,He came down to see the place,1,null,28172,28201 16,“I hope Mr. Bingley will like it”,0,null,28319,28352 16,I hope Mr. Bingley will like it,1,null,28320,28351 17,“I’m the tallest”,0,null,28393,28410 17,I’m the tallest,1,null,28394,28409 18,“He rode a black horse”,0,null,28467,28490 18,He rode a black horse,1,null,28468,28489 19,“When the party entered”,0,null,28541,28565 19,When the party entered,1,null,28542,28564 20,“She is tolerable”,0,null,28615,28633 20,She is tolerable,1,null,28616,28632 21,“Without once opening his lips”,0,null,28837,28868 21,Without once opening his lips,1,null,28838,28867 22,“The entreaties of several”,0,null,29059,29086 22,The entreaties of several,1,null,29060,29085 23,“A note for Miss Bennet”,0,null,29133,29157 23,A note for Miss Bennet,1,null,29134,29156 24,“Cheerful prognostics”,0,null,29207,29229 24,Cheerful prognostics,1,null,29208,29228 25,“The apothecary came”,0,null,29281,29302 25,The apothecary came,1,null,29282,29301 26,“Covering a screen”,0,null,29355,29374 26,Covering a screen,1,null,29356,29373 27,“Mrs. Bennet and her two youngest girls”,0,null,29429,29469 27,Mrs. Bennet and her two youngest girls,1,null,29430,29468 28,"“No, no; stay where you are”",0,null,29577,29605 28,"No, no; stay where you are",1,null,29578,29604 29,“Piling up the fire”,0,null,29651,29671 29,Piling up the fire,1,null,29652,29670 30,“Protested that he never read novels”,0,null,29947,29984 30,Protested that he never read novels,1,null,29948,29983 31,“The officers of the ----shire”,0,null,30169,30200 31,The officers of the ----shire,1,null,30170,30199 32,“Delighted to see their dear friend again”,0,null,30243,30285 32,Delighted to see their dear friend again,1,null,30244,30284 33,“Such very superior dancing is not often seen”,0,null,30391,30437 33,Such very superior dancing is not often seen,1,null,30392,30436 34,“To assure you in the most animated language”,0,null,30465,30510 34,To assure you in the most animated language,1,null,30466,30509 35,“They entered the breakfast-room”,0,null,30613,30646 35,They entered the breakfast-room,1,null,30614,30645 36,“Walked back with them”,0,null,30761,30784 36,Walked back with them,1,null,30762,30783 37,“So much love and eloquence”,0,null,30909,30937 37,So much love and eloquence,1,null,30910,30936 38,“Protested he must be entirely mistaken”,0,null,30983,31023 38,Protested he must be entirely mistaken,1,null,30984,31022 39,“Whenever she spoke in a low voice”,0,null,31057,31092 39,Whenever she spoke in a low voice,1,null,31058,31091 40,“Offended two or three young ladies”,0,null,31279,31315 40,Offended two or three young ladies,1,null,31280,31314 41,“Will you come and see me?”,0,null,31353,31380 41,Will you come and see me?,1,null,31354,31379 42,“On the stairs”,0,null,31427,31442 42,On the stairs,1,null,31428,31441 43,“At the door”,0,null,31501,31514 43,At the door,1,null,31502,31513 44,“In conversation with the ladies”,0,null,31575,31608 44,In conversation with the ladies,1,null,31576,31607 45,"“Lady Catherine,”",0,null,31649,31666 45,"Lady Catherine,",1,null,31650,31665 46,“you have given me a treasure”,0,null,31677,31707 46,you have given me a treasure,1,null,31678,31706 47,“He never failed to inform them”,0,null,31797,31829 47,He never failed to inform them,1,null,31798,31828 48,“The gentlemen accompanied him”,0,null,31871,31902 48,The gentlemen accompanied him,1,null,31872,31901 49,“Accompanied by their aunt”,0,null,32093,32120 49,Accompanied by their aunt,1,null,32094,32119 50,“On looking up”,0,null,32167,32182 50,On looking up,1,null,32168,32181 51,“Hearing herself called”,0,null,32315,32339 51,Hearing herself called,1,null,32316,32338 52,“Meeting accidentally in town”,0,null,32463,32493 52,Meeting accidentally in town,1,null,32464,32492 53,“His parting obeisance”,0,null,32537,32560 53,His parting obeisance,1,null,32538,32559 54,“Dawson”,0,null,32611,32619 54,Dawson,1,null,32612,32618 55,“The elevation of his feelings”,0,null,32685,32716 55,The elevation of his feelings,1,null,32686,32715 56,“They had forgotten to leave any message”,0,null,32759,32800 56,They had forgotten to leave any message,1,null,32760,32799 57,“How nicely we are crammed in!”,0,null,32833,32864 57,How nicely we are crammed in!,1,null,32834,32863 58,“I am determined never to speak of it again”,0,null,32981,33025 58,I am determined never to speak of it again,1,null,32982,33024 59,“When Colonel Miller’s regiment went away”,0,null,33055,33097 59,When Colonel Miller’s regiment went away,1,null,33056,33096 60,“Tenderly flirting”,0,null,33129,33148 60,Tenderly flirting,1,null,33130,33147 61,“Conjecturing as to the date”,0,null,33277,33306 61,Conjecturing as to the date,1,null,33278,33305 62,“To make herself agreeable to all”,0,null,33425,33459 62,To make herself agreeable to all,1,null,33426,33458 63,“Engaged by the river”,0,null,33499,33521 63,Engaged by the river,1,null,33500,33520 64,“I have not an instant to lose”,0,null,33647,33678 64,I have not an instant to lose,1,null,33648,33677 65,“The first pleasing earnest of their welcome”,0,null,33721,33766 65,The first pleasing earnest of their welcome,1,null,33722,33765 66,“To whom I have related the affair”,0,null,33869,33904 66,To whom I have related the affair,1,null,33870,33903 67,“But perhaps you would like to read it”,0,null,34017,34056 67,But perhaps you would like to read it,1,null,34018,34055 68,“The spiteful old ladies”,0,null,34091,34116 68,The spiteful old ladies,1,null,34092,34115 69,“With an affectionate smile”,0,null,34165,34193 69,With an affectionate smile,1,null,34166,34192 70,“I am sure she did not listen”,0,null,34239,34269 70,I am sure she did not listen,1,null,34240,34268 71,“Mr. Darcy with him”,0,null,34313,34333 71,Mr. Darcy with him,1,null,34314,34332 72,“Jane happened to look round”,0,null,34387,34416 72,Jane happened to look round,1,null,34388,34415 73,“Mrs. Long and her nieces”,0,null,34461,34487 73,Mrs. Long and her nieces,1,null,34462,34486 74,"“Lizzy, my dear, I want to speak to you”",0,null,34535,34575 74,"Lizzy, my dear, I want to speak to you",1,null,34536,34574 75,“After a short survey”,0,null,34683,34705 75,After a short survey,1,null,34684,34704 76,“But now it comes out”,0,null,34757,34779 76,But now it comes out,1,null,34758,34778 77,“The efforts of his aunt”,0,null,34831,34856 77,The efforts of his aunt,1,null,34832,34855 78,“Unable to utter a syllable”,0,null,34905,34933 78,Unable to utter a syllable,1,null,34906,34932 79,“The obsequious civility”,0,null,34979,35004 79,The obsequious civility,1,null,34980,35003 80,"“My dear Mr. Bennet,”",0,null,35639,35660 80,"My dear Mr. Bennet,",1,null,35640,35659 81,"“But it is,”",0,null,35784,35796 81,"But it is,",1,null,35785,35795 82,“Do not you want to know who has taken it?”,0,null,35906,35949 82,Do not you want to know who has taken it?,1,null,35907,35948 83,"“_You_ want to tell me, and I have no objection to hearing it.”",0,null,35980,36043 83,"_You_ want to tell me, and I have no objection to hearing it.",1,null,35981,36042 84,“He came down to see the place”,0,null,36061,36092 84,He came down to see the place,1,null,36062,36091 85,“What is his name?”,0,null,36560,36579 85,What is his name?,1,null,36561,36578 86,“Bingley.”,0,null,36581,36591 86,Bingley.,1,null,36582,36590 87,“Is he married or single?”,0,null,36593,36619 87,Is he married or single?,1,null,36594,36618 88,“How so? how can it affect them?”,0,null,36751,36784 88,How so? how can it affect them?,1,null,36752,36783 89,"“My dear Mr. Bennet,”",0,null,36786,36807 89,"My dear Mr. Bennet,",1,null,36787,36806 90,“Is that his design in settling here?”,0,null,36919,36957 90,Is that his design in settling here?,1,null,36920,36956 91,"“In such cases, a woman has not often much beauty to think of.”",0,null,37563,37626 91,"In such cases, a woman has not often much beauty to think of.",1,null,37564,37625 92,"“It is more than I engage for, I assure you.”",0,null,37722,37767 92,"It is more than I engage for, I assure you.",1,null,37723,37766 93,"“They have none of them much to recommend them,”",0,null,38555,38603 93,"They have none of them much to recommend them,",1,null,38556,38602 94,"“Ah, you do not know what I suffer.”",0,null,39038,39074

Documentation: 
Regular expressions were applied to extract dialogue enclosed in quotation marks. Three approaches were used: a simple pattern for curly quotes, an extended version supporting different quote types, and a non-greedy pattern to handle multiple quotations in one line. The results demonstrate that more flexible patterns improve coverage, but handling inconsistent or nested quotes remains challenging.


Task 3 : 
a.)	(?:Mr|Mrs|Miss|Lady)\.?\s+([A-Z][a-z]+)(?:\s+([A-Z][a-z]+))?
Explanation
•	(?:Mr|Mrs|Miss|Lady) → title (no capture group)
•	\.? → optional dot
•	\s+ → space
•	([A-Z][a-z]+) → first or last name (Group 1)
•	(?:\s+([A-Z][a-z]+))? → optional second name (Group 2)
 Last name logic:
•	If Group 2 exists → last name = Group 2
•	Otherwise → last name = Group 1
 Strengths
•	Works well for structured names
•	Uses capture groups correctly
 Limitations
•	Only works with titles
•	Misses names without titles

Matches (not all) : 
match_num,content,group_num,group_name,start_pos,end_pos 0,Mrs. Norris,0,null,4094,4105 0,Norris,1,null,4099,4105 1,Miss Austen,0,null,4471,4482 1,Austen,1,null,4476,4482 2,Miss Bates,0,null,4816,4826 2,Bates,1,null,4821,4826 3,Miss Austen,0,null,5338,5349 3,Austen,1,null,5343,5349 4,Mrs. Rushworth,0,null,6001,6015 4,Rushworth,1,null,6006,6015 5,Mr. Collins,0,null,6242,6253 5,Collins,1,null,6246,6253 6,Miss Austen,0,null,6662,6673 6,Austen,1,null,6667,6673 7,Miss Austen,0,null,8349,8360 7,Austen,1,null,8354,8360 8,Miss Austen,0,null,8513,8524 8,Austen,1,null,8518,8524 9,Mrs. Norris,0,null,8635,8646 9,Norris,1,null,8640,8646 10,Miss Austen,0,null,8801,8812 10,Austen,1,null,8806,8812 11,Mr. Spectator,0,null,9377,9390 11,Spectator,1,null,9381,9390 12,Miss Austen,0,null,9852,9863 12,Austen,1,null,9857,9863 13,Miss Burney,0,null,9986,9997 13,Burney,1,null,9991,9997 14,Mr. Addison,0,null,10047,10058 14,Addison,1,null,10051,10058 15,Miss Austen,0,null,10066,10077 15,Austen,1,null,10071,10077 16,Miss Austen,0,null,10327,10338 16,Austen,1,null,10332,10338 17,Mr. Shapely,0,null,10694,10705 17,Shapely,1,null,10698,10705 18,Miss Austen,0,null,10996,11007 18,Austen,1,null,11001,11007 19,Mrs. Musgrove,0,null,11037,11050 19,Musgrove,1,null,11042,11050 20,Miss Austen,0,null,11728,11739 20,Austen,1,null,11733,11739 21,Mr. Bennet,0,null,11826,11836 21,Bennet,1,null,11830,11836 22,Mr. Goldwin Smith,0,null,12138,12155 22,Goldwin,1,null,12142,12149 22,Smith,2,null,12150,12155 23,Miss Austen,0,null,13545,13556 23,Austen,1,null,13550,13556 24,Miss Austen,0,null,13994,14005 24,Austen,1,null,13999,14005 25,Miss Austen,0,null,14831,14842 25,Austen,1,null,14836,14842 26,Mr. Collins,0,null,14993,15004 26,Collins,1,null,14997,15004 27,Mrs. Bennet,0,null,15052,15063 27,Bennet,1,null,15057,15063 28,Mrs. Bennet,0,null,15106,15117 28,Bennet,1,null,15111,15117 29,Mr. Darcy,0,null,15153,15162 29,Darcy,1,null,15157,15162 30,Miss Austen,0,null,15414,15425 30,Austen,1,null,15419,15425 31,Mr. Collins,0,null,15626,15637 31,Collins,1,null,15630,15637 32,Mr. Collins,0,null,15639,15650 32,Collins,1,null,15643,15650 33,Mr. Collins,0,null,16081,16092 33,Collins,1,null,16085,16092 34,Mr. Collins,0,null,16459,16470 34,Collins,1,null,16463,16470 35,Mr. Collins,0,null,17082,17093 35,Collins,1,null,17086,17093 36,Mr. Bennet,0,null,17210,17220 36,Bennet,1,null,17214,17220 37,Lady Catherine,0,null,17228,17242 37,Catherine,1,null,17233,17242 38,Mr. Collins,0,null,17271,17282 38,Collins,1,null,17275,17282 39,Lady Catherine,0,null,17625,17639 39,Catherine,1,null,17630,17639 40,Lady Powerful,0,null,17686,17699 40,Powerful,1,null,17691,17699 41,Mr. Bennet,0,null,17923,17933 41,Bennet,1,null,17927,17933 42,Miss Austen,0,null,17935,17946 42,Austen,1,null,17940,17946 43,Mr. Darcy,0,null,17952,17961 43,Darcy,1,null,17956,17961 44,Miss Elizabeth,0,null,17972,17986 44,Elizabeth,1,null,17977,17986 45,Miss Austen,0,null,18551,18562 45,Austen,1,null,18556,18562 46,Mr. Collins,0,null,18707,18718 46,Collins,1,null,18711,18718 47,Mr. Collins,0,null,19099,19110 47,Collins,1,null,19103,19110 48,Lady Catherine,0,null,19150,19164 48,Catherine,1,null,19155,19164 49,Miss Austen,0,null,19321,19332 49,Austen,1,null,19326,19332 50,Mrs. Bennet,0,null,19762,19773 50,Bennet,1,null,19767,19773 51,Miss Austen,0,null,20171,20182 51,Austen,1,null,20176,20182 52,Mr. Austen Leigh,0,null,20350,20366 52,Austen,1,null,20354,20360 52,Leigh,2,null,20361,20366 53,Mr. Philips,0,null,20423,20434 53,Philips,1,null,20427,20434 54,Mr. Collins,0,null,20872,20883 54,Collins,1,null,20876,20883 55,Miss Austen,0,null,20991,21002 55,Austen,1,null,20996,21002 56,Mrs. Bennet,0,null,21088,21099 56,Bennet,1,null,21093,21099 57,Miss Darcy,0,null,21178,21188 57,Darcy,1,null,21183,21188 58,Miss Austen,0,null,21522,21533 58,Austen,1,null,21527,21533 59,Miss Austen,0,null,21967,21978 59,Austen,1,null,21972,21978 60,Miss Austen,0,null,23414,23425 60,Austen,1,null,23419,23425 61,Miss Austen,0,null,23620,23631 61,Austen,1,null,23625,23631 62,Lady Catherine,0,null,24615,24629 62,Catherine,1,null,24620,24629 63,Miss Austen,0,null,26250,26261 63,Austen,1,null,26255,26261 64,Mrs. Bennet,0,null,28253,28264 64,Bennet,1,null,28258,28264 65,Mr. Bingley,0,null,28327,28338 65,Bingley,1,null,28331,28338 66,Miss Bennet,0,null,29145,29156 66,Bennet,1,null,29150,29156 67,Mrs. Bennet,0,null,29430,29441 67,Bennet,1,null,29435,29441 68,Lady Catherine,0,null,31650,31664 68,Catherine,1,null,31655,31664 69,Mr. Darcy,0,null,34314,34323 69,Darcy,1,null,34318,34323 70,Mrs. Long,0,null,34462,34471 70,Long,1,null,34467,34471 71,Mr. Bennet,0,null,35648,35658 71,Bennet,1,null,35652,35658 72,Mr. Bennet,0,null,35747,35757 72,Bennet,1,null,35751,35757 73,Mrs. Long,0,null,35816,35825 73,Long,1,null,35821,35825 74,Mr. Bennet,0,null,35878,35888 74,Bennet,1,null,35882,35888 75,Mrs. Long,0,null,36191,36200 75,Long,1,null,36196,36200 76,Mr. Morris,0,null,36412,36422 76,Morris,1,null,36416,36422 77,Mr. Bennet,0,null,36795,36805 77,Bennet,1,null,36799,36805 78,Mr. Bingley,0,null,37292,37303 78,Bingley,1,null,37296,37303 79,Mr. Bingley,0,null,37670,37681 79,Bingley,1,null,37674,37681 80,Lady Lucas,0,null,37877,37887 80,Lucas,1,null,37882,37887 81,Mr. Bingley,0,null,38117,38128 81,Bingley,1,null,38121,38128 82,Mr. Bennet,0,null,38730,38740 82,Bennet,1,null,38734,38740 83,Mr. Bennet,0,null,39362,39372 83,Bennet,1,null,39366,39372 84,Mr. Bingley,0,null,39940,39951 84,Bingley,1,null,39944,39951 85,Mr. Bennet,0,null,40038,40048 85,Bennet,1,null,40042,40048 86,Mr. Bingley,0,null,40095,40106 86,Bingley,1,null,40099,40106 87,Mr. Bingley,0,null,40434,40445 87,Bingley,1,null,40438,40445 88,Mr. Bingley,0,null,40505,40516 88,Bingley,1,null,40509,40516 89,Mrs. Long,0,null,40678,40687 89,Long,1,null,40683,40687 90,Mrs. Long,0,null,40739,40748 90,Long,1,null,40744,40748 91,Mr. Bennet,0,null,40897,40907 91,Bennet,1,null,40901,40907 92,Mrs. Bennet,0,null,40977,40988 92,Bennet,1,null,40982,40988 93,Mrs. Long,0,null,41456,41465 93,Long,1,null,41461,41465 94,Mr. Bingley,0,null,41668,41679 94,Bingley,1,null,41672,41679 95,Mr. Bennet,0,null,41705,41715 95,Bennet,1,null,41709,41715 96,Mrs. Long,0,null,42011,42020 96,Long,1,null,42016,42020 97,Mrs. Bennet,0,null,42207,42218 97,Bennet,1,null,42212,42218 98,Mr. Bingley,0,null,42700,42711 98,Bingley,1,null,42704,42711 99,Mr. Bingley,0,null,42729,42740 99,Bingley,1,null,42733,42740 100,Mrs. Bennet,0,null,43070,43081 100,Bennet,1,null,43075,43081 101,Mr. Bennet,0,null,43261,43271 101,Bennet,1,null,43265,43271 102,Mr. Bennet,0,null,43585,43595 102,Bennet,1,null,43589,43595 103,Mr. Bingley,0,null,44051,44062 103,Bingley,1,null,44055,44062 104,Mr. Bennet,0,null,44274,44284 104,Bennet,1,null,44278,44284 105,Mrs. Bennet,0,null,44480,44491 105,Bennet,1,null,44485,44491 106,Mr. Bingley,0,null,44643,44654 106,Bingley,1,null,44647,44654 107,Lady Lucas,0,null,44889,44899 107,Lucas,1,null,44894,44899 108,Mr. Bingley,0,null,45245,45256 108,Bingley,1,null,45249,45256 109,Mrs. Bennet,0,null,45360,45371 109,Bennet,1,null,45365,45371 110,Mr. Bingley,0,null,45480,45491 110,Bingley,1,null,45484,45491 111,Mr. Bennet,0,null,45501,45511 111,Bennet,1,null,45505,45511 112,Mrs. Bennet,0,null,45939,45950 112,Bennet,1,null,45944,45950 113,Mr. Bingley,0,null,46061,46072 113,Bingley,1,null,46065,46072 114,Mrs. Bennet,0,null,46189,46200 114,Bennet,1,null,46194,46200 115,Lady Lucas,0,null,46465,46475 115,Lucas,1,null,46470,46475

b.)	([A-Z][a-z]+)\s+([A-Z][a-z]+)
Explanation
•	Matches two capitalized words
•	Group 1 = first name
•	Group 2 = last name
Strengths
•	Simple and general
•	Captures many names
Limitations
•	Also matches non-names (e.g., “Long Road”)
•	No titles

Matches (not all): 
match_num,content,group_num,group_name,start_pos,end_pos 0,The Project,0,null,0,11 0,The,1,null,0,3 0,Project,2,null,4,11 1,Prejudice This,0,null,41,60 1,Prejudice,1,null,41,50 1,This,2,null,56,60 2,United States,0,null,108,121 2,United,1,null,108,114 2,States,2,null,115,121 3,Project Gutenberg,0,null,277,294 3,Project,1,null,277,284 3,Gutenberg,2,null,285,294 4,United States,0,null,390,403 4,United,1,null,390,396 4,States,2,null,397,403 5,Prejudice Author,0,null,517,534 5,Prejudice,1,null,517,526 5,Author,2,null,528,534 6,Jane Austen,0,null,536,547 6,Jane,1,null,536,540 6,Austen,2,null,541,547 7,English Other,0,null,668,682 7,English,1,null,668,675 7,Other,2,null,677,682 8,Chuck Greif,0,null,748,759 8,Chuck,1,null,748,753 8,Greif,2,null,754,759 9,Online Distributed,0,null,768,786 9,Online,1,null,768,774 9,Distributed,2,null,775,786 10,Proofreading Team,0,null,787,804 10,Proofreading,1,null,787,799 10,Team,2,null,800,804 11,The Internet,0,null,877,889 11,The,1,null,877,880 11,Internet,2,null,881,889 12,Reading Jane,0,null,1325,1337 12,Reading,1,null,1325,1332 12,Jane,2,null,1333,1337 13,Jane Austen,0,null,1592,1603 13,Jane,1,null,1592,1596 13,Austen,2,null,1597,1603 14,George Saintsbury,0,null,1678,1695 14,George,1,null,1678,1684 14,Saintsbury,2,null,1685,1695 15,Hugh Thomson,0,null,1807,1819 15,Hugh,1,null,1807,1811 15,Thomson,2,null,1812,1819 16,Charing House,0,null,1909,1945 16,Charing,1,null,1909,1916 16,House,2,null,1940,1945 17,Cross Road,0,null,1954,1964 17,Cross,1,null,1954,1959 17,Road,2,null,1960,1964 18,London George,0,null,1999,2041 18,London,1,null,1999,2005 18,George,2,null,2035,2041 19,Comyns Carr,0,null,2246,2257 19,Comyns,1,null,2246,2252 19,Carr,2,null,2253,2257 20,Hugh Thomson,0,null,2485,2497 20,Hugh,1,null,2485,2489 20,Thomson,2,null,2490,2497 21,Walt Whitman,0,null,2568,2580 21,Walt,1,null,2568,2572 21,Whitman,2,null,2573,2580 22,Northanger Abbey,0,null,3314,3330 22,Northanger,1,null,3314,3324 22,Abbey,2,null,3325,3330 23,Mansfield Park,0,null,3724,3738 23,Mansfield,1,null,3724,3733 23,Park,2,null,3734,3738 24,Miss Austen,0,null,4471,4482 24,Miss,1,null,4471,4475 24,Austen,2,null,4476,4482 25,Miss Bates,0,null,4816,4826 25,Miss,1,null,4816,4820 25,Bates,2,null,4821,4826 26,Miss Austen,0,null,5338,5349 26,Miss,1,null,5338,5342 26,Austen,2,null,5343,5349 27,Frank Churchill,0,null,6456,6471 27,Frank,1,null,6456,6461 27,Churchill,2,null,6462,6471 28,Jane Fairfax,0,null,6476,6488 28,Jane,1,null,6476,6480 28,Fairfax,2,null,6481,6488 29,Although Miss,0,null,6653,6666 29,Although,1,null,6653,6661 29,Miss,2,null,6662,6666 30,Miss Austen,0,null,8349,8360 30,Miss,1,null,8349,8353 30,Austen,2,null,8354,8360 31,Miss Austen,0,null,8513,8524 31,Miss,1,null,8513,8517 31,Austen,2,null,8518,8524 32,John Thorpe,0,null,8610,8621 32,John,1,null,8610,8614 32,Thorpe,2,null,8615,8621 33,Miss Austen,0,null,8801,8812 33,Miss,1,null,8801,8805 33,Austen,2,null,8806,8812 34,Jane Austen,0,null,9400,9411 34,Jane,1,null,9400,9404 34,Austen,2,null,9405,9411 35,Miss Austen,0,null,9852,9863 35,Miss,1,null,9852,9856 35,Austen,2,null,9857,9863 36,Miss Burney,0,null,9986,9997 36,Miss,1,null,9986,9990 36,Burney,2,null,9991,9997 37,Miss Austen,0,null,10066,10077 37,Miss,1,null,10066,10070 37,Austen,2,null,10071,10077 38,Miss Austen,0,null,10327,10338 38,Miss,1,null,10327,10331 38,Austen,2,null,10332,10338 39,Lydia Bennet,0,null,10851,10863 39,Lydia,1,null,10851,10856 39,Bennet,2,null,10857,10863 40,Miss Austen,0,null,10996,11007 40,Miss,1,null,10996,11000 40,Austen,2,null,11001,11007 41,Miss Austen,0,null,11728,11739 41,Miss,1,null,11728,11732 41,Austen,2,null,11733,11739 42,Goldwin Smith,0,null,12142,12155 42,Goldwin,1,null,12142,12149 42,Smith,2,null,12150,12155 43,Even Scott,0,null,13413,13423 43,Even,1,null,13413,13417 43,Scott,2,null,13418,13423 44,Miss Austen,0,null,13545,13556 44,Miss,1,null,13545,13549 44,Austen,2,null,13550,13556 45,Mary Wollstonecraft,0,null,13903,13922 45,Mary,1,null,13903,13907 45,Wollstonecraft,2,null,13908,13922 46,Miss Austen,0,null,13994,14005 46,Miss,1,null,13994,13998 46,Austen,2,null,13999,14005 47,Miss Austen,0,null,14831,14842 47,Miss,1,null,14831,14835 47,Austen,2,null,14836,14842 48,Miss Austen,0,null,15414,15425 48,Miss,1,null,15414,15418 48,Austen,2,null,15419,15425 49,This Swiftian,0,null,15500,15513 49,This,1,null,15500,15504 49,Swiftian,2,null,15505,15513 50,John Dashwood,0,null,16304,16317 50,John,1,null,16304,16308 50,Dashwood,2,null,16309,16317 51,Lady Catherine,0,null,17228,17242 51,Lady,1,null,17228,17232 51,Catherine,2,null,17233,17242 52,Lady Catherine,0,null,17625,17639 52,Lady,1,null,17625,17629 52,Catherine,2,null,17630,17639 53,Lady Powerful,0,null,17686,17699 53,Lady,1,null,17686,17690 53,Powerful,2,null,17691,17699 54,Miss Austen,0,null,17935,17946 54,Miss,1,null,17935,17939 54,Austen,2,null,17940,17946 55,Miss Elizabeth,0,null,17972,17986 55,Miss,1,null,17972,17976 55,Elizabeth,2,null,17977,17986 56,Miss Austen,0,null,18551,18562 56,Miss,1,null,18551,18555 56,Austen,2,null,18556,18562 57,Lady Catherine,0,null,19150,19164 57,Lady,1,null,19150,19154 57,Catherine,2,null,19155,19164 58,Miss Austen,0,null,19321,19332 58,Miss,1,null,19321,19325 58,Austen,2,null,19326,19332 59,With Mary,0,null,20160,20169 59,With,1,null,20160,20164 59,Mary,2,null,20165,20169 60,Miss Austen,0,null,20171,20182 60,Miss,1,null,20171,20175 60,Austen,2,null,20176,20182 61,Austen Leigh,0,null,20354,20366 61,Austen,1,null,20354,20360 61,Leigh,2,null,20361,20366 62,Miss Austen,0,null,20991,21002 62,Miss,1,null,20991,20995 62,Austen,2,null,20996,21002 63,The Bingleys,0,null,21130,21142 63,The,1,null,21130,21133 63,Bingleys,2,null,21134,21142 64,Miss Darcy,0,null,21178,21188 64,Miss,1,null,21178,21182 64,Darcy,2,null,21183,21188 65,Charlotte Lucas,0,null,21302,21317 65,Charlotte,1,null,21302,21311 65,Lucas,2,null,21312,21317 66,Miss Austen,0,null,21522,21533 66,Miss,1,null,21522,21526 66,Austen,2,null,21527,21533 67,Don Juanish,0,null,21780,21791 67,Don,1,null,21780,21783 67,Juanish,2,null,21784,21791 68,Miss Austen,0,null,21967,21978 68,Miss,1,null,21967,21971 68,Austen,2,null,21972,21978 69,Henry Tilney,0,null,22024,22036 69,Henry,1,null,22024,22029 69,Tilney,2,null,22030,22036 70,Miss Austen,0,null,23414,23425 70,Miss,1,null,23414,23418 70,Austen,2,null,23419,23425

c.)	([A-Z][a-z]+)(?:\s+([A-Z][a-z]+))(?:\s+([A-Z][a-z]+))?
 Explanation
•	Matches 2 or 3 capitalized words
•	Group 3 (if exists) → last name
•	Otherwise → Group 2
 Strengths
•	More flexible
•	Captures full names like “Elizabeth Bennet”
Limitations
•	More false positives
•	Still heuristic-based
Matches (not all):  
match_num,content,group_num,group_name,start_pos,end_pos 0,The Project Gutenberg,0,null,0,21 0,The,1,null,0,3 0,Project,2,null,4,11 0,Gutenberg,3,null,12,21 1,Prejudice This,0,null,41,60 1,Prejudice,1,null,41,50 1,This,2,null,56,60 2,United States,0,null,108,121 2,United,1,null,108,114 2,States,2,null,115,121 3,Project Gutenberg License,0,null,277,302 3,Project,1,null,277,284 3,Gutenberg,2,null,285,294 3,License,3,null,295,302 4,United States,0,null,390,403 4,United,1,null,390,396 4,States,2,null,397,403 5,Prejudice Author,0,null,517,534 5,Prejudice,1,null,517,526 5,Author,2,null,528,534 6,Jane Austen Release,0,null,536,566 6,Jane,1,null,536,540 6,Austen,2,null,541,547 6,Release,3,null,559,566 7,English Other,0,null,668,682 7,English,1,null,668,675 7,Other,2,null,677,682 8,Chuck Greif,0,null,748,759 8,Chuck,1,null,748,753 8,Greif,2,null,754,759 9,Online Distributed Proofreading,0,null,768,799 9,Online,1,null,768,774 9,Distributed,2,null,775,786 9,Proofreading,3,null,787,799 10,The Internet Archive,0,null,877,897 10,The,1,null,877,880 10,Internet,2,null,881,889 10,Archive,3,null,890,897 11,Reading Jane,0,null,1325,1337 11,Reading,1,null,1325,1332 11,Jane,2,null,1333,1337 12,Jane Austen,0,null,1592,1603 12,Jane,1,null,1592,1596 12,Austen,2,null,1597,1603 13,George Saintsbury,0,null,1678,1695 13,George,1,null,1678,1684 13,Saintsbury,2,null,1685,1695 14,Hugh Thomson,0,null,1807,1819 14,Hugh,1,null,1807,1811 14,Thomson,2,null,1812,1819 15,Charing House,0,null,1909,1945 15,Charing,1,null,1909,1916 15,House,2,null,1940,1945 16,Cross Road,0,null,1954,1964 16,Cross,1,null,1954,1959 16,Road,2,null,1960,1964 17,London George Allen,0,null,1999,2047 17,London,1,null,1999,2005 17,George,2,null,2035,2041 17,Allen,3,null,2042,2047 18,Comyns Carr,0,null,2246,2257 18,Comyns,1,null,2246,2252 18,Carr,2,null,2253,2257 19,Hugh Thomson,0,null,2485,2497 19,Hugh,1,null,2485,2489 19,Thomson,2,null,2490,2497 20,Walt Whitman,0,null,2568,2580 20,Walt,1,null,2568,2572 20,Whitman,2,null,2573,2580 21,Northanger Abbey,0,null,3314,3330 21,Northanger,1,null,3314,3324 21,Abbey,2,null,3325,3330 22,Mansfield Park,0,null,3724,3738 22,Mansfield,1,null,3724,3733 22,Park,2,null,3734,3738 23,Miss Austen,0,null,4471,4482 23,Miss,1,null,4471,4475 23,Austen,2,null,4476,4482 24,Miss Bates,0,null,4816,4826 24,Miss,1,null,4816,4820 24,Bates,2,null,4821,4826 25,Miss Austen,0,null,5338,5349 25,Miss,1,null,5338,5342 25,Austen,2,null,5343,5349 26,Frank Churchill,0,null,6456,6471 26,Frank,1,null,6456,6461 26,Churchill,2,null,6462,6471 27,Jane Fairfax,0,null,6476,6488 27,Jane,1,null,6476,6480 27,Fairfax,2,null,6481,6488 28,Although Miss Austen,0,null,6653,6673 28,Although,1,null,6653,6661 28,Miss,2,null,6662,6666 28,Austen,3,null,6667,6673 29,Miss Austen,0,null,8349,8360 29,Miss,1,null,8349,8353 29,Austen,2,null,8354,8360 30,Miss Austen,0,null,8513,8524 30,Miss,1,null,8513,8517 30,Austen,2,null,8518,8524 31,John Thorpe,0,null,8610,8621 31,John,1,null,8610,8614 31,Thorpe,2,null,8615,8621 32,Miss Austen,0,null,8801,8812 32,Miss,1,null,8801,8805 32,Austen,2,null,8806,8812 33,Jane Austen,0,null,9400,9411 33,Jane,1,null,9400,9404 33,Austen,2,null,9405,9411 34,Miss Austen,0,null,9852,9863 34,Miss,1,null,9852,9856 34,Austen,2,null,9857,9863 35,Miss Burney,0,null,9986,9997 35,Miss,1,null,9986,9990 35,Burney,2,null,9991,9997 36,Miss Austen,0,null,10066,10077 36,Miss,1,null,10066,10070 36,Austen,2,null,10071,10077 37,Miss Austen,0,null,10327,10338 37,Miss,1,null,10327,10331 37,Austen,2,null,10332,10338 38,Lydia Bennet,0,null,10851,10863 38,Lydia,1,null,10851,10856 38,Bennet,2,null,10857,10863 39,Miss Austen,0,null,10996,11007 39,Miss,1,null,10996,11000 39,Austen,2,null,11001,11007 40,Miss Austen,0,null,11728,11739 40,Miss,1,null,11728,11732 40,Austen,2,null,11733,11739 41,Goldwin Smith,0,null,12142,12155 41,Goldwin,1,null,12142,12149 41,Smith,2,null,12150,12155 42,Even Scott,0,null,13413,13423 42,Even,1,null,13413,13417 42,Scott,2,null,13418,13423 43,Miss Austen,0,null,13545,13556 43,Miss,1,null,13545,13549 43,Austen,2,null,13550,13556 44,Mary Wollstonecraft,0,null,13903,13922 44,Mary,1,null,13903,13907 44,Wollstonecraft,2,null,13908,13922 45,Miss Austen,0,null,13994,14005 45,Miss,1,null,13994,13998 45,Austen,2,null,13999,14005 46,Miss Austen,0,null,14831,14842 46,Miss,1,null,14831,14835 46,Austen,2,null,14836,14842 47,Miss Austen,0,null,15414,15425 47,Miss,1,null,15414,15418 47,Austen,2,null,15419,15425 48,This Swiftian,0,null,15500,15513 48,This,1,null,15500,15504 48,Swiftian,2,null,15505,15513 49,John Dashwood,0,null,16304,16317 49,John,1,null,16304,16308 49,Dashwood,2,null,16309,16317 50,Lady Catherine,0,null,17228,17242 50,Lady,1,null,17228,17232 50,Catherine,2,null,17233,17242 51,Lady Catherine,0,null,17625,17639 51,Lady,1,null,17625,17629 51,Catherine,2,null,17630,17639 52,Lady Powerful,0,null,17686,17699 52,Lady,1,null,17686,17690 52,Powerful,2,null,17691,17699 53,Miss Austen,0,null,17935,17946 53,Miss,1,null,17935,17939 53,Austen,2,null,17940,17946 54,Miss Elizabeth,0,null,17972,17986 54,Miss,1,null,17972,17976 54,Elizabeth,2,null,17977,17986 55,Miss Austen,0,null,18551,18562 55,Miss,1,null,18551,18555 55,Austen,2,null,18556,18562 56,Lady Catherine,0,null,19150,19164 56,Lady,1,null,19150,19154 56,Catherine,2,null,19155,19164 57,Miss Austen,0,null,19321,19332 57,Miss,1,null,19321,19325 57,Austen,2,null,19326,19332 58,With Mary,0,null,20160,20169 58,With,1,null,20160,20164 58,Mary,2,null,20165,20169 59,Miss Austen,0,null,20171,20182 59,Miss,1,null,20171,20175 59,Austen,2,null,20176,20182 60,Austen Leigh,0,null,20354,20366 60,Austen,1,null,20354,20360 60,Leigh,2,null,20361,20366 61,Miss Austen,0,null,20991,21002 61,Miss,1,null,20991,20995 61,Austen,2,null,20996,21002 62,The Bingleys,0,null,21130,21142 62,The,1,null,21130,21133

Documentation: 
Three regular expressions were implemented to extract person names using capitalization patterns. The first approach focuses on names with titles and uses capture groups to identify the last name. The second approach detects sequences of capitalized words, while the third extends this to allow up to three words.
The results show that using titles provides more precise matches, while general capitalization patterns increase coverage but also introduce false positives. Capture groups were essential for extracting specific parts of the matched names, particularly the last name.

Note
AI tools were used to support spelling and grammar corrections. The content, implementation, and analysis were developed independently.

