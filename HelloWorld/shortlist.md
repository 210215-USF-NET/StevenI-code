CLR (Common Language Runtime)
 - Runtime that manages a bunch of stuff, garbage collection, etc.
 -  JIT (Just in Time) compiler
   - takes in code, transforms code into machine code that machine understands, the machine can then run your code

obj and bin folders
 - build output
 - result of running .net build

 dotnet run
 - dotnet build + run the code

dotnet build
 - compiles code

 TLDR compilation process:
 .cs file > compiled using MSBUILD > intermediate language (IL) > common language runtime (CLR) > processed by JIT > machine code

 "using" is like an import keyword in java
