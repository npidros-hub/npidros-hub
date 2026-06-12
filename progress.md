# This is all my progress.
i love memory managing, like write/read other procs mem
and web-developement also too! so today im learning some new languages (for me and my knowledges)
read messages below.
I Know. this looks like im clown trying to learn something and you reading it. but my coding skills was really bad so i tried an a my own experiment to rank up from junior+ who knows only language basics and small things to middle/senior.   

> I can make errors in text, so please dont hate me.

# Week One (#1)
I’ve been learning ruby for ~7 days and loving it ~except my brain is still stuck in C# mode. Ruby isn’t directly compatible with C# .dll files, but I found a workaround:

> run localhost: and let C# send requests to it, and let ruby handle the logic

## Why ruby
- good to storage data on databases by using ruby
- lua/luau but for databases
- to create clean code

for example, comparison with basic math:

```csharp
double x = 25.5;
int y = 15;
double z = 0.05;

if (x/5 + y/2 - z || !5+5 == 5) { ... }
else { ... }
```

and in ruby its

```ruby
x = 25.5
y = 15
z = 0.05
if x/5 + y/2 - z || !5+5 == 5 then ...
else ... end
```

<p align="left">
 <img width="200px" src="img.png" alt="qr"/>
</p>

> eazier syntax (# instead of //)

> for web, databases, data structures, etc.

> ruby knowledge needed to reverse my utils

## Plans in future
- learn **Zig, Nim, Go, JS, Dart, Lua/Luau** (lua=luau)
- planning to move into leetcode soon

# First results. (#4)
## What was changed?
- ruby: easy, but memory management is dead and sorry ('garbage')
- c#: completed some complicated tasks
- lua/luau: got ranked 1# on leaderboards in my coding app (on alt) 
- html/css: can be mastered in ~35 days for big $ (without deep experience)
- javascript: hard but trying

backend can give heart with live to frontend application so i selected ruby for data/databases.

(next days)
my first *nightmare* after chilling in c# on someone exploit-apis and done im 'senior' dev was thing called "leetcode". eazy-difficuilted tasks was really ez and can be completed in 1 - 8 mins. but when i tried hard ones i died 

# More (#5)
currently im more leaning on documentations. nothing new for today because exams. in **JS** (JavaScript) here's unique things like == and ===, in ruby 'unless' operator

and more. in next day i will go nim or zig and after golang 
these 3 languages have syntax that i never seen before

also recomendded this site for learning languages - learnxinyminutes.com

# First changes (#8)
this is my logs for day 5 - 8, in c# i learned how to work with arrays (by array class), counting, basic math and more. 

completed first part of c#, [certificate](https://coddy.tech/certifications/XA2TGB-csharp-dAHyUu)

> got almost every task in first attempt. also now im learning smarter on 3/7 when 1yr ago it was overloaded on 9/7

two days left untill all my exams will end. learned alot of things in spring period from school/programs/documentations, who dont knows im learning reverse engineering too. got source of even most obfuscated exe/dll/web services, listening/hosting, burping, injections, xor keys, bytecode stuff, etc.

thanks for reading my message. other days will be funnier with classes, lists, hashes and c# dirictories. maybe i will also host something open-sourced by me

# News (#11)
(day 10) sad news but currently i left from coding in dart. also my latest exam will be already in some hours (math helped me very much with coding)

and in result changing to C (will be my worst nightmare ever) but it helps in assembly and reverse engineering. thx for reading

(day 11)

completed all my exams and next will be in ~6 months

writing this after day, left from one more language (GO)
really burned out with all my languages. so i decided to left from one more
i dont see something big here. in the fact both projects (GO, Dart) was created by google

i dont know good points in google programming languages

not forgot about learning too and today i learned JSON library from ruby, writted my first hi world program in nim and basic math (nim is unique). also learned a little about SQL in ruby (+ ruby hashing / json hashing)

i will use nim to do things like: disabling windows defender (if false detections will occur), hiding and obfuscating tools to make it ud, more. 

sad but still good day # **good reading**
(thanks for reaching first 100 lines)

<p align="left">
 <img width="200px" src="left.png" alt="trash"/>
</p>

# Math (#16)
(day 12 - 13)
**in this part im going to showcase everyone what i learned, almost everything is math and needs math so it took me 5 days ~(when normally 3 days)**

this part is very overloaded with texts and documents, so i hidded everything. 
open details section to view documentation

```csharp
Math.Sqrt();
```
<details>
this thing will return square root of number you entered, for example in easy words: if number to use sqrt() method on it is 25 returned value going to be 5, because 5 * 5 = 25, like two numbers will be always exactly same. if you used 16 on it returned value will be 4, because 4 * 4 = 16
</details>

```csharp
Math.Pow();
```
<details>
so if you use 2 in first arg and 3 in other arg on it returned value will be 8. because you just used 2³. so 2 * 2 * 2 = 8! like first arg is what number you want to multiply and arg 2# is how much times you want to multiply it. if 2# arg will be 4 result is going to be 2⁴ 
(2 * 2 * 2 * 2) (output: 16)
</details>

```csharp
System.Linq.Average();
```
<details>
dont know but if im not wrong valid answer is to find average number in array(s)
</details>

```csharp
Math.Min();
```
<details>
to find minium number, like if you use Math.Min(5, 6); output is = 5
</details>

```csharp
Math.Max();
```
<details>
to find maxium number. Math.Max(5, 6); output is = 6
</details>

#### Byte; and sbyte;
<details>
for very small numbers, both of them has 8 bits / 1 byte. byte range is from 0 to 255. and some time ago i published project on my profile named "Console Improvization" and i used bytes in one of my function args, like WriteLineRgb(byte r, byte g, byte b) (rgb range is from 0 to 255).

also in math with bytes we need to use

```csharp
byte a = 10, b = 20;
byte sum = (byte)(a + b);
```

because without (byte) this is going to be error

sbyte is to save your disk space or memory. in sbyte allowed numbers from range -127 to 128
(supports negative numbers, byte can allow only > 0 but sbyte can allow < 0)
you can't use negative numbers on byte but sbyte allows it. by using it byte will return error.

we also can work with math and sbyte! for this we need to use

```csharp
sbyte baseValue = 2;
sbyte exponent = 3;

double result = Math.Pow(baseValue, exponent);
sbyte finalResult = (sbyte)result;
```

and result is going to be always 8
</details>

```csharp
Dictionary<TKey, TValue>
```
<details>
#1 arg is type key, #2 arg is type value

objective: when we need to add user and unique id fast or object and their value but buzy to return into line where we added list of words or hard to work with it = dictionary will help

for example:

```csharp
Dictionary<string, int> students = new Dictionary<string, int>();
students.Add("Alice", 85);
students.Add("Bob", 92);
students.Add("Charlie", 78);
```

and done! everything has their unique id! not only words
or we can make other dictionary types like <int, string>, etc.

method 2:

```csharp
Dictionary<string, int> students = new Dictionary<string, int>
{
    {"Alice", 85},
    {"Bob", 92},
    {"Charlie", 78}
};
```

if we want to check something here but dictionary is too big or overloaded:

```csharp
if (students.ContainsKey("Bob"))
{
    Console.WriteLine("Bob eats bob"); //example with Bob
}
```

to write all names and their unique ids

```csharp
foreach (KeyValuePair<string, int> kvp in students)
{
    Console.WriteLine($"student: {kvp.Key}, id: {kvp.Value}");
}
```

we also can remove someone:
```csharp
students.Remove("Bob");
```
or even clear everything by using Clear();
```students.Count();``` will return value of key-value pairs
and etc.
</details>

### (Time to talk about nim)
nim is very unique language. coding in nim holds instructions, for example:
```nim
var x: int = 5
```
and we just said: create var named x with integer type and valued 5
when in other languages: create int x with value 5

so we giving compiler more info about what we going to create
or method 2: **var x = 5**

i can also store multiple variables

```nim
var
  a = 4
  b = "yes"
```

comments like in ruby

```nim
#[
yes
multi
 #[
 multi comments
 #]
#]
```

i dont want to add more things, because i will reach 600 lines if im going to document every single thing here what i learned + styling them can take hours

my brain almost exploded after learning that in 2 days so im currently trying to stop learning and focus on what i learned. thanks.

added two more projects, about how to secure your code and DRY. learned about it just today. also im middle+ if you want to be like me you can take info from both projects <:

(day 14)

today i started learning zig programming language, zig is one of hardest programming languages for me, because all these unknown for me types i8, i32, i47, u64, i32, u32
> started zig for memory editing and windows stuff

but zig is like nim in some things, like nim is:

```nim
var x: int = 5;
```

and in zig (collected this example from other guy)

```zig
const x: i32 = 47;
```

im currently using vscode for nim and online compilers for zig because there's no web-compilers for nim

and i think if in zig when you working with memory only 1 small error will cause crash in your pc and black screen

but its okay. please say me how to understand with that?? 
```zig
+| <<| *| -%= .{} [_]
```

also i readed zig is [C]() but better and i need to learn C before doing on zig

[ityonemo](https://gist.github.com/ityonemo/769532c2017ed9143f3571e5ac104e50) helped me alot
all those stuff are very complicated with C so thanks to this guy


**published** more projects on my profile, read if you want
> [Code like Senior](https://github.com/npidros-hub/Proffesional-Code)
<small> you want to be like senior in programming? this is for you! </small>

> [Secure your game](https://github.com/npidros-hub/Shadow-Check)
<small> exploiters can affect your game!? just read this. </small>

(day 15)

today i started learning more things in zig programming language. also i randomly found this language named [rux](https://github.com/rux-lang/Web/blob/main/src/examples/Pointer.rux) 

maybe i will never start using this but try rux if you want

what i learned:

| i  | u |
| ------------- | ------------- |
| Signed  | Unsigned |

signed value types: number with symbol, can be negative and > 0 too

unsigned value types: symbols are unallowed, only > 0

> values: 8, 16, 32, 64, 128 (bits)

*i8* (8 bits) values: -128 to 127 (like sbyte), 

*u8* (8 bits) values: 0 to 255 (like byte in c#),

*i32* (32 bits) like normal int analog in other languages, 

*u64* (64 bits) values: 0 to 18 quintillions

f32 = float, f64 = double

i1 = (1 bit), values: 0 - 1, etc.

```hello world``` in zig

```zig
const std = @import("std");

pub fn main() void {
     std.debug.print("Hello world!\n", .{});
}
```

i will explain, in first line we importing ```std``` library by ```@import```

> to create main method we need to use ```pub fn```, pub = public, fn = function

we have ```std.debug.print``` to print something, im by using that printing hello world message in my terminal.

now you know. also by using ```\n``` we printing our message on next line. ```.{}``` is automatically **null type tuple** (list of arguments)

i cant skip this one, because compiler will give me error. ```.{}``` is used to print arguments.

```zig
const name = "World";
std.debug.print("Hello, {s}!\n", .{name});
```

asking it to print: "Hello, World"

{s} = like we saying that now we going to print ```name``` and this is going to be string type
.{name} = printing const string with "World" source

or if we want to print something more this will be hungry games with our brain:

```zig
const score = 100;
const label = "value";

// output: value: 100
std.debug.print("{s}: {d}\n", .{label, score}); 
```

in this example im saying to compiler: ok, firstly im going to print string type named ```label``` and after decimal type named ```score```

(decimal = every number, can be negative or > 0) 

> second type example

(day 16)
latest day in this part

we also can create our int32 types in zig (example from [@]()ityonemo)

```zig
const std = @import("std");

fn foo() i32 {
    return 47;
}

pub fn main() void {
    var result = foo();
    std.debug.print("foo: {}\n", .{result});
}
```

but it will crash if we normally try to call ```foo();```

# What next? (#18)
i was buzy adding info to day 16 so it got almost nothing and uncompleted, maybe i will also comeback to coddy soon because i love documentations better, today i started learning ruby back again with zig and other languages too

today i learned more ruby basics, apache kafka and rabbitMQ

google if you want also read more about it

(day 18)
today i went to learning basic reverse engineering and assembly instructions, like registers and ```mov``` instruction. 

now i know in zig we also can add value to something later with ```undefined``` operator
(for example):
```zig
var b: i32 = undefined;
```

arrays in zig:
```zig
const a = [5]u8{ 'h', 'e', 'l', 'l', 'o' };
```

[5] is how much chars we got (array size) like here we got 5, u8 is child type
if we dont know array size we can just put [_] without number

```zig
const array = [_]u8{ 'h', 'e', 'l', 'l', 'o' };
const length = array.len;
```

or we can use ```array.len``` to get size of array

(day 19 - 20)

today i started learning more reverse engineering and assembly, and what im going to say = that assembly is not too hard

yeah someone maybe thinks im mad now but i've learned basic assembly instructions already, like: ```mov rcx, rdx```, je, jne, sub (-), add (+)

and reversed one more popular project (xeno)

its hard to save what i learned past days ago, all info what i got.
im trying to not overload my brain and changing from 100% keyboard -> 80% keyboard to type faster

im sharing my life how i can

<p align="left">
 <img width="200px" src="goodenough.png" alt="qr"/>
</p>

+kotlin
> im not using kotlin programming language to write big mobile apps, im trying to understand how to find useful things like offsets for mobile (lvl upping my reverse skills and working with mobile stuff)

good fact: ```const``` in kotlin is ```val```

kotlin also has unique math stuff

```kotlin
fun main()
{
   val x = 5
   val y = 5
   println("the result is ${x + y}")
}
```

i dont think we have that also in other languages but we dont need to store result and after call it, we just can use this code (fun = function)

# Powerful Section (#23)
(day 21)
today i almost completed all of the kotlin programming language basics and starting OOP soon. learned something about while() loop and basics. today i also reversed solara icons by deobfuscating solara bootstrapper.

(day 24)
i was offline for alot of time cuz recently i was working on my project. i also need to lvl up my memory skills and learn something useful. im going to contiue with apache kafka

in kotlin we have constructors, there's two types of them: secondary, primary
(example)

```kotlin
class Person(val name: String, var age: Int) { // Primary constructor

    // Secondary constructor
    constructor(name: String) : this(name, 0) { 
        println("secondary constructor called for $name")
    }
}
```

to use primary constructors we just can use example below, without using new() 

```kotlin 
val user = Person("Alice", 25)
```

in secondary constructors we cant use val/var keywords. to use arguments you dont need to exactly add it. ```name: String```

example: 

Imagine the Primary constructor is a strict security guard at the door of club "Person". He has a strict rule: "I will only let you in if you have BOTH a Name AND an Age."

you call the Secondary constructor: Person("Alice"). You only give a name.

thehe Secondary constructor (your helper) knows the guard will not let you in like this.

so, using the trick : this(name, 0), the helper takes your name "Alice", makes up an age 0, and gives both to the guard (the primary constructor).

the guard is happy now (he gets both a name and an age), creates the person, and lets them in.

the main point: The primary constructor creates the actual person, and the secondary constructor just helps you when you do not have all the information (like the age).

<sub>(used translator for it)</sub>

(day 27)

i learned kafka and this video helped me alot.

this video explains the core concepts of kafka perfectly. ([link](https://www.youtube.com/watch?v=QkdkLdMBuL0))

this one explains base about frontend. ([link](https://www.w3schools.com/htmlcss/))

at this moment im working on security software engineering and on some projects. save my profile if you need more story about what i learned

(day 29)
in zig, we also normally have imports from other files like in any other programming languages. this is a simple example of this:

```zig
const user = @import("core/example.zig").User;
```

```zig
//core/example.zig
pub const User = struct {
    power: u64,
    name: []const u8,
}; //we need to make it public everytime to make it static
```

> credits: zig-lang website

also in this example i showcased how do structure being realized in zig! 
structures also can contain methods 

```zig
//core/example.zig
pub const User = struct {
    power: u64 = 0,
    name: []const u8,

    pub const SUPER_POWER = 9000;

    fn diagnose(user: User) void {
        if (user.power >= SUPER_POWER) {
            std.debug.print("how! power more than {d}!!!", .{SUPER_POWER});
        }
    }
};
```

> one more note: in function arguments we saying that user = User (our structure) to check power by using user.power, if this arg will be deleted this code cant be compiled anyone.

we also got this one:

```zig
const a = [_]i32{1, 2, 3, 4, 5};
const b = a[1..4];
```

looks ok but what happends ```b``` constant??

simple answer: this thing named 'cutted constant', if we have ```const a``` with 5 numbers and ```const b``` with ```a[1..4]``` if we try to output ```b``` in console the output will be: ```2, 3, 4```.  we just cutted constant in our first time! (4 is being ignored to be cutted)
