# Bash Scripting Practice: Five Mini-Programs

A collection of interactive shell scripts built while learning Bash scripting fundamentals, parameter expansion, loops, and control flow.

## 🛠️ Concepts Practiced
- Positional parameters & argument parsing (`$1`, `$#`)
- Conditional logic & regex matching (`[[ $var =~ \?$ ]]`, `[[ -z $var ]]`)
- Loops (`until`, `while`) and standard input (`read`)
- Array indexing and arithmetic expansion (`$(( RANDOM % 6 ))`)
- File permissions and executable scripts (`chmod +x`)

## 📂 Programs Included
1. **Questionnaire (`questionnaire.sh`)**: Interactive CLI form capturing user input.
2. **Countdown Timer (`countdown.sh`)**: Recursive / loop-based timer utilizing passed arguments.
3. **Bingo Generator (`bingo.sh`)**: Random letter-number picker using Bash arrays.
4. **Fortune Teller (`fortune.sh`)**: Validates user questions with regex before returning randomized fortunes.
5. **Master Runner (`five.sh`)**: Orchestrates and executes all four sub-programs sequentially.

## 🚀 How to Run

```bash
git clone [https://github.com/JerichElano/bash-scripting-practice.git](https://github.com/JerichElano/bash-scripting-practice.git)
cd bash-scripting-practice
chmod +x *.sh
./five.sh
```
