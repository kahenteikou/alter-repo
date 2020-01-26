# 概要
AlterLinux用のリポジトリです。

# 使用方法
ArchLinuxとの互換性があります。
`pacman.conf`に以下を追記してください。

```bash
[alter-stable]
Server = https://osdn.net/projects/serene/storage/repo/alter-stable/$arch
SigLevel = Optional TrustAll
```
