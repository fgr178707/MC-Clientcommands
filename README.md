## rng附魔模组Clientcommands

## [附魔ID](Enchantment.md) [装备ID](outfit.md)

## 1. RNG 钓鱼：
**（由于在 1.20 版本开始无法再利用 RNG 操作战利品表，在 1.20 之后的版本 cfish 命令已被删除）**
| 命令  | 解释
| :-|:-
|/cfish add-goal|物品名|
|/cfish add-enchanted-goal |附魔物品名|

## 2. RNG 附魔：

| 命令  | 解释
| :-|:-|
|/ccrackrng|启动附魔预测|
|/cconfig clientcommands enchantingPrediction set true| 设定附魔预测并打开附魔台
|/cenchant|物品id with 附魔 等级 获取附魔种子|

##  RNG 无限耐久：
| 命令  | 解释
| :-|:-|
|/cconfig clientcommands infiniteTools set true|启动无限工具|
|ccrackrng|计算玩家RNG|
|/cconfig clientcommands toolBreakWarning set true|工具损坏提示|

## 寻找：
| 命令  | 解释
| :-|:-|
|/cfind |要找的实体 寻找最近实体并返回位置|
|/cfindblock |要找的方块 寻找最近方块并返回位置。
|/cfinditem |要找的物品 寻找最近的含有此物品的容器并返回位置。
|/cglow area |坐标 1 坐标 2 使一块区域高亮。
|/cglow block |方块坐标 使方块高亮。
|/cglow entities| 实体名 使实体高亮。
|/clook block|方块坐标 使玩家看向此方块。
|/clook entities| 实体名 使玩家看向此实体。

## 调节:
| 命令  | 解释
| :-|:-|
|/cfov| 视场角 调节视场角。
|/cgamma |伽马值 调节伽马值

##  其他：
| 命令  | 解释
| :-|:-|
|/calias|为命令创建别名。
|/careastats|显示特定区域的统计信息。
|/cchorus|紫颂果传送位置，需要 /ctemprule set chorusManipulation true。
|/chotbar|保存或恢复您的快捷栏。
|/ckit|保存或恢复背包物品。
|/cbook|对于具有区块保存内容有用（仅在 1.15 及更低的版本中启用）。
|/cgive |目标 给一位创造模式下的玩家物品（与原版 give 相同）。
|/cgetdata |目标 获得对应方块或实体的 NBT。
|/ccalc |算式（例如 1+1，5*3）简易计算器。
|/cpos|在维度之间转换坐标。
|/ccalcstack|物品堆叠计算器。
|/cpermissionlevel|获取玩家的当前权限级别。
|/cplaysound |播放声音。
|/cstopsound |停止声音。
|/cghostblock |创建一个幽灵方块（仅客户端可见）。
|/cmote|在聊天中编写文本表情。
|/cnote |做笔记。
|/cwiki |快速查询 Wiki (注意是 MC Wiki，不是本模组 Wiki)。
|/csnake |贪吃蛇游戏。
|/chelp |显示帮助。
|/crelog|自动重新记录。
|/crender|更改呈现的实体。
|/cshrug|在聊天中写道 ¯\_(ツ)_/¯。
|/cscript|使您能够运行自己的脚本。（在 1.19 中要删除的已弃用客户端命令脚本)。
|/csignsearch|搜索包含指定文本的告示牌。
|/ctask|脚本的游戏内任务管理器。
|/ctemprule|激活特定功能。
|/ctime|获取世界当前时间。
|/cusagetree|显示其他命令的树用法。
|/ctime|获取世界当前时间。
|/cusagetree|显示其他命令的树用法。

