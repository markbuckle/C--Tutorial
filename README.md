<h2>C# Tutorial</h2>

**C# vs .NET**

C# is a language. .NET is a framework for building applications on Windows. .NET is not limited to C#

**.NET**

.NET framework consists of two components:

1) Common Language Runtime (CLR) 
2) Class Library

**CLR**

Common Language Runtime (CLR) takes the Intermediate Language (IL) code and converts it to Native Code (Machine Code). This process is also referred to as Just-in-time Compilation (JIT).

<img src="https://github.com/markbuckle/Csharp-Tutorial/blob/main/C%23-tutorial-img1.png" width=500>

When you build an application with C#, at a high level, your app consists of building blocks called **classes**. A class is a container that has some data aka **attributes** and functions aka **methods**. 

As our number of classes grows, we use namespaces. A **namespace** is a container for related classses, for example, there are often namespaces for database classes, graphics/images, security, etc.

An **assembly** is a container of related namespaces. It can either be a dynamically linked library (DLL) or executable (EXE). 
