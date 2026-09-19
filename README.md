# DLL Learning Project

This repository contains my experiments and learning exercises while studying **DLLs (Dynamic Link Libraries)** in **C#** and **Unity**.
My interest in DLLs started when I noticed that some of Unity's built-in scripts and systems could not be directly edited. I became curious about how Unity hides and organizes parts of its codebase, and I wanted to understand what happens behind the scenes.
## Overview

The goal of this project was to understand:

- What DLLs are and how they work
- Creating class libraries in C#
- Compiling code into DLL files
- Importing external DLLs into Unity
- Accessing classes, methods, and properties from DLLs
- Organizing reusable code outside of Unity projects

## What I Learned

During this learning project, I explored:

### C# Class Libraries
- Creating separate C# libraries
- Building DLL files
- Managing namespaces
- Public vs private accessibility

### Unity Integration
- Adding DLLs to Unity projects
- Calling DLL methods from MonoBehaviours
- Understanding assembly references
- Testing reusable code across projects

### Benefits of DLLs
- Code reuse
- Better project organization
- Faster development workflows
- Separation of concerns
- Easier maintenance for shared systems

## Project Structure

```text
/
├── DLL Source Code
├── Unity Test Project
├── Documentation
└── README.md
```

## Example Usage

```csharp
using MyLibrary;

public class TestScript : MonoBehaviour
{
    void Start()
    {
        MyClass myObject = new MyClass();
        myObject.Execute();
    }
}
```

## Purpose

This repository serves as a personal learning reference and a record of my progress while learning advanced C# and Unity development concepts.

## Technologies Used

- C#
- Unity
- .NET Class Libraries
- Visual Studio

## Notes

This project was created for educational purposes while learning how to build and use DLLs within Unity projects.

---
(AI Generated ) I am not fan of AI but I need a clean rm :(
