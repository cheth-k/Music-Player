# Music Player Project

## Project Breakdwon
```
your-project/
├── index.html
├── style.css
├── songs/
│   ├── song-1.mp3
│   ├── song-2.mp3
│   └── ...
├── images/
│   ├── song-1.jpg
│   ├── song-2.jpg
│   └── ...
└── js/
    ├── music-list.js
    └── script.js
```

## Usage
- Add your songs (`.mp3` files) to the `songs/` folder.
- Add corresponding album art (`.jpg` files) to the `images/` folder.
- Update the playlist in `js/music-list.js`:
  ```javascript
  const musicList = [
    {
      name: "Song 1",
      artist: "Artist 1",
      img: "song-1.jpg",
      src: "song-1.mp3"
    },
    {
      name: "Song 2",
      artist: "Artist 2",
      img: "song-2.jpg",
      src: "song-2.mp3"
    }
  ];
  ```
