
# File Shuffler and Organizer

A Rust utility for shuffling, renaming, and modifying file timestamps in directories. Ideal for dataset preparation and file organization workflows.

## Features
- **Shuffle and Rename**: Randomly renames files in directories (e.g., `001.csv`, `002.csv`).
- **Recursive Processing**: Handles directories and their subdirectories.
- **Timestamp Modification**: Adds randomized timestamps to files.
- **Automation**: Supports manual, periodic (e.g., 30 seconds), or weekly automation.
- **Error Logging**: Detailed logging and error handling for all operations.

## Installation
### Step 1: Install Rust
[Download Rust](https://www.rust-lang.org/tools/install).

### Step 2: Clone Repository
```bash
git clone https://github.com/windwalker46/File-shuffler-rust.git
cd File-shuffler-rust
```

### Step 3: Build the Project
```
cargo build --release
```

## Usage
### Running the Program
```
cargo run --release
```

### Path Configuration
- **Default Paths**
- **Alternate Paths**: `C:\data`
- **Custom Paths**: Specify paths manually.

### Operation Modes
- **Manual Shuffle**: Process files once.
- **Periodic Runs**: Shuffle every 30 seconds.
- **Weekly Runs**: Automate weekly processing.

### Actions
- Shuffles files, renames them sequentially.
- Modifies timestamps to simulate recent activity.

## Example Workflow
1. Select custom paths and run in periodic mode:
```
cargo run --release
```
2. Monitor shuffled files and logs for results.

## Contributors
- Ben Tran
- Justin Halvorson
- Daniel Leone
