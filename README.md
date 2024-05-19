Welcome to YouTube Downloader and Converter, a Python-based application developed by Uditi Shah. 
This tool allows users to download YouTube videos or playlists and convert videos to MP3 format. 

Code Explanation:

Import Statements:
pytube: A Python library for downloading YouTube videos.
youtube_downloader: Custom module for downloading videos and playlists.
file_converter: Custom module for converting video files to MP3.


Choice Handling:
Based on user input, the program executes different functions to download videos or playlists, or to download and convert videos to MP3.


Download Functions:
download_video(url, resolution): Downloads a video at the specified resolution.
download_videos(urls, resolution): Downloads multiple videos.
download_playlist(url, resolution): Downloads all videos in a playlist.


Utility Functions:
choose_resolution(resolution): Maps user-friendly quality descriptions to YouTube itags.
input_links(): Collects multiple video URLs from the user.


Conversion Function:
convert_to_mp3(filename): Converts a downloaded video file to MP3 using moviepy.
