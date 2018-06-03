># Variables and DataTypes in C#

Variables are conserned with the `storage of data`.You can think of varibles in computer memory as `boxes` sitting on a shelf.You can `put` things in boxes and `take them out` again or you can just look inside a box to see if anything is there. The same goes for variable; you `place data in them and can take it out or look at it, as required`.

Although all data in a computer is effectively the same thing (`a series of 0s and 1s`),
variables come in different flavors, known as types. Using the box analogy again,
boxes come in different shapes and sizes, so some items fit only in certain boxes.
The reasoning behind this type system is that different types of data may require
different methods of manipulation, and by restricting variables to individual types
you can avoid mixing them up. For example, it wouldn't make much sense to treat
the series of 0s and 1s that make up a digital picture as an audio file.To `use variables`, you have to `declare` them. This means that you have to assign them a name and a type.


C# syntax to declare a variable goes like 
     <type> <name>;

> What is the type above?
Simple types include type such as number and Boolean(true or false)
examples of the interger types

|Type                |Allowed Values |
|--------------------|---------------|
|sbyte               |Intergers between -128 and 127|
|byte                |Intergers between 0 and 255   |
|short               |Intergers betwen -32768 and 32767|
|ushort              |interges btwn 0 and 65535        |
|int                 |intergers between -2147483648 and 2147483648
|Long                |intergers btwn −9223372036854775808 and
9223372036854775807
|Ulong               |interges btwn 0 and 18446744073709551615

The `u` character before some variables names are `shorthand` for unsigned , meaning that you can't store negative numbers in variable fo those type.

Your will also need to store floating-ponts values those that aren't whole numbers.Your can use floating point variables 
       <li>float<li>
       <li>double<li>
       <li>decimal<li>
more type examples 
     
|type                   |min value   | max value   |
|-----------------------|------------|-------------|
|float                  |0           |22 power 4   |
|double                 |0           |25 power 5   |
|decimal                |0           |29 power 6   |

Types conserning the character and strings.
|type                   |Allowed values             |
|-----------------------|---------------------------|
|char                   |single unicode character, stored as intergers between 0 and 65535
|bool                   |Boolean Values, true or false|
|string                 |A sequence of Character      |
