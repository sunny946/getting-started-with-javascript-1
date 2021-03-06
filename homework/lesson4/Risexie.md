第四节课总结
===
### 最好的的时代

感谢老师为了照顾及学员进度而一再调节课程的内容，老师辛苦了。
说实话没有老师开设的这一门课程，我想我还是会去学习编程的，不管用什么方式。
曾经有人说过，这是一个最好的时代。在这个时代没有大型的战争，没有大型的冲突，我们可以生活得非常的安稳。同时互联网给我们提供了一个非常强大的外脑。  

笑来老师说：
> english +互联网=Almost everything
  
我们几乎可以从互联网上找到我们想要的一切信息。如果同时利用好搜索功能，我们甚至可以把互联网当作我们的记忆库，这可以帮助我们突破大脑记忆的上限。  
在接下来，我们的整个世界都会朝着电子化发展。越来越多生活设备被加入电脑芯片，被自动化，被电脑化。如果我们想要和这个世界更好的相处，想要在将来这个高度信息化，电脑化的世界体验更多的可能，掌握如何跟电脑相处，这是我们都逃不掉的命运。

尽管网上的资源是如此多，但是对于一个小白来说，面对如此多的信息，首先我们无法甄辨他们的质量。其次更是因为知识的繁杂，我们更多不知道从何下手，就光是安装编程的环境都让我们足够头疼。再加上编程其实是实现我们人类想法的工具。如果没有编程的思想，我们最终都只能成为写代码的机器，为了编码而编码，哪这件事情没有任何意义。，他们都跟企业有着保密协议，没有办法将我们人类思考的精华从企业带到我们这里。还好我们碰见了徐老师，愿意为了计算机教育，从大厂出来帮助我们这些小白，在这里再一次表示我的感激！
<hr>
### Function的三要素
在JS当中最为重要的三要素是：目标、方法和return。  
1. 目标：我们需要明确调用的目标，来使用函数。

2.  方法：方法内容是一个函数的内核，选用好的方法来执行，能够提运行的速率。
3. Return:返回值是函数的结果，而这个结果有可能是另外一端函数的输入

### 引入第三方库  

在网页制作当中，如果仅仅是依靠HTML自带的语法格式，我们无法做出一些赏心悦目的网页效果。这个时候我们就可以使用第三方库的服务。  
老师在直播当中就演示了如果引入VUE的服务，只需要加上库的来源URL。并在代码当中使用我们预定义好的数据，就可以让我们的静态网页“动起来”

### 如何将我们要执行的任务转化成代码？
计算机能够处理这么复杂的任务，看似不可思议。飞快的运算速度，更加会让我们误以为计算机是足够的聪明。其实不过时将一个复杂的大任务，逐个拆分，拆分到计算机可以执行的程度。  
在课堂当中，老师当场示范了如何让计算机做出“报数”这个动作。老师采取了几种不同的方法。 

1. 轮流 

直接写出五个独立的报数`function`，然后再用一个`function`把这个他们五个都串起来，再直接输出。这其实就是一个拆分工作的例子，将“5个人报数”这件事情拆分成5次的“单人”报数，然后再依次执行。

2. 通知

在第一个`function`当中嵌套第二条，因为接下来的每条函数都是层层嵌套的，所以只要执行第一条。自然就会不断执行，直到结束。感觉有点像多古诺骨牌，在每条函数当中都加上了“触发”机制，这样子在输出的时候就不用重复“输出”命令。  
<hr>

### 厨房的工作流  

在一开始，我们需要做众多的准备工作：(`prepare`)，扫地、洗碗等等，而接下来的工作是建立在这些准备工作之上的，所以我们必须要对准备工作是否完成加以判断(`ture`)。（这时候可以用到布尔值）

第二部我们需要去买菜：（`buyFoods`），而其实“买”这个过程对应到流程中就是定义字符串`food`,并最终`return`出来，好让我们有材料可以“做菜”。

第三部便是我们做菜的核心流程，但首先我们需要“拿“到菜来加工，才能最后得出色香味俱全的菜肴。所以要在第三个`funtion`当中使用到刚才第二部`return`出来的数据。

*当我们已经完成了任务的拆分，这个时候只要再把他们按照一定的条件串起来，就可以完成一个大工作。这其实就是编程！*

最后构建`startWorkFlow`，来将以上三部组合到一起。但是只有准备工作做好了，我们才能去买菜，才能开始做菜啊。所以这个时候需要一个`if `函数。
如果准备工作做好了：`ture`我们就继续开展，否则：`else`就是没有准备好。
然后我们使用第二部`return`出来，也就是买到的菜给第三部，执行它，然后再把第三部中`return`出来（也就是做好的菜）摆上桌子。我们就大功告成了。

*这个例子的确让我对后台数据的调用有深刻的理解。想起来老师曾经说过新生大学登陆后台，会对用户的数据进行5次的哈希运算。这个过程其实以上的例子有点相像。需要不断调用哈希出来的结果然后再一次哈希，最后才可以登录。*
