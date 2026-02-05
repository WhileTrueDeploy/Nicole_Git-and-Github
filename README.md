# Nicole_Git-and-Github
Tracking the course on cousera

# Quiz Reflection: Diff, Patch, and Script Execution

## 📘 Overview
This README documents the key concepts learned from a quiz focused on file comparison tools, patching workflows, and script execution behavior in Python. The quiz emphasized practical command-line skills used in collaborative software development.

## 🛠️ Key Learnings

### 1. Creating and Sharing Code Changes
When fixing bugs, it is good practice to work on a modified copy of the original file. The `diff` command is used to compare the original file and the modified version, producing a `.diff` file that captures only the changes made. This makes it easy to share fixes without sending entire files.

### 2. Applying Changes with Patch
The `patch` command applies changes described in a diff file to the original file. To use `patch`, both the original file and the corresponding diff file are required. This ensures consistent and accurate updates across different systems.

### 3. Comparing Files Effectively
The quiz highlighted different comparison tools:
- `diff` and `diff -u` compare files line by line.
- `wdiff` compares files word by word, making it useful for identifying small textual changes within lines.

### 4. Controlling Script Exit Values
Python scripts communicate success or failure through exit codes. Instead of using `return` outside a function, scripts should use `sys.exit()` to define exit values. This is especially important for automation and monitoring scripts.


