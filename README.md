# Python Keylogger – Educational Demonstration

This is a basic keylogger written in Python, created for educational and ethical demonstration purposes only. It captures keystrokes from the keyboard and logs them to a file for analysis or study.

**Important:** This tool should never be used on systems without full permission from the owner. Misuse of this software may be illegal and unethical. This project is intended only for cybersecurity research, personal education, or academic demonstration.

---

## Features

- Captures all keystrokes
- Logs output to `log.txt` and/or `keyfile.txt`
- Lightweight and simple design
- Includes basic detector code (`keylogdetector`) to demonstrate detection concepts

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/keyylog.git
cd keyylog
```

2. Install dependencies (if any are required):

This project uses only standard libraries (`pynput` may be required):

```bash
pip install pynput
```

---

## Usage

To start the keylogger, run:

```bash
python3 main.py
```

It will begin capturing keystrokes in the background and save them to `log.txt`.

You can also explore:

- `keylogger.py` – core logging logic
- `log.py` – handles writing to the log
- `keylogsup.py` – support code or setup logic

---

## Output

Captured keystrokes are saved in one or both of the following files:

- `log.txt`
- `keyfile.txt`

Each entry records the exact keys pressed in the order received.

---

## Keylogger Detector (Demo)

The `keylogdetector/` folder contains sample code meant to simulate detection of keyloggers. This is for those interested in learning about basic behavioral detection techniques.

---

## Folder Structure

```
keyylog/
├── main.py                # Entry point
├── keylogger.py           # Logging logic
├── log.py                 # File writing
├── keylogsup.py           # Support utilities
├── log.txt                # Output log
├── keyfile.txt            # Alternative output
├── keyloghas.code-workspace
├── keylogdetector/
│   ├── main.py
│   └── tempCodeRunnerFile.py
├── .idea/                 # (IDE config, can be ignored or .gitignored)
```

---

## Disclaimer

This project is intended **only for ethical, legal, and educational use**. Do not run this code on machines you do not own or without explicit permission. The author takes no responsibility for any misuse.

---

## License

MIT License (or specify another license if needed)

---

## Author

[Owais abdul haseeb]

