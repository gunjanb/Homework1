Expression1:
5 > 4 && false
true && false
false

Expression2:
true && 5 * 2 > 3 + 3 * 2
true && 10 > 3 + 6
true && 10 > 9
true && true 
true

Expression3:
true && 5 * 2 > (3 + 3) * 2
true && 5 * 2 > 6 * 2
true && 10 > 12
true && false
false

Expression4:
true && true || false
true || false
true

Expression5:
true && (true || false)
true && (true)
true

Expression6:
false && false || true
false || true
true

Expression7:
false && (false || true)
fasle && true
fasle

Expression8:
(false && false) && false && (true || false) || false
false && fasle && true || false
false && true || false
false || false
false

Expression9:
4 == "4"
true

Expression10:
4 == "4" || 4 == 4
true || true
true

Expression11:
10 % 3 == 10.0 % 3
1 == 1
true

Expression12:
10 * (5 / 2.0) == 10.0 * (5 / 2)
10 * 2.5 == 10.0 *  2.5
25 == 25
true

Expression13:
10 * 5 / 2 > 10 * (5 / 2)
10 * 5 / 2 > 10 * 2.5
50 / 2  > 25
25 > 25
false 

Expression14:
2 * 2 ** 3 == (2 * 2) ** 3
2 * 2 ** 3 == 4 ** 3
2 * 8 == 64
16 == 64
false

Expression15:
(10 - 4) < +6 || -(2 * -4) > 0
6 < +6 || -(-8) > 0
6 < 6 || 8 > 0
false || true
true