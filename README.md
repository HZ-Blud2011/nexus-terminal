# NEXUS — Terminal App Control Center 🖥️

A small terminal-based application launcher for Linux.

I made NEXUS because I thought it would be cool to have an app menu that just lives inside the terminal.

It's written in **Python** using `curses`. NEXUS scans the `.desktop` files on your system, finds installed applications, and lets you search, view information, and launch them directly from the terminal.

I'm 15, and this is mainly a learning project. I had a lot of fun building it and making it feel like a tiny desktop environment inside the terminal.

I also used **ChatGPT and Firefox** to help me figure things out while making it.

## ✨ Features

* 🔎 Scans installed applications
* 📂 Finds `.desktop` files
* 🔍 Search
* ℹ️ Application information
* 🚀 Launch applications with Enter
* 🔄 Rescan applications
* ⌨️ Keyboard navigation
* 🖥️ Runs completely in the terminal
* 📦 Uses Python's standard library
* 🐧 Designed for Linux

## 🎮 Controls

| Key       | Action                  |
| --------- | ----------------------- |
| `↑ / ↓`   | Navigate                |
| `J / K`   | Navigate                |
| `Enter`   | Launch application      |
| `/`       | Search                  |
| `I`       | Application information |
| `R`       | Rescan applications     |
| `H` / `?` | Help                    |
| `Esc`     | Clear search / exit     |
| `Q`       | Quit                    |

## 📦 Installation

### Requirements

* Linux
* Python 3
* A terminal with `curses` support
* No external Python packages required

### 1. Create the directory

```bash
mkdir -p ~/.local/bin
```

### 2. Download or copy the NEXUS script

Save the script as:

```text
~/.local/bin/nexus
```

Or create it with:

```bash
nano ~/.local/bin/nexus
```

Paste the NEXUS code into Nano.

Save with:

```text
Ctrl + O
Enter
Ctrl + X
```

### 3. Check the code

Run:

```bash
python3 -m py_compile ~/.local/bin/nexus
```

If nothing appears, the syntax check passed.

### 4. Make it executable

```bash
chmod +x ~/.local/bin/nexus
```

### 5. Run NEXUS

```bash
python3 ~/.local/bin/nexus
```

If `~/.local/bin` is already in your PATH, you can simply run:

```bash
nexus
```

## 🖥️ My Setup

* **OS:** Linux Mint XFCE
* **Terminal:** Kitty
* **Language:** Python
* **Interface:** `curses`

I use Kitty Terminal btw. 😎

## 💡 Why I Made It

I wanted to experiment with Python, terminal interfaces, Linux `.desktop` files, and process launching.

The idea was basically:

**"What if my terminal had its own little application menu?"**

So I made NEXUS.

## 🚧 Future Ideas

Some things I might add:

* 🎨 More themes
* ⭐ Favorites
* 📁 Application categories
* ⚙️ Settings
* 🔧 Better `.desktop` file support
* 🖼️ Application icons
* 📊 More application information

## 📜 License

This project is mainly a learning project. Feel free to look through the code and learn from it.
