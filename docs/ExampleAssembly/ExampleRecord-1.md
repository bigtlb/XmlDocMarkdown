# ExampleRecord&lt;T&gt; record

A C# 9 generic record&lt;T&gt;.

```csharp
public record ExampleRecord<T> : IEquatable<ExampleRecord>
```

| parameter | description |
| --- | --- |
| T | Some generic type |
| Name | A readonly string |
| Age | A readonly int |
| Days | A Hashset&lt;DayOfWeek&gt; |
| GenericType | A generic type parameter. |
| GenericLambda | An Action&lt;T&gt; lambda parameter. |

## Public Members

| name | description |
| --- | --- |
| [ExampleRecord](ExampleRecord-1/ExampleRecord.md)(…) | A C# 9 generic record&lt;T&gt;. |
| [Age](ExampleRecord-1/Age.md) { get; set; } |  |
| [Days](ExampleRecord-1/Days.md) { get; set; } |  |
| [GenericLambda](ExampleRecord-1/GenericLambda.md) { get; set; } |  |
| [GenericType](ExampleRecord-1/GenericType.md) { get; set; } |  |
| [Name](ExampleRecord-1/Name.md) { get; set; } |  |
| [Deconstruct](ExampleRecord-1/Deconstruct.md)(…) |  |
| virtual [Equals](ExampleRecord-1/Equals.md)(…) |  |
| override [Equals](ExampleRecord-1/Equals.md)(…) |  |
| override [GetHashCode](ExampleRecord-1/GetHashCode.md)() |  |
| override [ToString](ExampleRecord-1/ToString.md)() |  |
| [operator ==](ExampleRecord-1/op_Equality.md) |  |
| [operator !=](ExampleRecord-1/op_Inequality.md) |  |

## Protected Members

| name | description |
| --- | --- |
| [ExampleRecord](ExampleRecord-1/ExampleRecord.md)(…) |  |
| virtual [EqualityContract](ExampleRecord-1/EqualityContract.md) { get; } |  |
| virtual [PrintMembers](ExampleRecord-1/PrintMembers.md)(…) |  |

## See Also

* namespace [ExampleAssembly](../ExampleAssembly.md)
* [ExampleRecord.cs](../../tests/ExampleAssembly/ExampleRecord.cs)

<!-- DO NOT EDIT: generated by xmldocmd for ExampleAssembly.dll -->
