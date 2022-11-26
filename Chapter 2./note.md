# Chapter 2

## Data Type
| Type | changeable | Example |
|------|------------|---------|
| bool | no | True, False |
| int | no | 213, 0, 25_000 |
| float | no | 3.14, 2.7e5 |
| complex | no | 3j, 5 + 9j |
| str | no | 'I am Lichyo' |
| list | YES | ['Lichyo', 'Chyo'] |
| tuple | no | (2, 4, 8) |
| bytes | no | b'ab\xff' |
| bytearray | YES | bytearray(...) |
| set | YES | set([3, 5, 7]) |
| frozenset | no | frozenset(['Lichyo', 'Chyo'])
| dict | YES | {'game' : 'bingo', 'dog' : 'dingo'} |

## Key word
如果要顯示保留字
    help("keywords")

    or
     
    import keyword
    keyword.kwlist

**以下為保留字**
- False
- await
- else
- import
- pass
- None
- break
- except
- in
- raise
- True
- class 
- finally
- is
- return 
- and
- continue
- for
- lambda
- try
- as
- def
- from
- nonlocal
- while
- assert
- del
- global
- not
- with
- async
- elif
- if
- or
- yield

## 整數運算
** / -> 浮點數除法 **
** // -> 整數除法 **
== ** -> 次方 ==
== divmod(9,5) -> (1,4)==
