# PE Parser

## Introduction
This project provides a tool for parsing Portable Executable (PE) files on Windows systems. It extracts essential information such as DOS headers, NT headers, section headers, and data directory entries from a given PE file. The tool is useful for understanding the structure and contents of PE files, aiding in analysis, debugging, and development tasks.

## Prerequisites
To compile and use this project, ensure you have:
- A Windows operating system
- A C compiler (e.g., Visual Studio, MinGW, Cygwin)

## Compilation
Follow these steps to compile the project:
1. Open a command prompt.
2. Navigate to the directory containing the source code files.
3. Run the following command to compile the source code:
    ```
    gcc source.c -o pe_parser
    ```
    Replace `gcc` with your C compiler if necessary.

## Usage
Once the project is compiled successfully, you can use it to parse PE files and extract vital information.

### Syntax
```
pe_parser <Path_To_PE_File>
```

### Parameters
- `Path_To_PE_File`: The path to the Portable Executable (PE) file you want to parse.

### Example
```
pe_parser example.exe
```

## Notes
- Ensure that the specified PE file exists and is accessible.
- This tool provides insights into the DOS headers, NT headers, section headers, and data directory entries of the PE file.
- It's designed for educational, analysis, and debugging purposes.
---

## Remaining Tasks

- There are a few additional items that need to be added here, which will be updated at a later time.

--- 

I believe there are better ways to do what I done here. I'm not a C specialist, so I know there's room to improve this code. I'd love to hear your ideas and feedback. 
Don't hesitate to reach out to me. Thanks!


