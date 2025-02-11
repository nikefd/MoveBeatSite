# MoveBeatSite 🎵

MoveBeatSite 存储用于 MoveBeat 应用的音乐文件。所有音乐存放在 `music/` 目录，并通过 **jsDelivr** 进行下载。

## 📌 音乐来源
所有音乐均下载自 [Pixabay Music](https://pixabay.com/music/) 并符合 **Pixabay License** 许可。

## 📁 目录结构
```plaintext
MoveBeatSite/
│── music/                 # 存储所有音乐文件
│   ├── track1.mp3
│   ├── track2.mp3
│   ├── track3.mp3
│   ├── ...更多音乐文件
│   ├── music_list.json    # 存储所有音乐的列表，供 App 使用
│── README.md              # 项目说明文档
```

## 📜 music_list.json
存储音乐列表的 JSON 文件，格式如下：
```json
[
  {
    "title": "Track 1",
    "url": "https://cdn.jsdelivr.net/gh/your-username/MoveBeatSite@main/music/track1.mp3"
  },
  {
    "title": "Track 2",
    "url": "https://cdn.jsdelivr.net/gh/your-username/MoveBeatSite@main/music/track2.mp3"
  }
]
