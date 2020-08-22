# Coding Guidelines
The following guidelines aim to provide a framework to write code in a consistent style. If the following guidelines are incomplete the official [C# coding conventions](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/inside-a-program/coding-conventions) and [framework design guidelines](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/) apply.

## Comments
- Begin a comment with an uppercase letter.
- End a comment with a period.
- Insert a space before starting the comment text.

## Implicitly Typed Local Variables
- Use `var` for variables if the type of the right hand side expression is obvious or not important.

## New Operator
- Use object initializers to create objects.

## Members
Members include: Properties, constructors, methods, fields, events.
- Call static members by using the class name: `MyClass.MyMember`.
- Fields are only allowed to be private. If needed create a property.

## Naming
- Don't use underscores or hyphens.
- Don't use Hungarian notation.
- Don't use abbreviations as part of identifier names.
- Use `PascalCase` for all public / protected members.
- Use `PascalCase` for all types.
- Use `camelCase` for all private members and parameter names.

## Structure of *.cs files
Partial classes are allowed do split the content of a class into well named files with the following notation: `Class1.Part1.cs`

Inside a source file the structure is like:
 1. Private fields
 2. Properties (enclosed in a region tag `#region Properties`)
 3. Constructors
 4. Methods
 
 ## Access modifiers
 All access modifiers should explicitly stated in the code.
 