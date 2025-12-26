# 关于本项目

本项目仅可用于研究和学习用途（或者是剧情研究），**请勿用于游戏作弊并影响Eternights普通用户体验**。

# 如何打开文件

使用Visual Studio Code打开save.sav，然后给这个文件添加注释。

# 存档文件架构

这个存档文件使用JSON格式存储，为了方便普通人理解，本项目内的存档使用了JSON with Comments。

# 主角名字命名

参看此处代码（截取自save.sav）

```jsonc
{
 "names": [
            {
                "key": "Player",
                "value": true,
                "revealedName": "Don Quixote" // 这是您在游戏内的名字。
            }
          ]
}
```

# 已知问题

- 如果"BlackMother"对应暗怖拉，"WhiteMother"对应洛克丝（虽然游戏内剧情已经说明），那么我们需要解析"BlackMotherEssence"和"WhiteMotherEssence"在剧情内对应的含义。

# 如何提交发现

直接通过Github Issue提交新Issue，只需遵守Github Guidelines就行。
