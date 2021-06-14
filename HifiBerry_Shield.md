# Step 1
Edit boot configuration
```
sudo nano /boot/config.txt
```

# Step 2
Turn onboard audio off by
removing following line
```
dtparam=audio=on
```

# Step 3
Activate following overlay
```
dtoverlay=hifiberry-dacplus
```

# Step 4
Reboot
