# Alfred Spotify Finder ![](https://github.com/yonbergman/alfred_spotify_finder/raw/master/icon.png)

A small Alfred extension that lets you search and play a specific track. You need Powerpack to install extensions.

## Installation

Just double click the extension file

## Download

Download the extension here - [download link](https://github.com/yonbergman/alfred_spotify_finder/raw/master/Spotify%20Finder.alfredextension)

## Usage

        play [track name] - searches the Spotify API for that track and plays it using AppleScript


## Development

This is a Ruby extension, to enable it to run you need to wrap the ruby file `run.rb` into a shell script.
The `wrap.rb` file does that, it wraps the `run.rb` script with a shell that lets it be run under alfred extensions
