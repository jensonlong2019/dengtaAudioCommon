# 灯塔公共媒体库

公共音频从灯塔应用「公共音频 → 同步远端」双向合并；视频与独立 MP3 分类预留扩展。

manifest.json 使用 kind=shared-media-library、schemaVersion=1。音频文件位于 audio/{id}/audio.{ext}，只同步资源，不上传数据库、项目或身份凭据。删除先仅影响本地；两端同时改名会提示冲突。
