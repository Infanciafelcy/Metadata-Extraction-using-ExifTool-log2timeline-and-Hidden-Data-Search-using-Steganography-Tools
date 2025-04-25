# Metadata-Extraction-using-ExifTool-log2timeline-and-Hidden-Data-Search-using-Steganography-Tools
## AIM:
To extract metadata, perform timeline analysis, and search for hidden data using forensic tools like ExifTool, log2timeline, and steganography detection tools.

## DESIGN STEPS:
### Step 1:
Use exiftool to extract metadata from files such as images, documents, and videos.

### Step 2:
Use log2timeline and plaso to create and analyze event timelines from system logs and file metadata.

### Step 3:
Apply steganography detection tools like steghide, zsteg, or binwalk to uncover hidden data in media files.

## PROGRAM:
Metadata and Timeline Forensics, Steganography Analysis Steps
```
sudo apt update
sudo apt install exiftool -y
```
```
exiftool image.jpg
```
```
exiftool -r /path/to/folder
```

## OUTPUT:
Extracted Metadata, Timeline Events, and Hidden Data Detection Results
![image](https://github.com/user-attachments/assets/97d5609d-16a6-40ed-920f-5006e4ed8bac)
## install log2timeline
```
sudo apt install plaso -y
sudo apt install steghide -y
```
```
steghide extract -sf hidden.jpg

```
![image](https://github.com/user-attachments/assets/a9886672-a99d-49c5-bda1-4c0ffd132b52)
![image](https://github.com/user-attachments/assets/b99c6242-1ecf-4ee7-901d-652d198c21a5)

## Using binwalk – for file analysis
```
sudo apt install binwalk -y
binwalk suspicious.jpg
binwalk /home/kali/Downloads/wallpaper.jpg
```
## RESULT:
Metadata was successfully extracted, timeline analysis was completed, and hidden data was identified using steganography tools.

