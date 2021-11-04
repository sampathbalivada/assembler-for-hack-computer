# Assembler for Hack Computer

An assembler that compiles Hack Computers' Assembly (.asm) file to Hack Computer Machine Code. This project is done as a part of the Nand2Tetris course on Coursera.

The Hack computer is a virtual computer built as a part of the course to build an understanding about the inner workings of a modern computer.

For more information please visit [nand2tetris.org](https://nand2tetris.org).

> Note: Please be advised that the file in this repository is a compiled assembler and does not contain the source code.


### Running the assembler

Linux/MacOS:

```bash
# change directory to the assembler.pyc location

chmod 500 assembler.pyc && python3 assembler.pyc
```

Windows (Powershell):

```ps
# change directory to the assembler.pyc location

.\assembler.pyc
```
OR
```ps
# change directory to the assembler.pyc location

python.exe .\assembler.pyc
```

### Usage

The assembly file path can be supplied in the command line arguements 

```bash
python3 assembler.pyc [path/to/file.asm]
```

(OR)

the program will ask for a file location if the argument is not supplied
```bash
python3 assembler.pyc
# Output:
# Enter file location:
```

The machine code for the given assembly code is written to `path/to/file.asm.output.hack` after the execution.

### Areas of improvement

- Implement a better parser. Preferably using Abstract Syntax Trees.
- Implement better anomaly detection and handling.  
- Add verbose syntax error messages.
