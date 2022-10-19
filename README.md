# iiyama ProLite - Digital Signage Setup

## Setting Custom Boot Animation

1. Render Animation as PNG Sequence 
(1920 x 1080 Recommended for Landscape)
(1080 x 1920 Recommended for Portrait)

2. Rename PNG files in Sequentinal order
e.g. 0001.png, 0002.png .... 0120.png

3. Place this files in a folder named 'part0'

4. (optional) Editing desc.txt
If you need to make changes to the file use the following format:

1920 1080 60
p 1 0 part0


For more details, view Custom Boot Animation.pdf 

5. Add desc.txt & part0 folder to .zip file using 7zip.
Archive Format = zip
Compression Level = Store
Filename = bootanimation.zip

3. Copy 'bootanimation.zip' to USB Drive

4. Power on TV and switch to any source e.g. HDMI 1

5. Press the 'Home Button' then type '1668'

6.  Navigate to Path

Settings => Signage display => General setting => Boot Logo => Choose Boot Animation
Select bootanimation.zip in USB or SD card and press SAVE
bootanimation.zip is saved in '/data/local'

7. Reboot the monitor after the above steps 1 to 5 have bee done.
Make sure that the animation you selected is displayed on start screen.

## Play Video From USB

1. Create Directory on USB
-videos in /signage/video/
-photos in /signage/photo/
-music in /signage/music/

2. Place videos inside /video directory
Example path : /signage/video/VIDEO_1.mp4

Supported fi le system:
FAT32

Supported fi le format:
Music: MP3, WMA, WMA pro, M4A, AAC, LPCM
Video: AVI, MP4, 3GPP, MKV, ASF, VRO VOB, PS, TS
Photo: JPEG, BMP, PNG, GIF

3. Connect USB to Display

4. Load Media Player
Source => Media Player

5. Press Compose
Select "Compose" on the page. First you select one playlist to play between FILE1 and
FILE7.

6. Select the file and select edit or delete e.g FILE1  

<!-- NEED TO COMPLETE -->
