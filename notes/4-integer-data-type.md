Fundamental Data Types - Integer
================================

Size of Integers
----------------

* integers can take 2 bytes or 4 bytes of memory
* 2 bytes = 16 bits = (2^16 = 65,536)
* 4 bytes = 32 bits = (2^32 = 4,294,967,296)

---

* you can see the size of any data type:

```c
printf("%zu", sizeof(int));
```

---

Decimal Number System
---------------------

* Human understandable number system.
* also called base 10 number system.
* range: 0 to 9

|  10^2 (100) | 10^1 (10) | 10^0 (1) |
| :---: | :---: | :---: |
| 5 | 6 | 8 |

$10^2 \times 5 + 10^1 \times 6 + 10^0 \times 8 = 500 + 60 + 8 = 568 $

---

Binary number system
--------------------

* Machine understandable number system.
* also called base 2 number system.
* range: 0 to 1

|  2^3 (8) | 2^2 (4) | 2^1 (2) | 2^0 (1) |
| :---: | :---: | :---: | :---: |
| 1 | 1 | 0 | 0 |

 $2^3 \times 1 + 2^2 \times 1 + 2^1 \times 1 + 2^0 \times 1 = 8 + 4 + 0 + 0 = 12 $
