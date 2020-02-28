# poker-keyboard-setting
ikbc poker改键位分享 - 把poker方向键改到右边

(本来发表在简书的,但是不知道为什么这篇被简书封了, 看了下条例我也没违规什么啊..申诉好累我懒得用了,暂时没找到什么好的平台发我就先发在这里吧)

先声明一下:

每个人对键盘都有自己习惯的使用方法,这篇文章里的键位设置只是我自己习惯的而已哈, 并不是我这种方案就是最好的, 只能说是最适合我的. 大家看看方法之后可以按照自己的习惯来调整适合自己的键位哈.
此文里使用的是ikbc poker升级版改键位

--------------分割线--------------


前情提要:
一直用87键, 但是用87键的时候手要挪来挪去的, 每次翻页啊或者按完方向键手要挪回来的时候还得瞄一眼键盘,觉得好麻烦, 就想要个小键盘..

很小的那种..

小到能不用鼠标就不用鼠标的那种..

小到手用键盘的时候手不用怎么挪的那种..

于是我就去网上搜罗了一圈............然后就入了个ikbc的poker...........

--------------分割线--------------

拿到手的时候我是懵逼的, 这都0202年了, 怎么这个usb口还是长得那么古老? 某东南西北的自营应该卖的是新款吧???????网上做了下功课,哦原来这个是poker升级版...至于其他的poker2,3,4,5等等等等就不知道了......
东西是拿到了,那就要好好用啊,虽然一开始已经知道它的键位没有方向键等等等等了,但是它小啊,而且cherry茶轴手感我还蛮喜欢的,做工什么的也还可以,大键也不像别人说的那么肉,手感我是还蛮满意的, 就先用着吧
但是用了几天之后有点抓狂...主要是这个方向键, 它在它在左边!!! 虽然之前玩一些游戏的时候wasd这几个键作为方向键我已经适应过, 但是当浏览网页等等类似的动作的时候, 想配合pageDown pageUp这些键来使用的时候就觉得很不趁手了, 本来我把CapsLock的键改成了Fn的用意就是想单独操作而已,但是这样子要翻页的时候还是得用上右手, 那我手还是得挪来挪去的啊.........

不行,不能忍,我得把方向键改到右边去才行

--------------分割线--------------

网上相关的把poker的方向键往右边改的教程真的挺少的..而且我还看见好几个提问问了好多年都没人回复的, 还有的回复根本答不对题..搜了好久搜得心灰意冷, 甚至还产生了退货或者买hhkb的想法......
但是, 贫穷让我保持了理智, 终于让我找到了一个看起来挺有用的改键位分享:https://github.com/itgoyo/Poker-for-Mac/issues/1


这位仁兄把他的键位改成了这样:

https://github.com/eduxxdoo/poker-keyboard-setting/blob/master/1.png


键盘的原来布局是长这个样子的:

https://github.com/eduxxdoo/poker-keyboard-setting/blob/master/2.png


看起来好像有那么点意思, 然后看了一下他的方法, 感觉可以操作, 那我就来试一波.


--------------分割线--------------

改键位方案:

按照我的使用习惯,我准备把我的键位改成这样:

https://github.com/eduxxdoo/poker-keyboard-setting/blob/master/3.png


- 原CapsLock 改为 组合键, 按住这个键位可以结合ijkl切换上下左右;


- 原i,j,k,l字母键添加上下左右的功能, 这样子我手指放在键盘上基本不需要怎么动就可以操控方向键了;


- 反正我右边的那些功能键也不怎么使用,那就把原右边的ALT改为pageDown, 这样子可以结合上下左右键直接操作下翻页, 浏览网页或者看pdf的时候非常方便. 为什么不像那位仁兄把这个设置成上翻页呢, 因为我在我的实际使用过程中下翻页的频率比上翻页要高, 而为了少移动手臂, 下页设置在ALT的位置可以用右手大拇指或者右手无名指就可以操作了, 对我来说就很方便啊~

- 我是mac, 所以左边的ALT键和WIN键一定要换个位置改成opt键和command键.;


- 这个方案平常写代码写文字什么的还可以CapsLock+command+方向键实现类似Home和End的功能, 虽然麻烦了一点,但是习惯了之后很好用.


这样操作基本不影响键盘自带的功能, 比如要用之前wasd作为方向键,也还是可以用啊,有时候想偷懒不想按组合键只想按方向键也可以啊, Fn+space之后wasd就变成方向键了,再按一次又变回去wasd,一点都不影响键盘原来的功能


虽然我那个切换上下左右的组合键在左边, 但是比起之前要按住右边fn去操作方向键的方法来说我已经很少移动手了, 而且用wasd做方向键的时候我要调上下左右还得把手指移过去,多累. 把CapsLock键改成Fn的方法我在前面提到过, 也很不适应, 是我改键位的主要原因.

--------------小剧场--------------

什么,你问我大写锁定键呢?

啊哈..那个我觉得大写锁定键好像没什么用,就不要了...那打英文的时候大写怎么办?

我们还有shift啊

--------------分割线--------------

改键位方法:
根据那位仁兄提供的方法, 我使用了Karabiner-Elements这个神器来进行操作, 官网地址在这里:https://pqrs.org/osx/karabiner/


(看了官网才发现这个软件好像只支持mac....用windows的朋友散了散了吧)


首先根据那位仁兄的方法将Complex modifications那里的Rules添加了一个Change right_command +hjkl to arrow keys, 然后去到~/.config/karabiner/karabiner.json把里面的right_command改成left_control, 里面的hjkl的键按照功能分别替换为ijkl, 改完之后如图:

https://github.com/eduxxdoo/poker-keyboard-setting/blob/master/4.png


json里面对应位置长这样的(防止流量爆炸提供一个示例, 反正道理都是一样的啦):
https://github.com/eduxxdoo/poker-keyboard-setting/blob/master/5.png



然后我要把CapsLock键变成组合键,所以就要把这个caps_lock和left_control键换一下(我试过直接把CapsLock换right_command但是不成功,不知道什么原因,所以还是用caps_lock换left_control比较保险),;
再把command和opt键的位置设置一下,就完成啦. 设置如下:

https://github.com/eduxxdoo/poker-keyboard-setting/blob/master/6.png


经过这些设置之后,我的键位终于更改成功,撒花~!!
经过测试,完美使用, 而且一点不妨碍我切换输入法,并且组合键+h键居然是删除, 这下我连右上角的删除键也不用移动手去够了, 用习惯了甚至我的87键也可以这么改,和本来的键位也不冲突,这样就可以在换键盘的时候也能体会手不用移动的感觉,还不用担心切换键盘不适应啦~非常适合懒癌

https://github.com/eduxxdoo/poker-keyboard-setting/blob/master/7.png


东西是拿到了,那就要好好用啊,虽然一开始已经知道它的键位没有方向键等等等等了,但是它小啊,而且cherry茶轴手感我还蛮喜欢的,做工什么的也还可以,大键也不像别人说的那么肉,手感我是还蛮满意的, 就先用着吧
