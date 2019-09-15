# QuneiForm

  Imagine how do you , a Sumerian , buy things in B.C. 3200 . Now you have currency: 
[I] (1 buck), [V] (5 bucks), [X] (10 bucks), [L] (50 bucks), [C] (100 bucks)
and then you wanna buy some “magic” vegetables of FIRST bag within 1050(50*21), so you talk to dealer in store of market , so you “write” shopping list on mud block like:

    [X] [V] => 
	
(I PAY 15 BUCKS FOR THIS )

but actually this only cost you 13 BUCKS, for example, so you “write” again :

	[I] [I] <=
	

(2 BUCKS IN CHANGE)

  Now you can feel you are a REAL SUMERIAN!! OK, now we can use cuneiform as a programming language to do something. There must be a space in WORDS, don’t forget!!
  ## Syntax 
  ## Input
```bash  
	1.	dm / quu= / Tl= / =lT : point upper / lower / last / next zipper bag.
	2.	[I] / [V] / [X] / [L] / [C] + <= / => : change / pay bucks.
	3.	E^= / Ev= : list this bag as first / second bag.
	4.	=/C + [an integral number] : this bag in debt for [number] bucks.
	5.	O\= + [an integral number] : go to bags [number]. 
	6.	-<EEH + [integral number 1] + >-| / c[] + [integral number 2] : with rate [number 1] , count simple/complex interest in [number 2] periods.
	7.	[$] + [a single word] : print [word] on this bag (if word has 2 bytes than it costs two bags).
	8.	=D + [an float number] : [number] grams of shroom (means [1] real part of complex number [2] x component of )
	2D coordinate )
	9.	>|< + [an float number] : [number] grams of weed (means [1] imaginary part of complex number [2] y component of )
	2D coordinate )
	10.	=b / =p : drug is natural or not, which means the following calculation will be in complex variant or 2D coordinate.
	11.	=O= / mXm / =\/=  : drug in bag 1 add / multiply / devided by drug in bag 2.
	12.	F= : adulterate drugs , which means count [1] norm and main argument ; [2] length from origin and containing angle with X-axis.
	13.	' + [integral number 1] + ' + [integral number 2] / " + [integral number 1] + " + [integral number 2] : make weight of bag 1 and bag 2 the same / exchange.
```

  ## Statement
```bash  

	1.	=K / =mL / _lm= : is bag 1 as same as / heavier than/ lighter than bag 2?
	2.	T + … + _|_ : if … is true, then go back to pin “T”(IF).
	2.1	=GP : cost 1 time of -<EEH in Point 6 and used in Point 6. of Input
```

  ## IO stream
```bash  

	1.	=lE# : read "SHOPPINGLIST.htm" (if it exist in same folder)
	2.	lmL= : output as "CHECKLIST.htm" (it will be produced by program automatically)
	3.	>=>O +  [an integral number] : territory will be 1050 * [number] 
	4.	=nln : clean this bag
	5.	=m/ : clean all bags
	6.	&&& : copy all words in "SHOPPINGLIST.htm" with length of [territory] right now
	7.	{ + [string] + } : dealer talks somthing
	8.	M= : 
	
```
