# Valentine 特辑

> 今天是一个特殊的日子
> 因为没有办法jianmian，自己做的choko又失败了
> 本来还蛮难过的，后来Liz提醒我不要去朋友圈
> 我就去了，没想到之前从学校借书封面找代码加好友的那位大佬发了个程序员的瓦伦丁节庆祝指南
> 里面第一条就是写代码送给kanojyo
> 一拍脑袋，哎呀就是嘛！
> 说干就干！

## 需求分析
1. 最简单的轮播图（因为跟她说只需要几个小时）
2. 214的来历文案
3. 加一个iframe的网易云音乐
4. 最后祝她节日快乐

## 准备清单
1. 本地调试xampp客户端
2. 轮播图组件iSlider
3. 百度词条的214文案
4. 网易云《月色真美》ED

——————————
### xampp新建项目文件夹
这个嘛贼简单大家都懂
### 文案
    约在公元三世纪的罗马，那时恺撒已经死去快三百年了，暴君克劳多斯(Claudius)当政。当时，罗马内外战争频仍，民不聊生。为了补足兵员，将战争进行到底，Claudius下令，凡是一定年龄范围内的男子，都必须进入罗马军队，以生命为国家效劳。自此，丈夫离开妻子，少年离开恋人。于是整个罗马便被笼罩在绵长的相思中。对此，暴君大为恼火。为了达到自己的目的，他竟然下令禁止国民举行结婚典礼，甚至要求已经结婚的毁掉婚约。

    然而，暴政禁止不了爱情。就在暴君的国都里，居住着一位德高望重的修士，他就是瓦沦丁(Valentine)，他不忍看到一对对伴侣就这样生离死别，于是为前来请求帮助的情侣秘密地主持上帝的结婚典礼。一时间，这一令人振奋的消息在整个国度传开，更多的情侣秘密地赶来请求修士的帮助。

    但是，事情很快还是被暴君知晓了，于是他再一次显示了残暴面目--将修士打进大牢，最终折磨致死。修士死的那一天是2月14日，公元270年的2月14日。 人们为了纪念这个敢于与暴君斗争的人，渐渐地使得2月14日成为一个节日。很多世纪过去了，人们再也记不得Claudius的大名，再也记不得他的权杖与宝剑，但依然会纪念Valentine修士，因为那个日子是Valentine's Day，是情人节。

### 月色真美的iframe代码

```html
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=480097178&auto=1&height=66"></iframe>
```

### 主框架代码，利用iSlider的demo修改而成

见具体代码


然后就完成了
祝Liz这辈子都能幸福！
祝我也能有爱别人和被爱的能力



