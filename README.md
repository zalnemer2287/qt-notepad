# Qt Notepad

A simple desktop notepad application built with C++ and Qt.

## Features
- Create new text documents
- Open existing files
- Save files
- Basic editing (copy, paste, cut, undo, redo)
- Print support

## Tech Stack
- C++
- Qt Widgets
- Qt Designer
- qmake

## Project Structure
- `main.cpp` – application entry point
- `notepad.cpp / .h` – core application logic
- `notepad.ui` – UI layout (Qt Designer)
- `.pro` file – Qt project configuration

## How to Run

### Option 1 (Recommended)
1. Install Qt and Qt Creator
2. Open the `.pro` file in Qt Creator
3. Configure the project (Desktop Kit)
4. Click Run

### Option 2 (Command Line)
Make sure Qt is installed and available in PATH:

```bash
qmake
make
./QtNotepad
