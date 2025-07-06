# Suckless Tools Collection

This repository contains a collection of suckless software tools - minimalist, functional, and efficient Unix utilities.

## Included Tools

### dmenu
Dynamic menu for X - a fast and lightweight menu application for selecting from a list of options.

### dwm
Dynamic window manager for X - a tiling window manager that is extremely lightweight and customizable.

### st
Simple terminal - a minimalist terminal emulator for X with a focus on simplicity, clarity and frugality.

### surf
Simple web browser - a minimalist web browser based on WebKit/GTK+.

## Building and Installation

Each tool can be built independently. Navigate to the respective directory and run:

```bash
make
sudo make install
```

## Configuration

Each tool uses a `config.h` file for configuration. To customize:

1. Copy `config.def.h` to `config.h` (if not already present)
2. Edit `config.h` with your preferred settings
3. Rebuild the tool with `make clean && make`

## Documentation

Each tool includes man pages and additional documentation:
- Use `man toolname` after installation
- Check individual README files in each directory
- Refer to [suckless.org](https://suckless.org) for detailed documentation

## Philosophy

These tools follow the suckless philosophy:
- Clarity, frugality, and readability over features
- Source code under 2000 SLOC when possible
- Customization through editing source code rather than runtime configuration

## License

Each tool is released under its own license. Check the LICENSE file in each directory for details. 