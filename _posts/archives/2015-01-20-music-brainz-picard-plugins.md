---
layout: post
title:  MusicBrainz Picard Plugins
date:   2015-01-20 15:00:00 +0000
categories: music-brainz-picard
---

Hello, I am Nicolas Cenerario and this is my main public repository.
It will contain all my little projects and notes.

## Projects

* **MusicBrainz Picard Plugins**
  * Fake Picard
  * Really Clear Metadata
  * Delete Duplicate Files

## MusicBrainz Picard Plugins

### Fake Picard

This little project is just an fake Picard implementation
so that I can develop my plugin with Picard API without having to build Picard.
It only gives a view of Picard API and should integrate what is available but stay a small as possible.

### Really Clear Metadata

If you enable the "clear existing tags" option, it might happen that in some particular circumstances,
MusicBrainz Picard will not be able to clear all metadata properly from certain files.
This plugin provide a context menu action that allow to clear all metadata from a file or a group of file.

### Delete Duplicate Files

If you are like me, you have a lot of duplicate files on your hard drive.
I'm doing so many backup that in the end, I get a lot of duplicates.
But the time has come to organize my music library and I cannot let duplicates mess up my library.
I want to tag and organize my music so that I can build a clean library.
That's why I developed this plugin.
After adding my files into MusicBrainz Picard, I have a context menu action that find and delete duplicate files.
