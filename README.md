# Taniya_-CU_22mcc20019-
Certainly! Here is a simple README file for your `internsctl` script:

```markdown
# internsctl - v0.3.0

## Overview

`internsctl` is a custom Linux command designed for managing interns, retrieving system information, and obtaining file details.

## Usage

### Installation

Ensure the script is executable:

```bash
chmod +x internsctl
```

### Commands

- **List Interns:**
  ```bash
  internsctl list
  ```

- **Add Intern:**
  ```bash
  internsctl add <name>
  ```

- **Remove Intern:**
  ```bash
  internsctl remove <name>
  ```

- **Get CPU Information:**
  ```bash
  internsctl cpu getinfo
  ```

- **Get Memory Information:**
  ```bash
  internsctl memory getinfo
  ```

- **Create User:**
  ```bash
  internsctl user create <username>
  ```

- **List Users:**
  ```bash
  internsctl user list
  ```

- **List Sudo Users:**
  ```bash
  internsctl user list --sudo-only
  ```

- **Get File Information:**
  ```bash
  internsctl file getinfo <file-name>
  ```

- **Get Specific File Information:**
  ```bash
  internsctl file getinfo [options] <file-name>
  ```

  Options:
  - `--size, -s`: Print file size.
  - `--permissions, -p`: Print file permissions.
  - `--owner, -o`: Print file owner.
  - `--last-modified, -m`: Print last modified time.

## Examples

- **List all interns:**
  ```bash
  internsctl list
  ```

- **Add a new intern:**
  ```bash
  internsctl add JohnDoe
  ```

- **Get CPU information:**
  ```bash
  internsctl cpu getinfo
  ```

- **Get information about a file:**
  ```bash
  internsctl file getinfo hello.txt
  ```

- **Get specific information about a file:**
  ```bash
  internsctl file getinfo --size hello.txt
  ```

## Options

- `--version`: Display the version of internsctl.
- `--help`: Display help and usage information.

## Author

Taniya.

## Reporting Bugs

Report bugs to: taniyakashyap1110@gmail.com 

## License

This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.
```

