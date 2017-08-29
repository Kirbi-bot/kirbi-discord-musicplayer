# kirbi-discord-musicplayer module
A module for [Kirbi](https://github.com/richardson-media-house/kirbi), for playing music in voice channels on your Discord server.

Depends on [kirbi-discord](https://github.com/Richardson-Media-House/kirbi-discord).

## Usage

- !play <search terms|URL> => Plays the given video in the user's voice channel. Supports YouTube and many others: <http://rg3.github.io/youtube-dl/supportedsites.html>.
- !skip => skips track.
- !queue => prints the current music queue for this server.
- !dequeue <index> => Dequeues the given song index from the song queue.
- !pause => pauses music playback.
- !resume => resumes music playback.
- !volume <volume|volume%|volume dB> => set music playback volume as a fraction, a percent, or in dB.
