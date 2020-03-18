# youtube-song

Download music from YouTube
and convert it to an MP3 file.

## Installation

### Dependencies

#### youtube-dl

Install via apt:

```
$ sudo apt install youtube-dl
```

Install via pip3

```
$ sudo pip3 install -U youtube-dl
```

#### ffmpeg and lame

```
$ sudo apt install ffmpeg lame
```

### Install youtube-song

```
$ curl -O https://raw.githubusercontent.com/jgeewax/youtube-song/master/youtube-song
$ chmod a+x youtube-song
$ # Optional
$ sudo mv youtube-song /usr/local/bin/
```

## Usage

```
$ youtube-song "https://www.youtube.com/watch?v=dQw4w9WgXcQ" "Avicii - Levels.mp3"
```
