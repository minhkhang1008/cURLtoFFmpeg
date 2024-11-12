# cURL to FFmpeg
- In most website we watch video, they all use a video player
- We can extract the m3u8 information in Developer tools - Network tab (F12 or Inspect on Right Click)
- This website can help you to convert from cURL to FFmpeg command and all you need to do is paste that into terminal (or Command Prompt) and wait for the video to be installed

# How to use (please follow all steps)
1. You need FFmpeg installed in your computer
   
[Download FFmpeg from their website](https://www.ffmpeg.org/download.html) 

2. Open the page where you want to download, click F12 (or right click and click Inspect) to open Developer tools, then open tab Networks

![tuto1](https://github.com/user-attachments/assets/a9ab1049-f6ec-4b12-a066-bae98e38c2ff)

3. Reload the page, then start the video, search for m3u or m3u8 on the filter in Developer tools
4. Once you've found master or index.m3u8, right click and choose Copy -- Copy as cURL
   
<img width="559" alt="Ảnh màn hình 2024-11-12 lúc 23 41 11" src="https://github.com/user-attachments/assets/024d92fb-fa25-4a7c-b221-f7a4201f44ff">

5. Go to [this website](https://curltoffmpeg.vercel.app/), paste the cURL in, write your desired name and file extension (mp4/mov/mkv)
6. Click Convert then copy command

<img width="655" alt="Ảnh màn hình 2024-11-12 lúc 23 52 07" src="https://github.com/user-attachments/assets/6d2e7cc7-d67c-4b37-969b-463b6a7a36c1">

8. Open your terminal (Command Prompt), paste the FFmpeg command into it and click enter
9. Wait for it to download (it will download into the folder you are running on terminal, so make sure to change the directory before pasting the FFmpeg command (e.g: ```cd Downloads``` )

<img width="571" alt="Ảnh màn hình 2024-11-12 lúc 23 53 17" src="https://github.com/user-attachments/assets/c1f445ac-dec0-464f-a541-fa09251bedf9">

If everything runs fine, you will end up with your favorite movie - right inside your computer!

<img width="152" alt="Ảnh màn hình 2024-11-12 lúc 23 53 47" src="https://github.com/user-attachments/assets/0c45d091-b993-434a-a5c2-728aadc5f207">
