# Expr.NewObject Method (F#)

Creates an expression that represents the invocation of an object constructor.

**Namespace/Module Path:** Microsoft.FSharp.Quotations

**Assembly:** FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD

```
// Signature:
static member NewObject : ConstructorInfo * Expr list -> Expr

// Usage:
Expr.NewObject (constructorInfo, arguments)
```

#### CAPS_PARAMETERS_MD
*constructorInfo*
Type: **T:System.Reflection.ConstructorInfo**


The description of the constructor.


*arguments*
Type: [Expr](http://msdn.microsoft.com/en-us/library/ed6a2caf-69d4-45c2-ab97-e9b3be9bce65)[list](http://msdn.microsoft.com/en-us/library/c627b668-477b-4409-91ed-06d7f1b3e4a7)


The list of arguments to the constructor.



**The resulting expression.**
## CAPS_REMARKS_MD

## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Quotations.Expr Class &#40;F&#35;&#41;](Quotations.Expr+Class+%28F%23%29.md)

[Microsoft.FSharp.Quotations Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Quotations+Namespace+%28F%23%29.md)
