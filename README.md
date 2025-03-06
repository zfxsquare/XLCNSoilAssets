## Intergrity

### 如何贡献

1. 请先拥有一个完整无破坏的 FF14 国服客户端, 然后运行 [XIVLauncherCN (Soil)](https://github.com/AtmoOmen/FFXIVQuickLauncher), 
2. 设置好游戏客户端后重启, 软件会自动在 `%appdata%/XIVLauncherCN/gameHashes` 内生成一个以当前游戏客户端版本号的 `.json` 文件 (如果存在多个, 请找到最新的那个)
3. 打开后下拉, 找到末尾 `LastGameVersion` 一项, 填入在本仓库 integrity 文件夹内所能找到的上一个最新游戏版本的字符串 (注意格式)
4. 保存
5. 提交 Pull Request