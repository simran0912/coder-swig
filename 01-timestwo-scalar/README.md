# Description
Shows a simple timestwo scalar multiplication example. This example
shows how to call generated code taking and returning scalar doubles
can be used from C#, Java, and Python. Run `doitCsharp`, `doitJava`,
and `doitPython` to see the C#, Java, and Python examples,
respectively.

You should see output similar to:

**C#**
```
>> doitCsharp
Evaluating command

    ./timestwoMain.exe

produced output:

Calling initialize
Input = 3
Generated code from MATLAB fprintf: Entering timestwo
Generated code from MATLAB fprintf: Exiting timestwo
Result = 6
Calling terminate
```

**Java**
```
>> doitJava
Evaluating command

    java -Djava.library.path=codegen/dll/timestwo/ -classpath .:timestwoJava timestwoMain

produced output:

Calling initialize
Input = 3.0
Generated code from MATLAB fprintf: Entering timestwo
Generated code from MATLAB fprintf: Exiting timestwo
Result = 6.0
Calling terminate
```

**Python**
```
>> doitPython
Evaluating command

    python timestwoMain.py

produced output:

Calling initialize
Input = 3
Generated code from MATLAB fprintf: Entering timestwo
Generated code from MATLAB fprintf: Exiting timestwo
Result = 6
Calling terminate
```
