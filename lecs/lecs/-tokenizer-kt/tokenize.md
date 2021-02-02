---
title: tokenize -
---
//[lecs](../../index.md)/[lecs](../index.md)/[TokenizerKt](index.md)/[tokenize](tokenize.md)



# tokenize  
[jvm]  
Content  
final [List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[Token](../-token/index.md)>[tokenize](tokenize.md)([String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)[input](tokenize.md))  
  
More info  


Converts a string into a list of tokens. The tokens are as follows:

<ul><li>Single quote delimited strings with escapable single quotes terminating on end of line and end of string,</li><li>Double quote delimited strings with escapable double quotes terminating on end of line and end of string,</li><li>Semicolon signaled line comments,</li><li>Brackets: (, ), {, }, , ,</li><li>Whitespace separated unicode-16 strings.</li></ul>

Whitespace is considered insignificant and is only used to mark separation of tokens.



#### Return  


The list of tokens produced from input



## Parameters  
  
jvm  
  
|  Name|  Summary| 
|---|---|
| <a name="lecs//tokenize/#kotlin.String/PointingToDeclaration/"></a>input| <a name="lecs//tokenize/#kotlin.String/PointingToDeclaration/"></a>
  
  



