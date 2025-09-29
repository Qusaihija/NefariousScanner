# NefariousScanner
Lightweight interactive fuzzing launcher for ffuf, dirsearch, wfuzz, and gobuster. provides quick menus for common fuzzing modes.

## Install
```
# 1. Save the script to /usr/local/bin and make it executable

sudo chmod +x ./nefs
mv ./nefs /usr/local/bin/nefs

# 2. Run
nefs
```

## Uninstall
```
sudo rm -f /usr/local/bin/nefs
```

## Quick usage
Run nefs and choose a tool + mode from the menu. The script will print the final command and ask y/n before executing.
