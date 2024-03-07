# Eloqunet Javascript Reflections

## Terms

*Automatic Type Conversion*

'console.log(8 * null)
// → 0
console.log("5" - 1)
// → 4
console.log("5" + 1)
// → 51
console.log("five" * 2)
// → NaN
console.log(false == 0)
// → true'

When an operator is applied to the “wrong” type of value, JavaScript will convert that value to the type it needs

*Short-Circuit of Logical Operators*

The logical operators && and || will convert the value on their left side to Boolean type. Meanwhile the ?? will return values on the right if the values on the left are **null** or **undefined**

'console.log(0 || 100);
19
// → 100
console.log(0 ?? 100);
// → 0
console.log(null ?? 100);
// → 100'

**Another important property of these two operators is that the part to their right is evaluated only when necessary.**

## Reflections