SoundCloud Music Downloader

Tested with OS X 10.8.5 | iTunes 12.3.3 & macOS 10.12.5 | iTunes 12.6.1


1) Open and run the installer in the main folder.

-It will fetch and install:

	Homebrew (If not already installed)
		
	Curl (Can't access SoundClouds website without it)
		
	eyeD3 (Used for modifying ID3 metadata i.e song info, album artwork)
	
It will ask for your password if you don't already have these installed.

2) open Terminal and run 

	SCDL -L (SoundCloud web link here)

		
e.g.
	
	SCDL -L https://soundcloud.com/flume/disclosure-you-me-flume-remix
	
This will download the individual song, get the song album artwork and add it to iTunes.


02/05/2016 Update

·Updated code to work with iTunes 12.3.3+

·Fixed Client ID
	
27/11/2015 Update

·Added option for custom iTunes comment. '-x Comment' (Default is SoundCloud)

·SoundCloud transcode their sounds to 128kbps for streaming, thus all downloaded sounds will be at 128kbps

·Rewritten for iTunes support (Option -s) on OS X only

·Automatically adds downloaded songs to iTunes

·Automatically gets the artist from the song name

·Fixed broken links and client ID for accessing soundcloud api# SoundCloud-Downloader
# SoundCloud-Downloader-OS-X-10.8
