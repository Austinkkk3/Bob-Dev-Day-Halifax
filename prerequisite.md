# Prerequisites — AI Government Expense Tracker

Complete prerequisites guide for the AI Government Expense Tracker lab.

---

## System Requirements

- **Operating System**: macOS, Linux, or Windows
- **Python Version**: 3.10, 3.11, 3.12, or 3.13 (recommended)
  - Python 3.14 requires special setup (see below)
- **Internet Connection**: Required for first run (downloads ~2GB of ML models)
- **Disk Space**: At least 5GB free

---

## Installing Python

If you don't have Python installed, follow these steps:

**Mac:**
1. Go to [python.org/downloads](https://python.org/downloads).
2. Click **Download Python 3.13.x** (the big yellow button).
3. Open the downloaded `.pkg` file and follow the installer.
4. When done, open Terminal and run `python3 --version` to confirm.

**Windows**:
1. Go to [python.org/downloads](https://python.org/downloads, Download and install Python Install Manager.
2. Open Python Install Manager when installation is complete.
3. In the Python Install Manager window, run:

   ```bash
   py install 3.13
   ```

4. Wait for Python 3.13 to finish installing.
5. Open Command Prompt and run:

   ```bash
   py -3.13 --version
   ```

6. If the command is not recognized, add Python to your PATH:
   - Open **Edit the system environment variables**.
   - Click **Environment Variables**.
   - Edit the **Path** variable.
   - Add the Python installation directory and Scripts directory.
   - restart your device.
7. Open a new Command Prompt and run:

   ```bash
   py -3.13 --version
   ```

   to confirm the installation

> **Note for Python 3.14 users:** If you already have Python 3.14 installed, you must still install Python 3.13 using the steps above. When running scripts, always use:

```bash
py -3.13 YOURFILE.py
```

instead of:

```bash
python YOURFILE.py
```

or:

```bash
py YOURFILE.py
```

to ensure Python 3.13 is used.

> 💡 pip comes bundled with Python 3.13. If `pip3 --version` gives an error,
> run `python3 -m ensurepip` to install it.

---

## Installing IBM Bob

1. Search for IBM Bob online.
2. Download the IBM Bob installer for your operating system.
3. Open the installer and follow the prompts.
4. Launch Bob — you should see the Bob IDE with the chat panel on the right.


## Ready to Start

Once you have completed all the prerequisites above, you're ready to begin building your AI Government Expense Tracker!

👉 **[Continue to LAB1.md →](LAB1.md)**
