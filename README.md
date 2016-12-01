# KodiBasicTV-NFO
Basic - Minimal NFO file for KODI TV Episodes (for personal videos)

There are times when you might want to add your personal/home videos to your Kodi setup. However, there is no easy way to add these videos to Kodi. When I decided to do the same, I ran into several difficulties as there was no easy way to create the require NFO files that Kodi could use to scarape personal videos. For this reason, I created this utility. 

I am not a programmer by any means so use this utility at your own risk. I am sure a real program would have a ton more error checking and trappy but for this quick utility, I have done none of that. 

A things to note:
- This utility requires that your video files are already appropriately named such as S01E02 (Season 01, Episode 02). A utility such as Advanced Renamer (https://www.advancedrenamer.com/) may be used to rename video files. 
- Ensuring proper file permissions is your responsibility. Utility will try to write the NFO files in the same location as the video files. If it is unable to do so, I am sure it will fall over as there is no error checking in it.
- There is a sample run option included. Use that to see if you are getting what you expect before NFO files are created. This is a good way to see if utility is reading your file names correctly (check the season and episode tags in the log area)
- Utility adds a thumbnail tag in the NFO file as well. It allows the user to add information regarding the thumbnail image file. Typically, it is VideoFileName-thumb.jpg. For example, if video file name is: S01E02.avi and user enters -thumb.jpg then following thumbnail will be added to the NFO file:  S01E02-thumb.jpg. Utility also allows you to select whether you would like the path to the jpg added in the tag. Use this with causion as Kodi may not access the jpg using the same path if drive letters etc. change.
- You can use a utility such as Auto Movie Thumbnailer (https://funk.eu/amt/) to automatically generate thumbnails.

This utility creates basic NFO files; just good enough for Kodi to scrape. 

Use at your own risk.
