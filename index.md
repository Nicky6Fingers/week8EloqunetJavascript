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

It is helpful that javascript converts the data in the operations to what it thinks it needs to make it work. but also you need to pay attention and apply safeguards so that it doesn't mess something up on accident that you didn't intend to happen.

As far as the logical operators i don't believe i have seen the "??" but i imagine that is because it has less things you can do in a kinda classroom Assignment kinda way than && and || would be to make a problem about.
