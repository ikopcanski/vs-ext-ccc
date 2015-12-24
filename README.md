# vs-ext-ccc
Visual Studio extension for generating code contracts for your C# interfaces (Code Contracts Microsoft  RiSE project).
They work as validation for input parameters and output values, triggered optionally during debugging. 
Relieves you from having the validation code clutter in the begging or end of methods and properties,
but you can still have that exception you want to be thrown when unexpected value enters or leaves method/property.
This VS extension generates the class that appears "hidden under" your interface in Solution Explorer.
Class containing the code contract is generated by Roslyn compiler (set of syntax rewriters)
while VS Extensibility framework is used to add context menu command.
