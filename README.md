# Lyrics Bingo

### *Description:* ###

Generates lyric bingo sheets in a 5x5 grid based off scraped lyrics from a playlist. 
Uses the 250 most common words to create "bingo" sheets and puts them randomly in the grid.

*Not to be used to download music lyrics illegally!*

### *Why:* ###
Lyrics bingo can be a fun way to learn a language at a bar or something. It's not actually
as much fun as it seemed when I wrote this script, but whatever.

### *Instructions:* ###

0. Clone this repo:
```
$ git clone https://github.com/HarryMaher/LyricsBingo.git
```
1. Install BeautifulSoup4 and docx "pip3 install packagename"
2. Put Artist - Song Name into a playlist.txt separated by line breaks. Or copy a spotify playlist into playlist.txt it from: http://spotlistr.herokuapp.com/#/export/spotify-playlist 
3. Run this "python bingomaker.py [bingo grids]" where [bingo grids] is the number of bingo grids you want output (takes at least 3 seconds per song)
4. Check out out.txt because the word counts are kind of interesting.
5. Print the bingo squares out, call your friends, queue up the playlist, and enjoy!
- It plays like normal bingo, cross out the word when you hear it in the song. When you get 5 in any direction you win.

Note: It won't find obscure lyrics, and won't work for every song on your playlist. Read the output to see which songs weren't found.
