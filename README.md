ID3v1Tag
========

This simple command-line tool lets you view, add &amp; update [ID3v1.1](https://en.wikipedia.org/wiki/ID3#ID3v1) tags in MP3 files.

### Usage

	usage: ID3v1Tag FILE_NAME [-h] [-t TITLE] [-a ARTIST] [-A ALBUM] [-y YEAR]
	                     [-c COMMENT] [-n TRACK] [-g GENRE]

	Add, view, and update ID3v1.1 tags in MP3 files.

	positional arguments:
	  FILE_NAME            the file to process

	optional arguments:
	  -h            show this help message and exit
	  -t TITLE      ID3v1 title (maximum length 30)
	  -a ARTIST     ID3v1 artist name (maximum length 30)
	  -A ALBUM      ID3v1 album name (maximum length 30)
	  -y YEAR       ID3v1 year of release (4 characters)
	  -c COMMENT    ID3v1 optional comment (maximum 28 characters)
	  -n TRACK      ID3v1 optional track number (0-255)
	  -g GENRE      ID3v1 see https://en.wikipedia.org/wiki/ID3#List_of_Genres
