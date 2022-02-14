transcompile(dart); ligthweight editor Atom?; MDN[item]; official manual;
develop tool Shift+Enter
<script type="meaning changed"></>
separate file cache
"src" set, content ignore.
semicaolons can ignore(automatic semicolon insertion)
engine don't assume ";" before squre brackets "【】"
top of script, "use strict" (beginning of function); no going back; omit when use class and module
don't multiple declare variables
var name should $ _ *first can't be digit*
strict forbit use var before declare
*how to name a variable????*
don't reuse variable
NaN is sticky
BigInt argitrary length; suffix by "n"
typeof null == "object" legacy error
typeof x is more common
IE show 'undefined' when omit defaut value of prompt
convert to string: String(something); null -> 0 and undefiend -> NaN
"0" can be converted to true
> undefined -> NaN, not 0 !
js support **(exp)
"+" merges strings, any is a string, others converted to string
2 + 2 + 1 is "41" not 221
other arithmetic operators convert operands to numbers
"+" also can be unary, convert something to number
+apples + +oranges WTF??? It can explicit convert String to number!
"=" returns value
js has crzay ++/--
bitwise operator 32-bit integer
let a = (1+2, 3+4) --- a == 7
"," can put several operation in one line
number convertion: null -> 0
compare different types, all converted to NUMBER; '2' > 1 == true, ("01" == 1) == true;
0 == '0' is true, however, 0 is false, '0' is true.
null and undefined are a "sweet couple", they equal!(==) (undefined ONLY equals null)
null == 0 is false!(because the "sweet couple", undefined != 0)
? : can be use as (cond ...)!
? : can replace if-else but not recommended.
&& is higher than ||
double "!" can convert to boolean type
continue can be replaced by wraping code into a if level
switch is strict equality test
if we want to return another line , we should wrap it by parenthesis
we can use function before it declare(not expression format)

property shorthand: {name, age, ....}
"49" is a integer property, but "+49" not
V8 garbege collector is inclined to be study in the tutor
also OOP(design patterns, E G R H) or Object oriented analysis and design with applications by G Booch
method shorthand: { sayHi() {alert("")}}
new.target to identify whether in the new mode, we can use it to omit user to input 'new' but not recommend
omit parenthesis if new without parameter, not good.
?. can't be used to write, but can be used to access prop, func,
object prop name can't be num, bool, only string or *symbol*
symbols are skipped by for...in
global symbols
< > use "number" hint
built-in objects (no Date) default same as number
toString and valueOf must return string, otherwise it will be ignored.
js can create primitive wrapper, but not recommended.JS can't auto destroy the box!
use _ to seperate number
both (1234).toString() and 1234..toString(36) is OKf
num.toFiexed(5) return str, should be converted back.
NaN === NaN -> false. must use isNaN(NaN)
Object.is works with NaN, 0 and -0, otherwise equal ===
String:
    length is property not func
    if character not found, [] returns *undefined* but charAt() returns ''
    str.substring() not support negative, but start can greater than end
    str.substr(start, [length!!!])
~n == -(n+1), modern js provide str.include()
array:
    fruit.unshift("apple", "pear")
    simplest way to clear array is: arr.length=0
    splice
    arr.slice() [without arguments] means clone.
    [Symbol.isConcatSpreadable]: true -> treat as array
    arr.forEach(item, index, array)
    arr.includes(), indexOf() use === to compare
    NaN Attention:
        let arr = [NaN];
        alert( arr.indexOf(NaN) ); //-1
        alert( arr.includes(NaN)); //true
    arr.findIndex(...), find(lambda(item, index, array)) <- can be omitted
    find for one, filter for more
    map
    arr.sort() in place!!!
    arr.revese() can both inplace and have return value.
    "abcd".split('') == ["a", "b", "c", "d"]
    arr.reduce((accum, item, index, array)=>{}, [maybe initalization])
    arrow func can't be bound?!
    sort(), reverse(), splice modify array itself
    arr.fill() arr.flat()
Iterate:
    Symbol.iterator
    array.from(anythingIterableOrArraylike, [or also mapFn])
func:
    Dead ZONE?!
global:
    globalThis.
func:
    f.length() provide parameters, polymorphism
    property,,,, static?
Time:
    4 ms magic
func:
    func.call(CONTEXT)
    func.apply()
    func.bind() : can fixed the argument
    partial function application _.partial
    "don't want to leave the current context"?
