# MyGrep - Lightweight Grep-like Script

Welcome to the **MyGrep** project!

## Overview
This repository contains a simple Bash script that acts similarly to the `grep` command.
It allows users to search for a string inside a text file with optional flags.

## Features
- Case-insensitive search (default).
- `-n` : Display line numbers for matching lines.
- `-v` : Invert the match (show lines that do **not** match).
- `--help` : Show usage/help information.
- Supports combined flags like `-vn` or `-nv`.

## Getting Started

### Prerequisites
- Bash (any Unix/Linux system should work).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mygrep.git
   cd mygrep
   ```

2. Make the script executable:
   ```bash
   chmod +x mygrep.sh
   ```

3. (Optional) Move it to your PATH:
   ```bash
   sudo mv mygrep.sh /usr/local/bin/mygrep
   ```

### Usage
```bash
mygrep [options] <search_string> <file>
```

Example:
```bash
mygrep -n "error" logfile.txt
```

### Help
Display usage information:
```bash
mygrep --help
```

## Contribution
Pull requests are welcome! Feel free to open issues or suggest features.

## License
This project is licensed under the MIT License.
