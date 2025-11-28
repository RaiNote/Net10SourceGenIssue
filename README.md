This is just a generated project from Rider for a starting point to create a source generator.

It has been adjusted to be .net10 in order to showcase an issue.

The issue being:

inside of an IDE there will be errors in regards to symbols missing from generated types, methods etc. if the source generator project is target net10.

However if the sourcegenerator is targeting net9 and is using Microsoft.CodeAnalysis.CSharp with version 5.0.0 that will work, just like one would expect if it was netstandard2.0
