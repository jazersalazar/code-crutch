# C# Naming Convention

## camelCase
- parameters
- arguments
- methodVariables
- functionVariables
- _privateMemberVariables

## PascalCase
- ClassNames
- Methods
- Functions
- PublicMemberVariables
- ProtectedMemberVariables
- (I)Interfaces
- Enums

```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

interface IExampleInterface
{

}

enum ExampleEnums
{

}

public class ExampleClass : MonoBehaviour
{
    // Static variables always being written at the top of the class
    public static int ExampleStaticVariable;

    public int ExamplePublicMember;
    protect int ExampleProtectedMember;
    private int _examplePrivateMember;

    void Start()
    {

    }

    void Update()
    {

    }

    void ExampleMethod(ExampleClass exampleParameter)
    {
        float exampleVariable;
    }
}
```