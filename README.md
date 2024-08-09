# QuackBot

QuackBot is bump bot for [pump.fun](https://www.pump.fun). Its free for all wallets that hold 10 000 000 or more [DUCKLEY](https://pump.fun/3FbCDeGKdniHfpKnvmdejsPZvJVzQ13FX85bksvBpump) coin.

In future we will continue to update bot with new features as well as a support for [moonshot](https://dexscreener.com/moonshot).

QUACKBOT IS 3X CHEAPER THAN OTHER BUMP BOTS, SPENDING ONLY AROUND 0.1SOL FOR 30MIN OF WORK! With our recommended settings



---

# Installation Guide on Linux Or Cloud Linux Terminal

This guide will walk you through the steps to install and run `QuackBot.exe` on a Linux system using Wine.

## Prerequisites

Before you start, ensure that you have the following installed on your system:

- **Wine**: A compatibility layer that allows you to run Windows applications on Linux.
- **Internet connection**: To download the necessary packages.

## Installation Steps

### 1. Update Your System

Before installing anything, make sure your system is up to date:

```bash
sudo apt-get update && sudo apt-get upgrade
```

### 2. Add 32-bit Architecture Support

Wine requires 32-bit architecture support to run Windows applications:

```bash
sudo dpkg --add-architecture i386
sudo apt-get update
```

### 3. Install Wine

Now, install Wine along with the necessary 32-bit libraries:

```bash
sudo apt-get install wine32
```

### 4. Verify Wine Installation

To ensure Wine is installed correctly, check the version:

```bash
wine --version
```

You should see the Wine version output, indicating that Wine is installed.

### 5. Navigate to the `QuackBot.exe` Directory

Use the terminal to navigate to the directory containing `QuackBot.exe`:

```bash
cd WIN
```

### 6. Ensure Required Files are Present

Make sure that all necessary files, including `config.json`, are in the correct directory:

```bash
ls
```

You should see `QuackBot.exe` and other required files listed.

### 7. Run `QuackBot.exe`
Make sure the `config.json` file is in the same folder as QuackBot.exe

Finally, use Wine to run `QuackBot.exe`:

```bash
wine ./QuackBot.exe
```

Follow any on-screen instructions to complete the setup or operation.

## Troubleshooting

- **Wine Errors**: If you encounter issues with Wine, ensure you have installed the 32-bit version properly and that all dependencies are met.
- **Missing Files**: If `config.json` or other files are missing, double-check the directory or re-download the necessary files.

## Additional Resources

- [Wine Documentation](https://wiki.winehq.org/Documentation)
- [Linux Terminal Commands](https://www.tldp.org/LDP/abs/html/)

---
