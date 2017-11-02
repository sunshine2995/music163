# music163
## music163 spider

> 爬取网易云音乐的所有的歌曲的评论数的爬虫

- 爬取所有的歌手信息(music_163/artists.py)

- 根据上一步爬取到的歌手信息去爬取所有的专辑信息(music_163/album_by_artist.py)

- 根据专辑信息爬取所有的歌曲信息(music_163/music_by_album.py)

- 根据歌曲信息爬取其评论条数(music_163/comments_by_music.py)

- 数据库相关的语句都存放于(music_163/sql.py)中
