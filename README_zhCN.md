# DDLC Comfy UI
<img src="Logo.png?raw=true">

---
你好喵，我不是作者，所以我们快进到 **特点** 好吗？



## 特点
* 多种风格
* 游戏内设置项
* 高DPI支持



## 兼容性
所有不尝试修改界面的mod都适合这个

以下是已经验证的游戏:
* Doki Doki Literature Club
* Monika After Story
* Monika Before Story
* Purist



## Screenshots
<table>
  <tr>
    <th></th>
    <th>默认</th>
    <th>深色</th>
  <tr>
    <td>未安装</td>
    <td><img src="Screenshots/Unmodded.png?raw=true" width="320"></td>
    <td><img src="Screenshots/UnmoddedDark.png?raw=true" width="320"></td>
  </tr>
  <tr>
    <td>Default</td>
    <td><img src="Screenshots/Default.png?raw=true" width="320"></td>
    <td><img src="Screenshots/DefaultDark.png?raw=true" width="320"></td>
  </tr>
  <tr>
    <td>Cold</td>
    <td><img src="Screenshots/Cold.png?raw=true" width="320"></td>
    <td><img src="Screenshots/ColdDark.png?raw=true" width="320"></td>
  </tr>
  <tr>
    <td>Mint</td>
    <td><img src="Screenshots/Mint.png?raw=true" width="320"></td>
    <td><img src="Screenshots/MintDark.png?raw=true" width="320"></td>
  </tr>
  <tr>
    <td>Peach</td>
    <td><img src="Screenshots/Peach.png?raw=true" width="320"></td>
    <td><img src="Screenshots/PeachDark.png?raw=true" width="320"></td>
  </tr>
  <tr>
    <td>Strawberry</td>
    <td><img src="Screenshots/Strawberry.png?raw=true" width="320"></td>
    <td><img src="Screenshots/StrawberryDark.png?raw=true" width="320"></td>
  </tr>
  <tr>
    <td>Classic</td>
    <td><img src="Screenshots/Classic.png?raw=true" width="320"></td>
    <td><img src="Screenshots/ClassicDark.png?raw=true" width="320"></td>
  </tr>
  <tr>
    <td>Mystique</td>
    <td><img src="Screenshots/Mystique.png?raw=true" width="320"></td>
    <td><img src="Screenshots/MystiqueDark.png?raw=true" width="320"></td>
  </tr>
  <tr>
    <td>Chocolate</td>
    <td><img src="Screenshots/Chocolate.png?raw=true" width="320"></td>
    <td><img src="Screenshots/ChocolateDark.png?raw=true" width="320"></td>
  </tr>
  <tr>
    <td>Starry</td>
    <td><img src="Screenshots/Starry.png?raw=true" width="320"></td>
    <td><img src="Screenshots/StarryDark.png?raw=true" width="320"></td>
  </tr>
</table>



## 安装

> 在本存储库中，只发布MAS版本

1. [下载最新的发布版](https://github.com/MAS-Submod-MoyuTeam/DDLCComfyUI/releases)
2. 将所有文件解压后放在游戏的 `game` 文件夹



## 使用
1. 打开游戏
2. 切换到 **设置** 界面 (在MAS中是 **Submods** )
3. 找到风格部分
4. 通过移动 **主题** 标签下方的滑块来选择主题
    * 不勾选 **字体** 将会禁用字体
    * 不勾选 **布局** 将不会修改部分布局
    * 勾选 **高DPI** 将在可用时使用高清贴图
5. 按下 **Apply** 然后重启游戏



## 卸载
1. 打开游戏
2. 切换到 **设置** 界面 (在MAS中是 **Submods** )
3. 找到风格部分
4. 点击 **禁用** 并关闭游戏
5. 在你的DDLC目录中移除一下文件:
    * `game/comfy_meta/` (*文件夹*)
    * `game/comfy_ui/` (*文件夹*)
    * `game/comfy_ui.rpy`
    * `game/comfy_ui.rpyc`
    * `game/python-packages/comfy_ui.py`



## 问题定位
如果mod并没有加载并且报错了:
1. 请确保下载了正确的版本 (查看 [安装](#安装)).
    * 文件 `MASComfyUI_vX.X.X.zip` 不在DDLC及其通常衍生MOD中有效.
    * 文件 `DDLCComfyUI_vX.X.X.zip` 不在MAS和类似作品（after story）中生效.
    * 压缩包理应包括:
        * `python-packages`
        * `comfy_ui.rpy`
        * ...
    * 压缩包 **绝不应该** 包括:
        * `Source`
        * `Make.py`
        * ...
2. 确保解压到正确的目录.
    * **IMPORTANT:** 对于MAS玩家，ComfyUI **绝对不能** 被安装在 `Submods` 文件夹.
    * 最简单的方式就是查看你的 `game` 目录中是否含有以下内容:
        * `comfy_meta`
        * `comfy_ui`
        * `comfy_ui.rpy`
    * 这是一个示例的路径:
        * **正确:** `C:\Program Files (x86)\Steam\steamapps\Doki Doki Literature Club\game\comfy_ui.rpy`
        * **不正确:** `C:\Program Files (x86)\Steam\steamapps\Doki Doki Literature Club\game\Submods\MASComfyUI_v2.0.1\comfy_ui.rpy`
3. 确保你使用的是最新版本 (查看Github上的 [Releases](https://github.com/MAS-Submod-MoyuTeam/DDLCComfyUI/releases)).

如果以上建议都没用，请发起一个新的issue.



## FAQ
让我们假设你已经有问一些问题.

**Q:** 为什么?  
**A:** 因为我可以.

**Q:** 看起来一般.  
**A:** 你不是我的目标用户喵，对不起.



## 已知问题
现在无.



## 特别感谢
Dan Salvato 和 Team Salvato.



## License
See LICENSE file in the root of this repository.
