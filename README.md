## 指定可能文字色
- 黒 fg.BLACK
- 赤 fg.RED
- 緑 fg.GREEN
- 黄 fg.YELLOW
- 青 fg.BLUE
- マゼンタ fg.MAGENTA
- シアン fg.CYANY
- 白 fg.WHITE

## 指定可能文字色
- 黒 bg.BLACK
- 赤 bg.RED
- 緑 bg.GREEN
- 黄 bg.YELLOW
- 青 bg.BLUE
- マゼンタ bg.MAGENTA
- シアン bg.CYANY
- 白 bg.WHITE

## 使用可能エフェクト
- 太字 fg.BLOD
- 下線 fg.UNDERLINE

## 使用例
from Color import FrontGround as fg
from Color import BackGround as bg

print(fg.RED("赤"))
print(fg.BLUE("青"))
print(bg.CYAN(fg.RED(fg.UNDERLINE("背景色混ぜてみた"))))