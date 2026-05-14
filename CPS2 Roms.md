# CPS2 街机游戏兼容性列表

以 Widows 版的 RetroArch 为例，支持 CPS2 街机游戏的核心不止一个：
- Arcade (FB Alpha 2012 CPS-2)
- Arcade (FB Alpha 2012)
- Arcade (FinalBurn Neo)
- Arcade (MAME...) 系列核心

1G1R 是 1 Game 1 ROM 的缩写，意思是一个游戏只选取一个最佳版本的 ROM 文件。

下面这份 CPS1 街机游戏列表，是根据 FBNeo - Arcade Games.rdb 数据库里 ROM 文件描述，按照 1G1R 的策略收集整理的，当一个游戏有多个版本的 ROM 文件时，筛选规则如下：
1. 只支持 FinalBurn Neo，不支持 FB Alpha 2012 CPS-2 和 FB Alpha 2012 的 ROM 文件淘汰；
2. 如果不止一个版本的 ROM 文件支持多核心，优先选择没有依赖的 ROM 文件。

序号 | ROM 文件 | CRC32 | 依赖于 | 游戏名称 | 兼容性说明
--- | --- | --- | --- | --- | ---
1 | 1944d.zip | 8AED6511 | 1944.zip | # - 1944 循环的征服者 | 
2 | 19xxd.zip | 696F34C6 | 19xx.zip | # - 19XX 命运否决战 | 
3 | armwar.zip | E4CA3E59 | | Z - 装甲战士 | 
4 | avsp.zip | 4BFE3F71 | | Y - 异形对铁血战士 | 
5 | batcir.zip | B402FA51 | | Z - 战斗回路 | 
6 | choko.zip | A406029A | | Y - 益智麻将牌 长江 | 
7 | csclub.zip | 3CC73D20 | | K - 卡普空运动俱乐部 | 
8 | cybots.zip | 7665466C | | J - 机甲战士 全金属狂潮 | 
9 | ddsom.zip | 8546133B | | L - 龙与地下城2 暗黑秘影 | 
10 | ddtod.zip | 3480C0E8 | | L - 龙与地下城1 毁灭之塔 | 
11 | dimahoo.zip | 72E0E27A | | C - 超级魔法大作战 | 
12 | dstlk.zip | C31741E5 | | E - 恶魔战士 午夜斗士 | 
13 | ecofghtr.zip | F7967835 | | H - 环保战士 | 
14 | gigawing.zip | AB0228A7 | | Q - 千兆之翼 | 
15 | hsf2.zip | 673346FD | | C - 超级街头霸王2 周年纪念版 | 
16 | jyangoku.zip | FD11BC92 | | Q - 雀国志 霸王的采牌 | 
17 | megaman2.zip | F0DD6874 | | L - 洛克人2 力量对决 | 
18 | mmancp2u.zip | 62035888 | | L - 洛克人1 力量之战 (CPS2版) | FB Alpha 的两个核心不可玩：<br>无法运行 
19 | mmatrix.zip | D7C6AB6C | | H - 火星矩阵 超固体射击 | 
20 | mpang.zip | 87EFFC38 | | C - 超强魔法气泡 | 
21 | msh.zip | 52F31C17 | | M - 漫威超级英雄 | 
22 | mshvsf.zip | 5E897C84 | | M - 漫威对街霸 | 
23 | mvscud.zip | 73B92F08 | mvsc.zip | M - 漫威对卡普空 超级英雄的碰撞 | 
24 | nwarr.zip | 6A9DBB19 | | X - 吸血鬼猎人1 恶魔的复仇 | 
25 | progear.zip | 705FF2B3 | | N - 能源之岚 | 
26 | pzloop2.zip | 1CC2DB97 | | Z - 智力循环2 | 
27 | qndream.zip | 34D21FCF | | W - 问答七彩梦 虹色町的奇迹 | 
28 | ringdest.zip | 10660821 | | S - 摔角霸王2 连环爆裂 | 
29 | sfa.zip | 1BF4890D | | S - 少年街霸1 斗士之梦 | 
30 | sfa2.zip | 0C8733F2 | | S - 少年街霸2 | 
31 | sfa3.zip | 4492FC52 | | S - 少年街霸3 | 
32 | sfz2al.zip | DD9434D2 | | S - 少年街霸2 Alpha | 
33 | sgemf.zip | 3D5EB900 | | C - 超级口袋战士 | 
34 | spf2td.zip | C66B6CE7 | spf2t.zip | J - 街霸方块 | 
35 | ssf2d.zip | C77C5178 | ssf2.zip | C - 超级街头霸王2 新挑战者 | 
36 | ssf2t.zip | 92B67A50 | | C - 超级街头霸王2 加强版 | 
37 | vhunt2.zip | 024088A4 | | X - 吸血鬼猎人2 恶魔的复仇 | 
38 | vsav.zip | AB46F0EE | | X - 吸血鬼救世主1 吸血鬼之王 | 
39 | vsav2.zip | FFED36BB | | X - 吸血鬼救世主2 吸血鬼之王 | 
40 | xmcota.zip | 24DE20B9 | | X - X战警 磁场原子人 | 
41 | xmvsf.zip | F1A75536 | | X - X战警对街霸 | 

建议优先使用 Arcade (FinalBurn Neo) 核心加载游戏。

我拥有游戏手柄和街机摇杆两种设备，为了避免来回修改按键映射的麻烦，我的做法是：
- 使用手柄的时候切换到 Arcade (FinalBurn Neo) 核心，采用手柄的按键映射方案；
- 使用街机摇杆的时候切换到 Arcade (FB Alpha 2012 CPS-2) 核心，采用街机摇杆的按键映射方案。
