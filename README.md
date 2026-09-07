<!--
╔══════════════════════════════════════════════════════════════════╗
║  ███████╗██╗   ██╗███████╗████████╗███████╗███╗   ███╗        ║
║  ██╔════╝╚██╗ ██╔╝██╔════╝╚══██╔══╝██╔════╝████╗ ████║        ║
║  ███████╗ ╚████╔╝ ███████╗   ██║   █████╗  ██╔████╔██║        ║
║  ╚════██║  ╚██╔╝  ╚════██║   ██║   ██╔══╝  ██║╚██╔╝██║        ║
║  ███████║   ██║   ███████║   ██║   ███████╗██║ ╚═╝ ██║        ║
║  ╚══════╝   ╚═╝   ╚══════╝   ╚═╝   ╚══════╝╚═╝     ╚═╝        ║
╚══════════════════════════════════════════════════════════════════╝
-->

<div align="center">

# 🐍 PYTHON REFERENCE GUIDE
# Google Cybersecurity Certificate

> *Complete Python reference guide covering comments, conditionals, loops, functions, regex, file operations, and parsing.*

[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red.svg)](https://github.com/iqramaaqsoodmughal363)
[![Course](https://img.shields.io/badge/Course-Google%20Cybersecurity-blue.svg)](https://github.com/iqramaaqsoodmughal363)
[![Python](https://img.shields.io/badge/Python-3.x-yellow.svg)](https://github.com/iqramaaqsoodmughal363)
[![Status](https://img.shields.io/badge/Status-Complete-brightgreen.svg)](https://github.com/iqramaaqsoodmughal363)

</div>

---

## 📋 Overview

This reference guide covers all essential Python concepts from the **Google Cybersecurity Certificate** program. It is designed as a quick reference for students and professionals working with Python in cybersecurity contexts.

**Topics Covered:**
- Comments
- Conditional Statements
- Iterative Statements
- User-Defined Functions
- Built-in Functions
- Importing Modules and Libraries
- String Methods
- List Methods
- Additional Syntax for Strings and Lists
- Regular Expressions (Regex)
- File Operations
- Parsing

---

## 📚 Topics Covered

| # | Topic | Key Focus |
|:-:|:---|:---|
| 1 | **Comments** | `#`, `""" """` (docstrings) |
| 2 | **Conditional Statements** | `if`, `elif`, `else`, `and`, `or`, `not` |
| 3 | **Iterative Statements** | `for`, `while`, `break`, `continue` |
| 4 | **User-Defined Functions** | `def`, `return` |
| 5 | **Built-in Functions** | `print()`, `type()`, `range()`, `max()`, `min()`, `sorted()`, `str()`, `len()` |
| 6 | **Modules & Libraries** | `import`, `from ... import ...` |
| 7 | **String Methods** | `.upper()`, `.lower()`, `.index()` |
| 8 | **List Methods** | `.insert()`, `.remove()`, `.append()`, `.index()` |
| 9 | **String/List Syntax** | Concatenation (`+`), Bracket Notation (`[]`) |
| 10 | **Regular Expressions** | `re.findall()`, `\w`, `.`, `\d`, `\s`, `\.`, `+`, `*`, `{}` |
| 11 | **File Operations** | `with`, `open()`, `as`, `.read()`, `.write()` |
| 12 | **Parsing** | `.split()`, `.join()` |

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/iqramaaqsoodmughal363/python-reference-guide-google-cybersecurity.git

# Open the reference guide
open python_reference_guide.pdf
## 📖 Detailed Reference

### Comments
| Syntax | Purpose | Example |
| :--- | :--- | :--- |
| `#` | Single-line comment | `# Print approved usernames` |
| `""" """` | Multi-line comment (docstring) | `"""This function estimates attempts."""` |

### Conditional Statements
| Keyword/Operator | Purpose | Example |
| :--- | :--- | :--- |
| `if` | Starts a conditional statement | `if user in approved_list:` |
| `elif` | Checks another condition | `elif status == 500:` |
| `else` | Executes when all conditions are False | `else:` |
| `and` | Both conditions must be True | `if user == "bmoreno" and attempts < 5:` |
| `or` | At least one condition must be True | `if status == 100 or status == 102:` |
| `not` | Negates a condition | `if not account_status == "removed":` |

### Iterative Statements
| Keyword | Purpose | Example |
| :--- | :--- | :--- |
| `for` | Iterates through a sequence | `for username in ["bmoreno", "tshah"]:` |
| `while` | Iterates based on a condition | `while login_attempts < 5:` |
| `break` | Exits a loop | `break` |
| `continue` | Skips to next iteration | `continue` |

### User-Defined Functions
| Keyword | Purpose | Example |
| :--- | :--- | :--- |
| `def` | Defines a function | `def greet_employee():` |
| `return` | Returns a value from a function | `return fail_percentage` |

### Built-in Functions
| Function | Purpose | Example |
| :--- | :--- | :--- |
| `print()` | Outputs to screen | `print("Login success")` |
| `type()` | Returns data type | `type(51.1)` → `float` |
| `range()` | Generates a sequence | `range(0, 5, 1)` → `0,1,2,3,4` |
| `max()` | Returns largest value | `max(10, 15, 5)` → `15` |
| `min()` | Returns smallest value | `min(10, 15, 5)` → `5` |
| `sorted()` | Sorts a list | `sorted([10, 15, 5])` → `[5,10,15]` |
| `str()` | Converts to string | `str(10)` → `"10"` |
| `len()` | Returns length | `len("security")` → `8` |

### Importing Modules
| Syntax | Purpose | Example |
| :--- | :--- | :--- |
| `import` | Imports a module | `import statistics` |
| `from ... import ...` | Imports specific functions | `from statistics import mean, median` |

### String Methods
| Method | Purpose | Example |
| :--- | :--- | :--- |
| `.upper()` | Converts to uppercase | `"Security".upper()` → `"SECURITY"` |
| `.lower()` | Converts to lowercase | `"Security".lower()` → `"security"` |
| `.index()` | Finds first occurrence | `"Security".index("c")` → `2` |

### List Methods
| Method | Purpose | Example |
| :--- | :--- | :--- |
| `.insert()` | Adds at specific index | `list.insert(2, "wjaffrey")` |
| `.remove()` | Removes first occurrence | `list.remove("elarson")` |
| `.append()` | Adds to end | `list.append("btang")` |
| `.index()` | Finds first occurrence | `list.index("tshah")` → `2` |

### Additional Syntax
| Syntax | Purpose | Example |
| :--- | :--- | :--- |
| `+` | Concatenation | `"IT" + "nwp12"` → `"ITnwp12"` |
| `[]` | Bracket notation (indexing) | `"h32rb17"[0]` → `"h"` |
| `[:]` | Slicing | `"h32rb17"[0:3]` → `"h32"` |

### Regular Expressions (`re` module)
| Pattern | Purpose | Example |
| :--- | :--- | :--- |
| `\w` | Alphanumeric + underscore | `re.findall("\w", "a53-32c.E")` → `["a","5","3","3","2","c","E"]` |
| `.` | Any character (including symbols) | `re.findall(".", "a53-32c.E")` |
| `\d` | Digits | `re.findall("\d", "a53-32c.E")` → `["5","3","3","2"]` |
| `\s` | Spaces | `re.findall("\s", "a53-32c .E")` → `[" "]` |
| `\.` | Period character | `re.findall("\.", "a53-32c .E")` → `["."]` |
| `+` | One or more occurrences | `re.findall("\w+", "a53-32c.E")` → `["a53","32c","E"]` |
| `*` | Zero or more occurrences | `re.findall("\w*", "a53-32c.E")` |
| `{n}` | Exactly n occurrences | `re.findall("\w{3}", "a53-32c.E")` → `["a53","32c"]` |

### File Operations
| Function/Keyword | Purpose | Example |
| :--- | :--- | :--- |
| `with` | Manages resources | `with open("logs.txt", "r") as file:` |
| `open()` | Opens a file | `open("login_attempts.txt", "r")` |
| `as` | Assigns a variable | `as file` |
| `.read()` | Reads file content | `file.read()` |
| `.write()` | Writes to file | `file.write("jrafael")` |

**File Modes:**
- `"r"` → Read
- `"w"` → Write (overwrites)
- `"a"` → Append

### Parsing
| Method | Purpose | Example |
| :--- | :--- | :--- |
| `.split()` | Converts string to list | `"a,b,c".split(",")` → `["a","b","c"]` |
| `.join()` | Converts list to string | `",".join(["a","b","c"])` → `"a,b,c"` |

---

## 🛠️ Tools & Technologies Covered

| Category | Tools |
| :--- | :--- |
| **Language** | Python 3.x |
| **Modules** | `re` (Regular Expressions), `statistics` |
| **File Modes** | `r` (read), `w` (write), `a` (append) |
| **Data Types** | String, Integer, Float, Boolean, List |

---

## 📂 File Structure


python-reference-guide-google-cybersecurity/
│
├── 📄 Reference_Guide_Python_concepts_from_Course_7.pdf
├── 📄 Python_concepts_from_module_4.pdf
└── 📄 README.md
---

## 👩‍💻 Author

**Iqra Maqsood Mughal**  
*Software Engineer · Full-Stack Developer · Code Craftsman · Android App Developer · Problem Solver 🚀*

const 💻 = "Code is life";
while (true) { learn(); build(); innovate(); }

📅 Date
September 7, 2026

📄 License
This reference guide is intended for educational and personal study purposes.
