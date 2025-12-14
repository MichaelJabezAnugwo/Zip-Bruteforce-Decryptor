What This Project Is About

This is a cybersecurity project where you simulate a real-life situation:
A hacker used ransomware to lock a .zip file. Your job is to write a Python script that tries many possible passwords (from a list) to unlock that file — this is called brute-forcing.


├── bruteforce.py       # This is your Python script that does the brute-force work

├── enc.zip             # This is the encrypted zip file you're trying to unlock

└── wordlist.txt        # This is the list of passwords your script will try


---

## How It Works

The script attempts to extract the contents of `enc.zip` using each password from `wordlist.txt`. It stops when the correct password is found and prints it to the console.

---

## Background

This project was developed as part of the **Forage AIG Cybersecurity Virtual Experience Program**. It demonstrates:

- Brute-force password cracking
- Python scripting for cybersecurity
- Incident response and recovery techniques
- Use of common password wordlists (e.g., RockYou)

---

## Requirements

- Python 3.6+
- No external libraries required (uses Python's built-in `zipfile` module)

---

## Usage

1. Clone the repository or download the files.
2. Place your encrypted `.zip` file and `wordlist.txt` in the same directory as `bruteforce.py`.
3. Run the script:

```bash
python bruteforce.py
