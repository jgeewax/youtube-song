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

#### libav-tools and lame

```
$ sudo apt install libav-tools lame
```

### Install youtube-song

```
$ curl -O https://raw.githubusercontent.com/jgeewax/youtube-song/master/youtube-song
$ chmod a+x youtube-song
```

## Usage

```
$ youtube-song "https://www.youtube.com/watch?v=dQw4w9WgXcQ" "Avicii - Levels.mp3"
```
