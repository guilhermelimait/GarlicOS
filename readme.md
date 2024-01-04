On your TF1 SD card, you will need to have access to modify the following files:

Background Images
LCD 640x480 (use own folder lcd)
HDMI 1280x720 (use own folder hdmi)

- Path: linuxrootfs/mnt/vendor/res/wallpapers/
- Names: 0.jpeg, 1.jpeg, 2.jpeg, 3.jpeg

Theme Images
- Path: linuxrootfs/mnt/vendor/res/theme/
- Folders:
-- Numbered 0-9
has hdmi (160x160) and lcd (120x120) folders
uses .png files numbered 0-5
0- Game Rooms
1- Retroarch
2- Favorites
3- History
4- Search
5- Settings

Anbernic Boot Logo (Primary Boot Screen)
-Path: Volumn/
--bootlogo.bmp (640x480)

Anbernic Boot Logo (Second Screen)
-Path: linuxrootfs/mnt/vendor/res/boot/
--logo.png (640x480)

Anbernic Boot Logo (Reset to go back to main screen from game)
-Path: linuxrootfs/mnt/vendor/res/loading/
--loading.png (640x480)

Shutdown Image
-Path: linuxrootfs/mnt/vendor/res/shutdown/
--Name: lcd.jpg
--Size: 640x480

--Name: hdmi.jpg
--Size: 1280x720

Font
-Path: linuxrootfs/mnt/vendor/bin/
--.ttf format
