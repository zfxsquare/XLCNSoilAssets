## Intergrity

### 如何贡献

1. 请先拥有一个完整无破坏的 FF14 国服客户端, 然后运行 [XIVLauncherCN (Soil)](https://github.com/AtmoOmen/FFXIVQuickLauncher), 
2. 设置好游戏客户端后重启, 软件会自动在 `%appdata%/XIVLauncherCN/gameHashes` 内生成一个以当前游戏客户端版本号的 `.json` 文件 (如果存在多个, 请找到最新的那个)
3. 打开后下拉, 找到末尾 `LastGameVersion` 一项, 填入在本仓库 `integrity` 文件夹内所能找到的上一个最新游戏版本的字符串 (注意格式)
4. 保存
5. 提交 Pull Request

## Patch Info

### 如何贡献

1. 找到 `XIVLauncherCN.exe` 同一文件夹下的 `XIVLauncher.PatchInstaller.exe`, 确定文件夹无误
2. 在当前文件夹下右键打开终端, 运行以下命令 (根据你的终端类型任选其一执行):
   - CMD: `xivlauncher.patchinstaller.exe index-update -r .\patch-dl\`
   - PowerShell: `.\xivlauncher.patchinstaller.exe index-update -r .\patch-dl\`
3. 等待下载完成后 (需要下载完整游戏客户端), 找到同一文件夹下的 `patch-dl` 文件夹打开
4. 分别上传对应的 `.index` 文件到对应文件夹里, 修改 latest.json 内的内容至最新版本
5. 提交 Pull Request

