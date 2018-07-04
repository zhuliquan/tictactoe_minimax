# 项目说明

> 这是一个使用python实现的`MiniMax`搜索玩TicTacToe游戏，
这里主要参考了一篇[MiniMax的博文](https://blog.csdn.net/wldgg/article/details/50132923)

## 文件说明

项目中有四个文件
- game.py
- human.py
- minimax.py
- run_tictactoe.py
---
>比较重要的是game.py 和 minimax.py 文件。在game.py 中主要包含状态类State 和 游戏类Game
在minimax.py 中主要包含搜索树的节点类Node和搜索树类MiniMax AlphaBeta

## 运行程序
如果你想ai玩这个游戏你可以运行run_tictactoe.py这个文件。
```
python run_tictactoe.py
```

## 运行条件
- python 3.6.5
- numpy 1.13.3
- pandas 0.22.0

## 参考
[minimax搜索的ppt](./reference/ai_minimax.ppt)
