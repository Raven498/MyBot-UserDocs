This website is intended to help end users understand the various services and commands MyBot provides. If you are a developer attempting to access MyBot technical docs, you can find them here:

## Introduction
MyBot is a Discord bot that provides various "subservices" involving music, server moderation/management, an RPG text game, etc. MyBot provides many commands to use these services, so this website serves as a reference for users to look up commands and understand what they do. This website organizes all of our commands into the subservices they are a part of and provides detailed information regarding their proper use and functionality.

MyBot's command prefix is `*`. If you are plugging in more than one word for any parameter, make sure to enclose the words in double quotes. (`""`). 

## Music
__*playtube:__ Joins the command author's VC (if they are in one) and plays the requested audio from Youtube. 

Parameters:
1. query: Search terms for a Youtube video
2. loopChoice: Loop mode (loopOn: plays audio until stopped, loopOff: plays audio only once)

EX: *playtube "batman theme song" loopOn

__*pause:__ Pauses any audio currently playing.
EX: *pause

__*resume:__ Resumes any audio currently paused.
EX: *resume

__*stop__: Stops playing any audio currently playing and leaves the loop if it is in one.
EX: *stop

__*dc__: Disconnects from the voice channel it is currently in
EX: *dc

__*add__: Adds song title to the user's playlist

Parameters:
1. song: Title of the song that needs to be added

EX: *add "batman theme song"

__*delete__: Deletes a song title from the user's playlist if it exists

Parameters:
1. song: Title of the song that needs to be deleted

EX: *delete "batman theme song"

__*playlist__: Prints all songs in the user's playlist
EX: *playlist

__*singleplay__: Plays one requested song from the user's playlist
Parameters:
1. song: Title of the song to be played
2. loopMode: User's loop choice (same as the `loopChoice` parameter for `playtube`)

EX: *singleplay "batman theme song" loopOn

__*shuffleplay__: Plays random songs from the user's playlist (shuffle mode)
EX: *shuffleplay

__*listplay__: Plays all songs in the playlist in order (list mode)

Parameters:
1. loopMode: User's loop choice (same as the `loopChoice` parameter for `playtube`)

EX: *listplay loopOn

## RPG

## Memes

## Moderation/Management

## ChatBot

## Calculator
