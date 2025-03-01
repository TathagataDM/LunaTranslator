# OCR模式绑定游戏窗口

默认已激活`选取OCR范围后自动绑定窗口`，当范围框的四个顶点同属于某个窗口HWND时，会自动绑定到该窗口上。

一般来说，用其他OCR软件时，一个很折磨人的地方就是，经常需要留个神注意游戏窗口和翻译窗口的位置。可能翻译窗口和截图区域相交，或者有时游戏窗口要切到后台，这时候都很烦

但是，Luna的**绑定窗口**这一设置，能完美解决这个痛苦。

点击**绑定窗口**按钮，然后点击游戏窗口，按钮变成粉色，说明成功绑定了游戏窗口

![img](https://image.lunatranslator.org/zh/gooduseocr/bind.png)

![img](https://image.lunatranslator.org/zh/gooduseocr/bindok.png)

这时会有一些重要变化：

1. **截图将是仅会对游戏窗口的截图，不会截图到其他非游戏窗口**。这样，翻译窗口可以随意放在任何位置，而不会因为和截图区域相交而激烈变化；这样，当游戏窗口被其他窗口遮挡，截图也仅会截取游戏窗口，不会截取遮挡窗口。

2. **当游戏窗口移动时，OCR区域会跟随游戏窗口同步移动**。这样，当有时需要移动游戏窗口时，不需要移动OCR范围框了，尤其是当你隐藏了范围框时，不需要显示-移动-再隐藏了。


除此之外，当绑定了游戏窗口后，还有一些别的好处是：

1. 游戏截图功能能更准确的截取到游戏窗口

2. 游玩时间追踪功能能更准确的记录时间

3. 可以使用内置的Magpie，或使用工具按钮呼叫你自己下载的Magpie

4. 可以从窗口句柄获取到游戏位置以及软件内部ID，可以对游戏进行进行一些个性化的设置，包括专用于该游戏的语言/语言合成/翻译优化/文本处理/Anki等的设置等
