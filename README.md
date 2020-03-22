###  CSharp interview questions

<br/>

| Number | Question                                                                    |
| ------ | --------------------------------------------------------------------------- |
| 1      | [What is C# ?](#What-is-C#)                                                 |
| 2      | [What is the root type of all types ?](#What-is-the-root-type-of-all-types) |
| 3      | [What is object ?](#)                                                       |
| 4      | [What is value type ?](#)                                                   |
| 5      | What is reference type ?                                                    |
| 6      | What is class ?                                                             |
| 7      | What is struct ?                                                            |
| 8      | What is the difference between struct and class ?                           |
| 9      | What is enum ?                                                              |
| 10     | What are the types of class ?                                               |
| 11     | What is sealed class ?                                                      |
| 12     | What is partial class ?                                                     |
| 13     | What is default class access modifier ?                                     |
| 14     | What is abstract class ?                                                    |
| 15     | What is interface ?                                                         |
| 16     | What is the difference between interface and abstract class ?               |
| 17     | What is anonymous type ?                                                    |
| 18     | What is boxing and unboxing ?                                               |
| 19     | What is the difference between value type and reference type ?              |
| 20     | What is inheritance ?                                                       |
| 21     | What is encapsulation ?                                                     |
| 22     | What is polymorphism ?                                                      |
| 23     | What is managed code and unmanaged code ?                                   |
| 24     | What is the difference between virtual method and abstract method ?         |
| 25     | What is namespace ?                                                         |
| 26     | What is the difference between break and continue ?                         |
| 27     | What is the difference between constant and readonly ?                      |
| 28     | What is the difference between ref and out ?                                |
| 29     | What is the difference between finalize and dispose ?                       |
| 30     | What is the difference between finalize and finally ?                       |
| 31     | What is the difference between string and System.String ?                   |
| 32     | What is the difference between String and StringBuilder ?                   |
| 33     | What is delegate and how to use delegate?                                   |
| 34     | What are types of delegates ?                                               |
| 35     | What is event ?                                                             |
| 36     | What is the relationship between delegate and event ?                       |
| 37     | What is generics ?                                                          |
| 38     | What is lazy loading ?                                                      |
| 39     | What is IEnumerable<T> ?                                                    |
| 40     | What is property ?                                                          |
| 41     | What is indexer ?                                                           |
| 42     | What is .NET Framework ?                                                    |
| 43     | What is CLR ?                                                               |
| 44     | What is CTS ?                                                               |
| 45     | What is CLI ?                                                               |
| 46     | What is BCL ?                                                               |
| 47     | What is DLR ?                                                               |
| 48     | What is side by side execution ?                                            |
| 49     | What is Application domain ?                                                |
| 50     | What is GAC ?                                                               |
| 51     | What is JIT ?                                                               |
| 52     | What are the types of JIT ?                                                 |
| 53     | What is GC ?                                                                |
| 54     | What is IL ?                                                                |
| 55     | What is manifest ?                                                          |
| 56     | What is CAS ?                                                               |
| 57     | How many ways are there to overload a method ?                              |
| 58     | How "using" is used ?                                                       |
| 59     | What is serialization ?                                                     |
| 60     | What is jagged array ?                                                      |
| 61     | What is LINQ ?                                                              |
| 62     | What is Lambda expression ?                                                 |
| 63     | What is dealock ?                                                           |
| 64     | What is race condition ?                                                    |
| 65     | What is thread ?                                                            |
| 66     | What are status of a thread ?                                               |
| 67     | What is multithreading ?                                                    |
| 68     | What are types of thread ?                                                  |
| 69     | What are async and await ?                                                  |
| 70     | What is covariance ?                                                        |
| 71     | What is contravariance ?                                                    |
| 72     | What is async and await ?                                                   |



1. #### What is C# ?

C# (pronounced "See Sharp") is a modern, object-oriented, and type-safe programming language. C# has its roots in the C family of languages and will be immediately familiar to C, C++, Java, and JavaScript programmers.

C# (pronounced "See Sharp") is a general-purpose, multi-paradigm programming language encompassing strong typing, lexically scoped, imperative, declarative, functional, generic, object-oriented (class-based), and component-oriented programming disciplines. It was developed around 2000 by Microsoft as part of its .NET initiative, and later approved as an international standard by Ecma (ECMA-334) and ISO (ISO/IEC 23270:2018). Mono is the name of the free and open-source project to develop a compiler and runtime for the language. C# is one of the programming languages designed for the Common Language Infrastructure (CLI).

C# was designed by Anders Hejlsberg, and its development team is currently led by Mads Torgersen.

**[↥ back to top](#CSharp-interview-questions)**

<br/>

2. #### What is the root type of all types?

C# has a unified type system. All C# types, including primitive types such as int and double, inherit from a single root object type. Thus, all types share a set of common operations, and values of any type can be stored, transported, and operated upon in a consistent manner. Furthermore, C# supports both user-defined reference types and value types, allowing dynamic allocation of objects as well as in-line storage of lightweight structures.

**[↥ back to top](#CSharp-interview-questions)**

<br/>

3. #### What is object?



**[↥ back to top](#CSharp-interview-questions)**

<br/>


31. #### What is the difference between string and System.String ? 

The string type represents a sequence of zero or more Unicode characters. string is an alias for System.String in .NET.

 

| C# Reference type keyword | .NET type     |
| ------------------------- | ------------- |
| object                    | System.Object |
| string                    | System.String |

| C# Value type keyword | .NET type      |
| --------------------- | -------------- |
| bool                  | System.Boolean |
| byte                  | System.Byte    |
| sbyte                 | System.SByte   |
| char                  | System.Char    |
| decimal               | System.Decimal |
| double                | System.Double  |
| float                 | System.Single  |
| int                   | System.Int32   |
| uint                  | System.UInt32  |
| long                  | System.Int64   |
| ulong                 | System.UInt64  |
| short                 | System.Int16   |
| ushort                | System.UInt16  |










