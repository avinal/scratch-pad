# Scratch Pad

Creating a simple text editor in C.

## How to compile and run

There are no dependencies other than a working C compiler. All the headers used are mostly present by default on any linux system.

- Either GCC or Clang
- Make

Run:

```bash
git clone https://github.com/avinal/scratch-pad.git
cd scratch-pad
make
```

## Usage

### Editing

- Create a new file and edit.

    ```bash
    ./scratch
    ```

- Edit an exisiting file

    ```bash
    ./scratch <file-name>
    ```

### Keybindings

| Actions | Key Combination |
| --- | --- |
| Close the editor | `CTRL+X` |
| Save the modification | `CTRL+S` |
| Delete a character | `Backspace`, `Delete`, `CTRL+H` |
| The usual | `Arrows`, `Home`, `End`, 'Page Up/Down' |

## Features

Nothing more than being able to edit text files.

## Acknowledgement

- [Build your own text editor](https://viewsourcecode.org/snaptoken/kilo/index.html) by Paige Ruten
- [Kilo Editor](https://github.com/antirez/kilo) by Salvatore Sanfilippo aka antirez
