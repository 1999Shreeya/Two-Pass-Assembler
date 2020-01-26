# Two-Pass-Assembler

 -------------------------------------------------------------------------------------------------------------------------------
 -------------------------------------------------------------------------------------------------------------------------------

Assemblers typically make two or more passes through a source program in order to resolve forward references in a program. A forward reference is defined as a type of instruction in the code segment that is referencing the label of an instruction, but the assembler has not yet encountered the definition of that instruction.

    Pass-1:
        1.Define symbols and literals and remember them in symbol table and literal table respectively.
        2.Keep track of location counter
        3.Process pseudo-operations
    Pass-2:
        1.Generate object code by converting symbolic op-code into respective numeric op-code
        2.Generate data for literals and look for values of symbols
 
 -------------------------------------------------------------------------------------------------------------------------------
 -------------------------------------------------------------------------------------------------------------------------------
 
 This code is written in C++ to implement a two pass assembler.
 Instructions to run this program ::
     Pass-1: 
         1.Extract everything to single folder.
         2.Run the pass-I.cpp file.
         3.Output is generated as IntermediateCode.txt
     Pass-2:
         1.Extract everything to single folder.
         2.Run the pass-II.cpp file.
         3.Output is generated as MachineCode.txt

-------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------
