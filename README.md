# LibreTV 整合直播源

国内外频道合并去重后的 M3U / TXT 播放列表，供 IPTV 播放器（DIYP、TVBox、TiviMate、Kodi 等）使用。

## 文件

| 文件 | 说明 |
| --- | --- |
| `tv.m3u` | **推荐**，同名频道限 3 条线路，分组名纯中文，兼容性最好 |
| `all-channels.m3u` | 全量版，包含所有线路（14641 条） |
| `all-channels.m3u8` | 同上，扩展名为 .m3u8 的副本 |
| `all-channels-lite.m3u` | 精简版，同名限 3 线路 |
| `all-channels.txt` | TXT 格式（频道名,地址 + #genre# 分组） |
| `tv.txt` | TXT 精简版 |
| `test.m3u` | 仅央视 + 卫视，用于排查网络问题 |
