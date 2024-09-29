# Open Source SW - Lab 4 Report  
**Student ID**: 202034941
**Name**: 조세연  

## 1. Introduction to Linux and Shell  
Linux is an open-source operating system consisting of three main components:

- **Kernel**: The core of the OS, managing hardware resources.
- **Shell**: The interface for users to communicate with the kernel.
- **User Space**: Where applications run and users interact.

### 1.1 CLI (Command Line Interface)  
- Requires command memorization.  
- Faster and supports automation.  
- Primarily keyboard-based.  
- Ideal for developers.

### 1.2 GUI (Graphical User Interface)  
- More intuitive for beginners.  
- Slower, requires manual work.  
- Mostly mouse-based.  
- Suited for daily users.

## 2. Accessing the CLI  
- **Linux/MacOS**: Use the built-in Terminal application.  
- **Windows**: Install and use Git Bash.

## 3. Essential Shell Commands  

| Command | Description | Usage Examples |
|---------|-------------|----------------|
| `pwd`   | Print Working Directory | `pwd` |
| `cd`    | Change Directory | `cd Documents`, `cd ..`, `cd ~` |
| `ls`    | List directory contents | `ls`, `ls -l`, `ls -la` |
| `cp`    | Copy files/directories | `cp file1 file2`, `cp -R dir1 dir2` |
| `mv`    | Move/rename files/directories | `mv file1 file2`, `mv file1 dir1` |
| `rm`    | Remove files/directories | `rm file1`, `rm -r dir1` |
| `mkdir` | Make a new directory | `mkdir new_folder` |

## 4. Navigation and Paths  

| Symbol | Meaning |
|--------|---------|
| `/`    | Root directory |
| `.`    | Current directory |
| `..`   | Parent directory |
| `~`    | Home directory |
| `/path/to/dir` | Absolute path |
| `./path/to/dir` | Relative path from current directory |
| `../path/to/dir` | Relative path from parent directory |

## 5. Command Options and Arguments  
Options modify command behavior:

- Example: `ls -lha`

| Option | Description |
|--------|-------------|
| `-l`   | Long format (detailed info) |
| `-a`   | Show all (including hidden files) |
| `-h`   | Human-readable file sizes |
| `-R`   | Recursive (for directories) |
| `-i`   | Interactive mode (asks before overwriting) |

## 6. Wildcards and Patterns  

| Wildcard | Matches |
|----------|---------|
| `*`      | Any number of characters |
| `?`      | A single character |
| `[...]`  | Any character within brackets |

### Examples:
- `*.txt`: All files ending with `.txt`.
- `file?.txt`: Matches `file1.txt`, `file2.txt`, etc.
- `[abc]*`: All files starting with `a`, `b`, or `c`.

## 7. Advanced File Management  

### Copying Files
- `cp source_file destination_file`
- `cp -R source_directory destination_directory`
