Object types /Data Types


- Number : 1234 , 3.1415 , 3+4j , 0b111 , Decimal(),Fraction()

- String : 'spam' , "Bob's" , b'a\x01c , u'sp\xc4m'

- List : [1,[2,'three'],4.5] , list(range(10))

- Tuple : (1,'spam' ,  4, 'U') tuple('spam') , namedtuple

- Dictionary : {'food': 'spam' , 'taste':'yum'} , dict(hours=10)

- Set : set('abc') , {'a','b','c'}

- File : open('eggs.txt') , open(r'C:\ham.bin','wb')

- Boolean : True , False

- None : None

- Functions , modules , classes

- Advance : Decorators , Generatorss , Iterators , MetaProgramming

- String is immutable


>>> import sys
>>> sys.getrefcount(24601)
3
>>> sys.getrefcount('Siddhes')
3
>>> sys.getrefcount('Rama')
3
>>> a = 3
>>> a = 'chaiaurcode'
>>> print(a)
chaiaurcode
>>> a = 3.14
>>> a = 5
>>> b = 2
>>> a 
5
>>> b
2
>>> a = a + 3
>>> a
8
>>> myListOne = [1 , 2 , 3]
>>> myListTwo = myListOne 
>>> myListTwo
[1, 2, 3]
>>> myListOne[0] = 33
>>> myListOne
[33, 2, 3]
>>> myListTwo
[33, 2, 3]
>>> myListOne[0] = 90
>>> myListOne
[90, 2, 3]
>>> myListTwo
[90, 2, 3]
>>> h1 = [1 , 2 , 3] 
>>> h2 = h1[:]  
>>> h1 
[1, 2, 3]
>>> h2
[1, 2, 3]
>>> h1[0] = 2
>>> h1
[2, 2, 3]
>>> h2
[1, 2, 3]
>>> import copy
>>> h2 = copy.copy(h1)
>>> h2 = copy.deepcopy(h1)

>>> 
>>> n = [1, 2, 3]
>>> m = n
>>> m
[1, 2, 3]
>>> n
[1, 2, 3]
>>> m == n 
True
>>> m is n (checking memory reference)
True
>>> 
>>> m = n
>>> m
[1, 2, 3]
>>> n
[1, 2, 3]
>>> m == n
True
>>> m is n
True
>>>
>>> 
>>> n = [1 , 2 , 3]
>>> m is n
False
>>> m == n
True
>>> 