# 图表字体
# 声明：本项目所有字体版权归本人所有，仅用于个人学习交流；未经许可，不得用于任何商业用途！如有商业用途，请联系QQ：1034769071。
## 1.PieChart 使用说明

[**下载 PieChart 字体**](https://coding.net/u/sharemine/p/sharemine.coding.me/git/raw/master/PieChart.ttf)

在文档中设置字体为 PieChart，输入字符即可显示对应的饼图，字符与饼图对应表详见下图：

![字符、字形及饼图对照表](https://raw.githubusercontent.com/ChartsFont/ChartsFont.github.io/master/PieChart.png)

若要在Excel中以迷你饼图展示百分数，可参考以下公式：
<pre>=IF(MOD(A1*100,5)=0,MID("A0F1K2P3U4Z5e6j7o8t9y",INT(A1*20)+1,1),MID("BCDEGHIJLMNOQRSTVWXYabcdfghiklmnpqrsuvwx",INT(A1*40)+1,1))</pre>
注：公式中的 A1 单元格是一个百分数，可在单元格B1中输入上述公式，此时单元格B1需设置字体为 PieChart。

<br>
<br>
<hr>
<br>

## 2.BlockChart 使用说明
[**下载 BlockChart 字体**](https://coding.net/u/sharemine/p/sharemine.coding.me/git/raw/master/BlockChart.ttf)

使用方法类似 PieChart 字体，以下是几个实例：

![例子](https://raw.githubusercontent.com/ChartsFont/ChartsFont.github.io/master/Blockchart-examples.png)

若要在 Excel 中以方块堆积图展示百分数，可参考以下公式：
<pre>=MID("0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz①②③④⑤⑥⑦⑧⑨七三上下九二八六十千口土大天太女子山工干平开心才文方无日木四",INT(A1*100)+1,1)</pre>
注：公式中的A1单元格是一个百分比数值，可在单元格B1中输入上述公式，此时单元格B2需设置字体为 BlockChart，字体大小设置150以上，显示效果较好。
