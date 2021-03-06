---
title: "no_namespace import attribute"
ms.date: "08/29/2019"
f1_keywords: ["no_namespace"]
helpviewer_keywords: ["no_namespace attribute"]
ms.assetid: 5d81b741-a558-451b-b493-1f3b18967337
---
# no_namespace import attribute

**C++ Specific**

Specifies that the compiler doesn't generate a namespace name.

## Syntax

> **#import** *type-library* **no_namespace**

## Remarks

The type-library contents in the `#import` header file are normally defined in a namespace. The namespace name is specified in the `library` statement of the original IDL file. If the **no_namespace** attribute is specified, then this namespace isn't generated by the compiler.

If you want to use a different namespace name, then use the [rename_namespace](../preprocessor/rename-namespace.md) attribute instead.

**END C++ Specific**

## See also

[#import attributes](../preprocessor/hash-import-attributes-cpp.md)\
[#import directive](../preprocessor/hash-import-directive-cpp.md)
