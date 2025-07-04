# -FILE-INTEGRITY-CHECKER
*COMPANY* : CODETECH IT SOLUTIONS

*NAME* : N.REEMA OPHIR GEORGE

*INTERN ID* : CT04DL106

*DOMAIN* : CYBER SECURITY

*DURATION* : 4WEEKS

*MENTOR* : NEELA SANTOSH

Description:This project is a File Integrity Checker implemented in Python, designed to monitor and verify the integrity of files in a directory. It helps detect whether files have been modified, deleted, or remain unchanged by comparing their current state with previously saved hash values. The script calculates the SHA-256 hash of each file and stores the results in a JSON file (hashes.json) for later verification. When checking integrity, it reads the saved hashes and scans the folder again to report any changes, such as modified content, missing files, or files that remain intact. This tool is particularly useful for identifying unauthorized changes, monitoring sensitive files, or maintaining the integrity of important directories.

The program is written using Python 3 and utilizes built-in libraries: hashlib for computing SHA-256 hashes, os for directory traversal and file operations, and json for saving and reading the hash data in a structured format. No external libraries are required, making it lightweight and easy to use. The script is interactive and runs through a simple command-line interface (CLI) with a menu-driven approach. It supports large files by reading them in chunks during hashing to prevent memory issues.

For development and testing, the Python IDLE environment was used, ensuring compatibility with beginners and providing a straightforward setup. This project demonstrates how Python’s standard libraries can be combined to build a practical file-monitoring utility that is platform-independent and efficient. To use it, simply run the script in IDLE or terminal, choose the option to save hashes or check integrity, and follow the prompts. This tool showcases the power of Python for creating security-focused utilities without the need for complex frameworks or dependencies.

*OUTPUT* : ![Image](https://github.com/user-attachments/assets/7bb32f25-3b38-4178-a732-7bc7c0d0e1d8)
