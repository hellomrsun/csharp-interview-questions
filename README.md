###  CSharp interview questions and answers

<br/>

| Number | Questions                                                                                                                       |
| ------ | ------------------------------------------------------------------------------------------------------------------------------- |
| 1      | [What is C# ?](#What-is-CSharp)                                                                                                 |
| 2      | [What is the root type of all types ?](#What-is-the-root-type-of-all-types)                                                     |
| 3      | [What is object ?](#What-is-object)                                                                                             |
| 4      | [What is value type ?](#What-is-value-type)                                                                                     |
| 5      | [What is reference type ?](#What-is-reference-type)                                                                             |
| 6      | [What is the difference between value type and reference type ?](#What-is-the-difference-between-value-type-and-reference-type) |
| 7      | [What is class ?](#What-is-class)                                                                                               |
| 8      | [What is struct ?](#What-is-struct)                                                                                             |
| 9      | [What are access modifiers ?](#What-are-access-modifiers)                                                                       |
| 10     | [What is sealed class ?](#What-is-sealed-class)                                                                                 |
| 11     | [What is partial class ?](#What-is-partial-class)                                                                               |
| 12     | [What is abstract class ?](#What-is-abstract-class)                                                                             |
| 13     | [What is static class ?](#What-is-static-class)                                                                                 |
| 14     | [What is partial method ?](#What-is-partial-method)                                                                               |
| 15     | [What is sealed method ?](#What-is-partial-method)                                                                               |

| 16     | [What is interface ?](#What-is-interface)                                                                                       |
| 17     | What is the difference between interface and abstract class ?                                                                   |
| 18     | What is anonymous type ?                                                                                                        |
| 19     | What is boxing and unboxing ?                                                                                                   |
| 20     | What is inheritance ?                                                                                                           |
| 21     | What is encapsulation ?                                                                                                         |
| 22     | What is polymorphism ?                                                                                                          |
| 22     | What is abstraction ?                                                                                                           |
| 23     | What is managed code and unmanaged code ?                                                                                       |
| 24     | What is the difference between virtual method and abstract method ?                                                             |
| 25     | What is namespace ?                                                                                                             |
| 26     | What is the difference between break and continue ?                                                                             |
| 27     | What is the difference between constant and readonly ?                                                                          |
| 28     | What is the difference between ref and out ?                                                                                    |
| 29     | What is the difference between finalize and dispose ?                                                                           |
| 30     | What is the difference between finalize and finally ?                                                                           |
| 31     | What is the difference between string and System.String ?                                                                       |
| 32     | What is the difference between String and StringBuilder ?                                                                       |
| 33     | What is delegate and how to use delegate?                                                                                       |
| 34     | What are types of delegates ?                                                                                                   |
| 35     | What is event ?                                                                                                                 |
| 36     | What is the relationship between delegate and event ?                                                                           |
| 37     | What is generics ?                                                                                                              |
| 38     | What is lazy loading ?                                                                                                          |
| 39     | What is IEnumerable<T> ?                                                                                                        |
| 40     | What is property ?                                                                                                              |
| 41     | What is indexer ?                                                                                                               |
| 42     | What is .NET Framework ?                                                                                                        |
| 43     | What is CLR ?                                                                                                                   |
| 44     | What is CTS ?                                                                                                                   |
| 45     | What is CLI ?                                                                                                                   |
| 46     | What is BCL ?                                                                                                                   |
| 47     | What is DLR ?                                                                                                                   |
| 48     | What is side by side execution ?                                                                                                |
| 49     | What is Application domain ?                                                                                                    |
| 50     | What is GAC ?                                                                                                                   |
| 51     | What is JIT ?                                                                                                                   |
| 52     | What are the types of JIT ?                                                                                                     |
| 53     | What is GC ?                                                                                                                    |
| 54     | What is IL ?                                                                                                                    |
| 55     | What is manifest ?                                                                                                              |
| 56     | What is CAS ?                                                                                                                   |
| 57     | How many ways are there to overload a method ?                                                                                  |
| 58     | How "using" is used ?                                                                                                           |
| 59     | What is serialization ?                                                                                                         |
| 60     | What is jagged array ?                                                                                                          |
| 61     | What is LINQ ?                                                                                                                  |
| 62     | What is Lambda expression ?                                                                                                     |
| 63     | What is dealock ?                                                                                                               |
| 64     | What is race condition ?                                                                                                        |
| 65     | What is thread ?                                                                                                                |
| 66     | What are status of a thread ?                                                                                                   |
| 67     | What is multithreading ?                                                                                                        |
| 68     | What are types of thread ?                                                                                                      |
| 69     | What are async and await ?                                                                                                      |
| 70     | What is covariance ?                                                                                                            |
| 71     | What is contravariance ?                                                                                                        |
| 72     | What is async and await ?                                                                                                       |


<br/>
<br/>


1. #### What is CSharp?

C# (pronounced "See Sharp") is a general-purpose, multi-paradigm programming language encompassing strong typing, lexically scoped, imperative, declarative, functional, generic, object-oriented (class-based), type-safe, and component-oriented programming disciplines. 

It was developed around 2000 by Microsoft as part of its .NET initiative, and later approved as an international standard by Ecma (ECMA-334) and ISO (ISO/IEC 23270:2018). 

Mono is the name of the free and open-source project to develop a compiler and runtime for the language. 

C# is one of the programming languages designed for the Common Language Infrastructure (CLI).

C# was designed by Anders Hejlsberg, and its development team is currently led by Mads Torgersen.

ECMA 334 Specification: [Link](https://www.ecma-international.org/publications/standards/Ecma-334.htm)

<br/>

##### C# version & features:

| C# version | Publication year | .NET version                                 | Visual Studio version   | New Features                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ---------- | ---------------- | -------------------------------------------- | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| C# 1.0     | 2002             | .NET 1.0                                     | Visual Studio .NET 2002 | > Classes <br/>> Structs<br/>> Interfaces<br/>> Events<br/>> Properties<br/>> Delegates<br/>> Expressions<br/>> Statements<br/>> Attributes                                                                                                                                                                                                                                                                                                                                           |
| C# 1.2     | 2003             | .NET 1.1                                     | Visual Studio .NET 2003 | > The code generated in a foreach loop called Dispose on an IEnumerator when that IEnumerator implemented IDisposable.                                                                                                                                                                                                                                                                                                                                                                |
| C# 2.0     | 2005             | .NET 2.0                                     | Visual Studio 2005      | > Generics<br/>> Partial types<br/>> Anonymous methods<br/>> Nullable value types<br/>> Iterators<br/>> Covariance and contravariance<br/>> Getter/setter separate accessibility<br/>> Method group conversions (delegates)<br/>> Static classes<br/>> Delegate inference                                                                                                                                                                                                             |
| C# 3.0     | 2008             | .NET 3.5                                     | Visual Studio 2008      | > Auto-implemented properties<br/>> Anonymous types<br/>> Query expressions<br/>> Lambda expressions<br/>> Expression trees<br/>> Extension methods<br/>> Implicitly typed local variables(var)<br/>> Partial methods<br/>> Object and collection initializers<br/>> LINQ                                                                                                                                                                                                             |
| C# 4.0     | 2010             | .NET 4.0                                     | Visual Studio 2010      | > Dynamic binding<br/>> Named/optional arguments<br/>> Generic covariant and contravariant<br/>> Embedded interop types                                                                                                                                                                                                                                                                                                                                                               |
| C# 5.0     | 2012             | .NET 4.5                                     | Visual Studio 2012      | > Asynchronous members<br/>> Caller info attributes                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| C# 6.0     | 2015             | .NET 4.6<br/>.NET Core 1.0<br/>.NET Core 1.1 | Visual Studio 2015      | > Static imports<br/>> Exception filters<br/>> Auto-property initializers<br/>> Expression bodied members<br/>> Null propagator<br/>> String interpolation<br/>> nameof operator<br/>> Index initializers<br/>> Await in catch/finally blocks<br/>> Default values for getter-only properties                                                                                                                                                                                         |
| C# 7.0     | 2017             | .NET 4.7                                     | Visual Studio 2017      | > Out variables<br/>> Tuples and deconstruction<br/>> Pattern matching<br/>> Local functions<br/>> Expanded expression bodied members<br/>> Ref locals and returnsDiscards<br/>> Binary Literals and Digit Separators<br/>> Throw expressions                                                                                                                                                                                                                                         |
| C# 7.1     | 2017             | .NET Core 2.0                                | Visual Studio 2017      | > async Main method<br/>> default literal expressions<br/>> Inferred tuple element names                                                                                                                                                                                                                                                                                                                                                                                              |
| C# 7.2     | 2017             | .NET Core 2.0                                | Visual Studio 2017      | > Techniques for writing safe efficient code<br/>> Non-trailing named arguments<br/>> Leading underscores in numeric literals<br/>> private protected access modifier<br/>> Conditional ref expressions                                                                                                                                                                                                                                                                               |
| C# 7.3     | 2017             | .NET Core 2.1<br/>.NET Core 2.2<br/>.NET 4.8 | Visual Studio 2017      | > Accessing fixed fields without pinning<br/>> Reassigning ref local variables<br/>> Using initializers on stackalloc arrays<br/>> Using fixed statements with any type that supports a pattern<br/>> Using additional generic constraints                                                                                                                                                                                                                                            |
| C# 8.0     | 2019             | .NET Core 3.0                                | Visual Studio 2019      | > Readonly members<br/>> Default interface methods<br/>> Switch expressions<br/>> Property patterns<br/>> Tuple patterns<br/>> Positional patterns<br/>> Using declarations<br/>> Static local functions<br/>> Disposable ref structs<br/>> Nullable reference types<br/>> Asynchronous streams<br/>> Indices and ranges<br/>> Null-coalescing assignment<br/>> Unmanaged constructed types<br/>> Stackalloc in nested expressions<br/>> Enhancement of interpolated verbatim strings |

<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>

1. #### What is the root type of all types?

C# has a unified type system. 

All C# types, including primitive types such as int and double, inherit from a single root **object** type. 

Thus, all types share a set of common operations, and values of any type can be stored, transported, and operated upon in a consistent manner. 

Furthermore, C# supports both user-defined reference types and value types, allowing dynamic allocation of objects as well as in-line storage of lightweight structures.

<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>

3. #### What is object?

Object is the base type for all the other types.

Object's body:

```csharp
[ClassInterface(ClassInterfaceType.AutoDual)]
[ComVisible(true)]
public class Object
{
    [NonVersionableAttribute]
    [ReliabilityContract(Consistency.WillNotCorruptState, Cer.MayFail)]
    public Object();

    [NonVersionableAttribute]
    [ReliabilityContract(Consistency.WillNotCorruptState, Cer.Success)]
    ~Object();

    public static bool Equals(Object objA, Object objB);
    
    [NonVersionableAttribute]
    [ReliabilityContract(Consistency.WillNotCorruptState, Cer.Success)]
    public static bool ReferenceEquals(Object objA, Object objB);
    
    public virtual bool Equals(Object obj);

    public virtual int GetHashCode();

    [SecuritySafeCritical]
    public Type GetType();

    public virtual string ToString();

    [SecuritySafeCritical]
    protected Object MemberwiseClone();
}
```

Object has 2 extension methods: **Equals** and **ReferenceEquals**.
Equals: compares two objects' values
ReferenceEquals: compares two objects' references

Object has 3 default virtual methods **Equals**, **GetHashCode**, **ToString**.
You can override the default methods in your customized derived types (structs, classes).

Object has 1 public method **GetType** to get the type of a variable.

<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>

4. #### What is value type?

Value type includes **all numeric** types, **DateTime**, **Timespan**, **Struct** and **Enum** types.

<br/>

| C# Value type keyword | .NET type       | Description                                                                                                                         |
| --------------------- | --------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| bool                  | System.Boolean  | A true/false value                                                                                                                  |
| byte                  | System.Byte     | Unsigned 8-bit value                                                                                                                |
| sbyte                 | System.SByte    | Signed 8-bit value                                                                                                                  |
| char                  | System.Char     | 16-bit Unicode character (char never represents an 8-bit value as it would in unmanaged C++.)                                       |
| decimal               | System.Decimal  | A 128-bit high-precision floating-point value commonly used for financial calculations in which rounding errors can't be tolerated. |
| double                | System.Double   | IEEE 64-bit floating point value                                                                                                    |
| float                 | System.Single   | IEEE 32-bit floating point value                                                                                                    |
| int                   | System.Int32    | Signed 32-bit value                                                                                                                 |
| uint                  | System.UInt32   | Unsigned 32-bit value                                                                                                               |
| long                  | System.Int64    | Signed 64-bit value                                                                                                                 |
| ulong                 | System.UInt64   | Unsigned 64-bit value                                                                                                               |
| short                 | System.Int16    | Signed 16-bit value                                                                                                                 |
| ushort                | System.UInt16   | Unsigned 16-bit value                                                                                                               |
| DateTime              | System.DateTime | date and time of day                                                                                                                |
| TimeSpan              | System.TimeSpan | time interval                                                                                                                       |

<br/>

The caracteristics of value type is: a value type variable contains a simple value.
When you copy an value type variable, you create **a new copy of the value**.

<br/>

```csharp
//Declare a struct
public struct Rectangle{
    public int X {get;set;}
    public int Y {get;set;}
}

public static void Main(){
    var rectangle1 = new Rectangle(){
        X = 5,
        Y = 10
    };
    var rectangle2 = rectangle1;
    rectangle1.X = 6;
    Console.WriteLine(rectangle1.X); //Display: 6
    Console.WriteLine(rectangle2.X); //Display: 5, rectangle2'X has changed
}
```

<br/>

To check if a variable is value type, you can simply do this:
```csharp
var value = 10;
var isValueType = value.GetType().IsValueType;
Console.WriteLine(isValueType); //Display: true
```

<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>

5. #### What is reference type?

Reference type includes **class**, **string**, **delegates**, **interface**, and **array** types.

<br/>

| C# Reference type keyword | .NET type     | Description                                                           |
| ------------------------- | ------------- | --------------------------------------------------------------------- |
| object                    | System.Object | Base type of all types                                                |
| string                    | System.String | An array of characters                                                |
| dynamic                   | System.Object | To the common language runtime (CLR), dynamic is identical to object. |

<br/>

When you copy an reference type variable, you **create a new copy of reference** pointing to the same value.

```csharp
//Declare a class
public class Circle{
    public int Radius {get;set;}
}

public static void Main(){
    var circle1 = new Circle(){
        Radius = 1
    };
    var circle2 = circle1;
    circle1.Radius = 2;
    Console.WriteLine(circle1.Radius); //Display: 2
    Console.WriteLine(circle2.Radius); //Display: 2, circle2 has the same reference as circle1
}
```

<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>

6. #### What is the difference between value type and reference type?

Value typed data is stored in stack.

Reference typed data is stored in heap, the reference to data is stored in stack.

![](./images/001_stack_heap.png)

<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>

7. #### What is class?

A type that is defined as a class is a reference type.
Its default value is null.

```csharp
public class Student{
    public string Name {get;set;}
}
public static void Main(){
    Student student;
    Console.WriteLine(student.Name == null); //Display: true
}
```

<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>

8. #### What is struct?

A structure type (or struct type) is a value type that can encapsulate data and related functionality.

Typically, you use structure types to design **small data-centric types** that provide little or no behavior. 
For example, .NET uses structure types to represent a number (both integer and real), a Boolean value, a Unicode character, a time instance.

```csharp
public struct Coordinate {
    public decimal X {get;set;}
    public decimal Y {get;set;}
}
```

<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>

9. #### What are access modifiers?

**public**: can be accessed in same assembly or different assembly

**internal**: can be accessed in the same assembly, but not from another assembly.

**protected internal**: can be accessed in the same assembly, or derived types in another assembly.

**protected**: can be accessed in the same class or derived class.

**private protected**: can be accessed in the same class or derived class.

**private**: The type or member can be accessed only by code in the same class or struct.

<br/>

Classes and structs declared **directly within a namespace** (in other words, that aren't nested within other classes or structs) can be either **public** or **internal**. Internal is the default if no access modifier is specified.


```csharp
namespace CSharpAssembly {
    //The following are OK
    public class ClassA {}
    internal class ClassB {} 

    //The following are KO
    //Compile-time error: Elements defined in a namespace cannot be explicitly declared as private, protected, or protected internal
    private class ClassC {} 
    protected class ClassD {}
    private protected class ClassE {} 
    protected internal class ClassF {} 
}
```

<br/>

Class members could be **public**, **internal**, **protected**, **protected internal**, **private**, **private protected**, and **private**.

##### Class member access modifier table:

<br/>

<table>
<tr><td><b>Access Modifier</b></td><td colspan=3><b>Same Assembly</b></td><td colspan=2><b>Different Assembly</b></td></tr>
<tr><td></td><td><b>Same class</b></td><td><b>Derived class</b></td><td><b>Other class</b></td><td><b>Derived class</b></td><td><b>Other class</b></td></tr>
<tbody>
<tr><td><b>Public</b></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td>Y</td></tr>
<tr><td><b>Internal</b></td><td>Y</td><td>Y</td><td>Y</td><td></td><td></td></tr>
<tr><td><b>Protected Internal</b></td><td>Y</td><td>Y</td><td>Y</td><td>Y</td><td></td></tr>
<tr><td><b>Protected</b></td><td>Y</td><td>Y</td><td></td><td>Y</td><td></td></tr>
<tr><td><b>Private Protected</b></td><td>Y</td><td>Y</td><td></td><td></td><td></td></tr>
<tr><td><b>Private</b></td><td>Y</td><td></td><td></td><td></td><td></td></tr>
</tbody>
</table>

<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>

10. #### What is sealed class?

Sealed class can not be inherited.

```csharp
public sealed class A{
    public int Add(int x, int y){
        return x + y;
    }
}
```

<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>

11. #### What is partial class?

Partial class means a class can be divided into several classes.

Partial class could be generated automatically by frameworks like ASP.NET Web Forms, or Entity Framework etc.

ASP.NET Web Forms example:

```csharp
//File: About.aspx.cs
public partial class About : Page
{
    protected void Page_Load(object sender, EventArgs e)
    {
    }
}
//File: About.aspx.designer.cs
public partial class About
{
}
```

In the above About class you can see, if one partial class already inherit from a base class, its homologue will not need to inherit the same base class again in the declaration.

Entity framework generated partial dbContext:

```csharp
public partial class WineDbEntities : DbContext
{
    public WineDbEntities()
        : base("name=WineDbEntities")
    {
    }

    protected override void OnModelCreating(DbModelBuilder modelBuilder)
    {
        throw new UnintentionalCodeFirstException();
    }

    public virtual DbSet<C__EFMigrationsHistory> C__EFMigrationsHistory { get; set; }
    public virtual DbSet<Grape> Grape { get; set; }
}
```

Entity framework generated partial data model:

```csharp
public partial class Grape
{
    public int Id { get; set; }
    public string Name { get; set; }
    public string Description { get; set; }
}
```

Partial class could also be used in different components of the same framework.

Take a example of CoreCLR:

```csharp
//File path: TypeSystem\RuntimeDetermined\TypeDesc.RuntimeDetermined.cs
namespace Internal.TypeSystem
{
    partial class TypeDesc
    {
        public abstract bool IsRuntimeDeterminedSubtype
        {
            get;
        }

        public bool IsRuntimeDeterminedType
        {
            get
            {
                return this.GetType() == typeof(RuntimeDeterminedType);
            }
        }

        public abstract TypeDesc GetNonRuntimeDeterminedTypeFromRuntimeDeterminedSubtypeViaSubstitution(Instantiation typeInstantiation, Instantiation methodInstantiation);
    }
}

//File path: TypeSystem\Serialization\TypeDesc.Serialization.cs
namespace Internal.TypeSystem
{
    partial class TypeDesc
    {
        public virtual bool IsSerializable
        {
            get
            {
                return false;
            }
        }
    }
}
```

**Important:** partial class must be in the same namespace and same physical assembly (.dll or .exe).

<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>

12. #### What is abstract class?

abstract class is always used with abstract method, and act as the base class.

abstract class can not be instantiated, you have to instantiate its derived class.

```csharp
public abstract class Employee
{
    public abstract void Do();
}
public class Worker : Employee
{
    public override void Do()
    {
        //DO
    }
}
```

<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>

13. #### What is static class?



<br/>

**[![](images/chevron.png) back to top](#CSharp-interview-questions-and-answers)**

<br/>


1.    #### What is the difference between string and System.String ? 

The string type represents a sequence of zero or more Unicode characters. string is an alias for System.String in .NET.

string is an alias in C#
System.String is a .NET type.













