---
layout: post
title: 如何成为一名黑客
catogory: hacker
tags: [hacker]
---
{% include JB/setup %}

Copyright © 2001 by Eric S. Raymond

翻译：Barret

翻译水平有限，欢迎来信指教，我的Email是barret（a）ynmail.com， 但请勿问电脑技术问题（反正也不懂）。

允许未经作者及译者的同意进行非商业目的的转载，但必须保持原文的完整性。

## 内容一览

+ 为什么会有这份文档?
+ 什么是黑客?
+ 黑客应有的态度!
+ 黑客的基本技能!
+ 黑客文化中的地位!
+ 黑客和书呆子(Nerd)的联系
+ 风格的意义!
+ 其它资源!
+ FAQ(常问问题解答)


为什么会有这份文档？

作为 Jargon File 的编辑和 一些其他有名的类似性质文章的作者，我经常收到充满热情的网络新手的email提问（确实如此） “我如何才能成为一名出色的黑客？”非常奇怪的是似乎没有任何的FAQ或者Web形式的文档来说明这个 十分重要的问题，因此我写了一份。

如果你现在读的是这份文档的离线拷贝，那么请注意当前最新版本（英文版）在 http://www.tuxedo.org/~esr/faqs/hacker-howto.html可以得到。

注意：在这份文档最后有 FAQ（常问问题解答）。 请在向我提出任何关于这份文档的疑问之前读两遍。

目前这份文档有很多翻译版本： 保加利亚语， 简体中文， 繁体中文， 丹麦语， 荷兰语， 法语， 德语， 匈牙利语， 印尼语， 日语， 朝鲜语， 葡萄牙语， 俄语及 瑞典语。 注意由于这份文档时有修正，所以以上翻译版本可能有不同程度的过时。

什么是黑客？

Jargon File 包含了一大堆关于“hacker”这个词的定义，大部分与技术高超和热衷解决问题 及超越极限有关。但如果你只想知道如何 成为 一名黑客， 那么只有两件事情确实相关。

这可以追溯到几十年前第一台分时小型电脑诞生, ARPAnet 实验也刚展开的 年代，那时有一个由程序设计专家和网络名人所组成的, 具有分享特点的文化社群。 这种文化的成员创造了 “hacker” 这个名词。黑客们建立了 Internet。 黑客们发明出了现在使用的 UNIX 操作系统。黑客们使 Usenet 运作起来， 黑客们让 WWW 运转起来。如果你是这个文化的一部分，如果你对这种文化有所贡献，而且 这个社群的其它成员也认识你并称你为 hacker, 那么你就是一位黑客。

黑客精神并不仅仅局限在软件的黑客文化中。 有人用黑客态度对待其它事情，如电子学和音乐—— 事实上，你可以在任何最高级别的科学和艺术活动中发现它。 精于软件的黑客赞赏这些在其他领域的同类并把他们也称作黑客—— 有人宣称黑客天性是绝对独立于他们工作的特定领域的。 但在这份文档中， 我们将注意力集中在软件黑客的技术和态度， 以及发明了“黑客”一词的以共享为特征的文化传统之上。

有一群人大声嚷嚷着自己是黑客，但他们不是。 他们（主要是正值青春的少年）是一些蓄意破坏计算机和电话系统的人。 真正的黑客把这些人叫做“骇客”(cracker)，并不屑与之为伍。 多数真正的黑客认为骇客们又懒又不负责任，还没什么大本事。 专门以破坏别人安全为目的的行为并不能使你成为一名黑客， 正如 用铁丝偷开走汽车并不能使你成为一个汽车工程师。 不幸的是，很多记者和作家往往错把“骇客”当成黑客； 这种做法一直使真正的黑客感到恼火。

根本的区别是：黑客搞建设，骇客搞破坏。

如果你想成为一名黑客，请接着读下去。如果你想做一个骇客，去读 alt.2600 新闻组，并在意识到你并不像自己想象的那么聪明后去坐五到十次监狱。 关于骇客，我只想说这么多。

黑客应有的态度

黑客们解决问题，建设事物，同时他们崇尚自由和无私的双向帮助。 要被他人承认是一名黑客，你的行为得体现出你好像具备了这种态度一般。 而要想做得好象你具备这种态度一般，你就得切切实实坚持它。

但是如果你认为培养黑客态度只是一条在黑客文化圈中得到承认的路子， 那就大错特错了。成为具备这些特质的这种人对 你自己非常重要——有助于你学习，及给你提供源源不断的动力。 同所有创造性的艺术一样，成为大师的最有效方法就是模仿大师的精神—— 不仅从智力上，也要从感情上进行模仿。

或许, 下面这首现代的禅诗很好的阐述了这个意思：

    To follow the path:（沿着这样一条道路：）
    look to the master,（寻找大师，）
    follow the master,（跟随大师，）
    walk with the master,（与大师同行，）
    see through the master,（洞察大师，）
    become the master.（成为大师。）

嗯，如果你想成为一名黑客，反复读下面的事情直至你相信它们：

1. 世界充满了待解决的迷人问题。

做一名黑客会有很多乐趣，但却是要费很多气力方能得到的乐趣。 这些努力需要动力。成功的运动员从锻炼身体、超越自我极限的愉悦中得到动力。 同样，做黑客，你得能从解决问题，磨练技术及锻炼智力中得到基本的乐趣。

如果你还不是天生的这类人又想做黑客，你就要设法成为这样的人。 否则你会发现，你的黑客热情会被其他分心的事物吞噬掉——如金钱、性和社会上的虚名。

（同样你必须对你自己的学习能力建立信心——相信尽管当你对某问题近乎一无所知， 但只要你一点一点地试验、学习，最终会掌握并解决它。）

2. 一个问题不应该被解决两次。

聪明的脑袋是宝贵的有限的资源。当世界还充满非常多有待解决的有趣的新问题时， 它们不应该被浪费在重新发明轮子这类事情上。

作为一名黑客，你必须相信其他黑客的思考时间是宝贵的——因此共享信息， 解决问题并发布结果给其他黑客几乎是一种道义，这样其他人就可以去解决 新问题而不是不断地忙于对付旧问题。

(你不必认为一定要把你 所有的发明创造公布出去， 但这样做的黑客是赢得大家极度尊敬的人。卖些钱来养家糊口，租房买计算机 甚至发大财和黑客价值观也是相容的，只要你别忘记你还是个黑客。)

3. 无聊和乏味的工作是罪恶。

黑客（泛指具有创造力的人们）应该从来不会被愚蠢的重复性劳动所困扰， 因为当这种事情发生时就意味着他们没有在做只有他们才能做的事情—— 解决新问题。这样的浪费伤害每一个人。因此，无聊和乏味的工作不仅仅是 令人不舒服而已，而且是罪恶。

作为一个黑客，你必须坚信这点并尽可能多地将乏味的工作自动化， 不仅为你自己，也为了其他人（尤其是其他黑客们）。

(对此有一个明显的例外。黑客有时也做一些在他人看来是重复性或枯燥的工作 以进行“脑力休息”，或是为了获得某种技能，或是获得一些除此以外无法获得的 特别经验。但这是自愿的——有脑子的人不应该被迫做无聊的活儿。）

4. 自由万岁。

黑客们是天生的反独裁主义者。 任何能向你发命令的人能够迫使你停止解决令你着迷的问题， 同时，按照独裁者的一般思路，他通常会给出一些极端愚昧的理由。 因此，不论何处，任何独裁主义的作法，只要它压迫你和其他黑客，你就要和它斗到底。

(这并非向所有权威挑战。儿童需要监护，罪犯要被看管起来。 如果服从命令得到某种东西比起用其他方式得到它更节约时间，黑客可以同意 接受某种形式的权威。但这是一个有限度的，有意的交易； 那种权威想要的个人服从不是你应该同意给予的。)

权威喜欢审查和保密。他们不信任自愿的合作和信息的共享—— 他们只喜欢由他们控制的所谓“合作”。因此，作为一个黑客， 你得对审查、保密，以及使用武力或欺骗去压迫有行为能力的人们的做法有一种本能的敌意。 同时你要有为此信念斗争的意愿。

5. 态度不能替代能力。

作为一名黑客，你必须培养起这些态度。 但只具备这些态度并不能使你成为一名黑客，也不能使你成为一个运动健将和摇滚明星。 成为一名黑客需要智力，实践，奉献精神和辛苦工作。

因此，你必须学会怀疑，并尊重各种各样的能力。 黑客们不会为那些装模做样的人浪费时间，但他们却非常尊重能力—— 尤其是从事黑客工作的能力，不过任何能力总归是好的。 具备很少人能具备的那些方面的能力尤其好，其中具备 涉及脑力、技巧和专注方面能力的当然最好。

尊敬能力，你就会享受到提高自己能力的乐趣—— 辛苦的工作和奉献会变成一种高度娱乐而非苦差事。 要想成为一名黑客，这一点非常重要。

黑客的基本技能

黑客态度重要，但技术更加重要。 态度无法替代技术，在你被别的黑客称为黑客之前，有一些基本的技术你必须掌握。

这些基本技术随着新技术的出现和老技术的过时也随时间在缓慢改变。 例如，过去内容包括使用机器语言编程，而直到最近才包括了HTML。 总的来说现在主要包括以下技术：

1. 学习如何编程。

这当然是最基本的黑客技能。如果你还不会任何编程语言，我建议你从Python开始。 它设计清晰，文档齐全，合适初学者入门。 它是一门很好的入门语言，并且不仅仅只是个玩具； 它非常强大、灵活，也适合做大型项目。 我有一篇 Python评价详细说明这点。好的 教程 可以在Python网站得到。 （译者：比较好的中文Python站点可能是http://pythonrecord.51.net。）

Java也是好的入门语言。它比Python难得多，但是生成的代码速度也快得多。 它同时也是一种优秀的计算机语言，不止是用来入门。

但是注意，如果你只会一两门语言，你将不会达到黑客所要求的技术水平， 甚至也不能达到一个程序员的水平——你需要学会如何以抽象的方式思考编程问题， 独立于任何语言。要做一名真正的黑客，你需要学会在几天内通过一些手册， 结合你现在所知，迅速掌握一门新语言。这意味着你应该学会几种截然不同的语言。

如果要做一些重要的编程工作，你将不得不学习C语言，Unix的核心语言。 C++与C非常其他类似；如果你了解其中一种，学习另一种应该不难。 但这两种都不适合编程入门者学习。而且事实上，你越避免用C编程，你的工作效率会越高。

C非常有效率，节约你的机器资源。不幸的是，C的高效是通过你手动做很多底层的管理 （如内存）来达到的。底层代码都是复杂极易出现bug的，会使你花极多的时间调试。 如今的机器速度如此之快，这通常是得不偿失——比较明智的做法是使用一种运行较慢、较低 效率，但大幅节省你的时间的语言。因此，选择Python。

其他对黑客而言比较重要的语言包括 Perl和 LISP。 Perl实用，值得一学；它被广泛用于动态网页和系统管理， 因此即便你从不用Perl写程序，至少也应该学会看。许多人使用Perl的理由和 我建议你使用Python的理由一样，都是为了避免用C完成那些不需要C高效率的工作。 你会需要理解那些工作的代码的。

LISP值得学习的理由不同——最终掌握了它时你会得到丰富的启迪和经验。 这些经验会使你在以后的日子里成为一个更好的程序员，即使你实际上很少使用LISP本身。

当然，实际上你最好五种都会（Python，Java，C/C++，Perl和LISP）。 除了是最重要的黑客语言外，它们还代表了截然不同的编程思路和方法，每种都会让你受益非浅。

这里我无法给你完完全全的指导教会你如何编程——这是个复杂的技能。 但我可以告诉你，书本和上课也不能作到（最好的黑客中，有许多，也许 几乎都是自学成材的）。 你可以从书本上学到语言的特点——只是一些皮毛， 但要使书面知识成为自身技能只能通过实践和虚心向他人学习。 因此要作到 （一）读代码及（二）写代码。

学习如何编程就象学习用优美的自然语言写作一样。 最好的做法是读一些大师的名著，试着自己写点东西，再读些，再写点，再读些，再写点…… 如此往复，直到你的文章达到你体会到的范文的简洁和力量。

过去找到适合阅读的好的代码是困难的，因为几乎没有大型程序的源代码能让新手练手。 这种状况已经戏剧性地发生变化；开放源代码软件，编程工具和操作系统（全都由黑客写成）现在已经 随处可见。让我们在下一个话题中继续讨论……

2. 得到一个开放源代码的Unix并学会使用、运行它。

我假设你已经拥有或者能使用一台个人电脑（今天的孩子们真幸福 :-) ）。新手们能够朝学习黑客技能迈出的最基本的一步就是得到 一份Linux或BSD-Unix的一种，安装在个人电脑上，并运行它。

没错，这世界上除了Unix还有其他操作系统。 但它们都是以二进制形式发布的——你无法读到它的源代码，也不可能修改它。 尝试在运行DOS或Windows或MacOS的机器上学习黑客技术，就象是带着脚镣学跳舞。

除此之外，Unix还是Internet的操作系统。 你可以学会上网却不知道Unix，但你不了解Unix就无法成为一名Internet黑客。 因此，今天的黑客文化在很大程度上是以Unix为中心的。（这点并不总是真的， 一些很早的黑客对此一直很不高兴，但Unix和Internet之间的联系已是如此之强， 甚至连Microsoft也无可奈何。）

所以, 安装一套UNIX——我个人喜爱LINUX但还有其他种类的 （是的，你可以同时安装Linux及DOS/Windows在同一电脑上)。 学习它，使用它，配置它。用它在Internet上冲浪。阅读它的源代码。修改它的源代码。 你会得到比在Microsoft操作系统上更好的编程工具（包括C，LISP，Python及Perl）。 你会觉得乐趣无穷，学到在你成为大师之前意识不到的更多的知识。

想知道更多关于学习Unix的信息，访问 The Loginataka。

想知道如何得到一份Linux，访问 我在哪里可以获得Linux。 （译者：对于中文读者来讲，最简单的方式未过于前往附近的D版/正版光盘店。）

你可以在 www.bsd.org找到BSD Unix的求助及其他资源。

我有写一篇关于 Unix和Internet基础的入门文章。

（注：如果你是一个新手，我不推荐自己独立安装Linux或者BSD。 安装Linux的话，寻求本地Linux用户组的帮助；或联系 Open Projects Network。 LISC维护着一些 IRC频道， 在那里你可以获得帮助。）

3. 学会如何使用WWW和写HTML

黑客文化建造的大多东西都在你看不见的地方发挥着作用，帮助工厂、办公室和大学正常运转， 表面上很难看到它对非黑客的普通人的生活的影响。Web是一个大大的例外。 即便政客也同意，这个巨大耀眼的黑客玩具正在改变整个世界。 单是这个原因（还有许多其它的），你就需要学习掌握Web。

这并不是仅仅意味着如何使用浏览器（谁都会），而是要学会如何写HTML， Web的标记语言。如果你不会编程，写HTML会教你一些有助于学习的思考习惯。 因此，先完成一个主页。（网上有很多好的教程； 这是一个。)

但仅仅拥有一个主页不能使你成为一名黑客。 Web里充满了各种网页。大多数是毫无意义的，零信息量垃圾——界面时髦的垃圾， 注意，垃圾的水准都类似（更多信息访问 The HTML Hell Page）。

要想有价值，你的网页必须有内容—— 它必须有趣或对其它黑客有帮助。这是下一个话题所涉及的……

4. 如果你不懂实用性的英语，学习吧。

作为一个美国人和一个以英语为母语的人，我以前很不情愿提到这点，免得成为 一种文化上的帝国主义。但相当多以其他语言为母语的人一直劝我指出这一点，那就是 英语是黑客文化和Internet的工作语言，你需要懂得以便在黑客社区顺利工作。

这一点千真万确。大概1991年的时候我就了解到许多黑客在技术讨论中使用英语，甚至当他们的母语都 相同，英语对他们而言只是第二语言的时候；据我知道的报导，当前英语有着比其他语言丰富得多的技术词汇， 因此是一个对于工作来说相当好的工具。 基于类似的原因，英文技术书籍的翻译通常不令人满意（如果有翻译的话）。

Linus Torvalds，一个芬兰人，用英语注释他的代码（很明显这对他来说不是凑巧）。 他流利的英语成为他能够管理全球范围的Linux开发人员社区的重要因素。 这是一个值得学习的例子。

黑客文化中的地位

象大部分不涉及金钱的文化一样，黑客王国靠声誉运转。 你设法解决有趣的问题，但它们到底多有趣，你的解法有多好， 是要由那些和你具有同样技术水平的人或比你更厉害的人去评判的。

相应地，当你在玩黑客游戏时，你得认识到你的分数主要靠其他黑客对你的技术的评价给出 （这就是为什么只有在其它黑客称你为黑客时，你才算得上是一名黑客）。 这个事实常会被黑客是一项孤独的工作这一印象所减弱；也会被另一个黑客文化的禁忌所减弱 （现在逐渐减弱但仍强大）：拒绝承认自我或外部评估与一个人的动力有关系。

特别地，黑客王国被人类学家们称为一种奉献文化。 在这里你不是凭借你对别人的统治来建立地位和名望，也不是靠美貌，或拥有其他人想要的东西， 而是靠你的奉献。尤其是奉献你的时间，你的创造和你的技术成果。

要获得其他黑客的尊敬，基本上有五种事情你可以干：

1. 写开放源代码软件

第一个（也是最集中的和传统的）是写些被其他黑客认为有趣或有用的程序， 并把程序源代码提供给整个黑客文化使用。

（过去我们称之为“free software （自由软件）”， 但这却使很多不知 free 的精确含义的人感到困惑。 现在我们很多人，根据搜索引擎网页内容分析至少有2：1的比率，使用“ open-source”software（开放源代码软件）这个词）。

黑客王国里最受尊敬的偶像是那些写了大型的、好用的、具有广泛用途的软件， 并把它们公布出去，使得每人都在使用他软件的人。

2. 帮助测试并调试开放源代码软件

黑客也尊敬那些使用、测试开放源代码软件的人。 在这个并非完美的世界上，我们不可避免地要花大多数的开发时间在调试阶段。 这就是为什么任何有头脑的开放源代码的作者都会告诉你好的beta测试员 （知道如何清楚描述出错症状，很好地定位错误，能忍受快速发布中的bug， 并且愿意使用一些简单的诊断工具）象红宝石一样珍贵。 甚至他们中的一个能判断出哪个测试阶段是延长的， 哪个是令人精疲力尽的噩梦，哪个只是一个有益的小麻烦。

如果你是个新手，试着找一个你感兴趣的正在开发的程序，做一个好的beta测试员。 你会自然地从帮着测试，进步到帮着抓臭虫，到最后帮着改程序。 你会从中学到很多，并且与未来会帮你的人结下友谊。

3. 公布有用的信息

另一个好事是收集整理有用有趣的信息做成网页或文档如FAQ列表，且让他们容易获得。

主要技术FAQ的维护者受到几乎同其他开放源代码的作者一样多的尊敬。

4. 帮助维护基础设施的运转

黑客文化（还有Internet的工程方面的发展，就此而言）是靠自愿者运转的。 要使Internet能正常工作，就要有大量枯燥的工作不得不去完成——管理mail list，新闻组，维护大型软件库，开发RFC和其它技术标准等等。

做这类事情的人会得到很多尊敬，因为每人都知道这些事情是十分花时间又不象编程那样好玩。 做这些事情需要奉献精神。

5. 为黑客文化本身服务

最后，你可以为这个文化本身做宣传（例如，象我这样，写一个“如何成为黑客”的正面的教程 :-) ） （译者：不知道Barret把它翻成中文算不算？）。 这并非一定要在你已经在这个圈子呆了很久，因以上四点中的某点而出名，有一定声誉后才能去做。

黑客文化没有领袖。精确地说，它确实有些文化英雄、部落长者、历史学家和发言人。 若你在这圈内呆的够长，你或许成为其中之一。 记住：黑客们不相信他们的部落长者的自夸的炫耀， 因此大举追求这种名誉是危险的。与其奋力追求，不如先摆正自己的位置 等它自己到你的手中——那时则要做到谦虚和优雅。

黑客和书呆子(Nerd)的联系

同流行的迷思相反，做一名黑客并不一定要你是个书呆子。 但它确实有帮助，而且许多黑客事实上是书呆子。 做一个深居简出的人有助于你集中精力进行十分重要的事情，如思考和编程。

因此，很多黑客都愿意接受“书呆子”这个外号， 更有甚者使用更尖刻的“geek（怪人）”一词并引以为豪—— 这是一种宣布他们独立于主流社会的声明方式。访问 The Geek Page 参加更多的讨论。

如果你能集中足够的精力做好黑客工作同时还能有正常的生活，这很好。 现在作到这一点比我在1970年代是新手的时候要容易的多； 如今主流文化对技术怪人要友善的多。 甚至有越来越多的人意识到黑客通常是很好的恋人和配偶的材料。

如果你因为生活上不如意而迷上做黑客，那也没什么——至少你不会分神了。 或许以后你会找到自己的另一半。

风格的意义

重申一下，作为一名黑客，你必须进入黑客精神之中。 当你不在计算机边上时，你仍然有很多对黑客工作有帮助的事情可做。 它们并不能替代真正的编程（没有什么能），但很多黑客都那么做， 并感到它们与黑客的本质存在某些基本的连系。

学会流畅地用母语写作。尽管程序员不能写好文章的错误看法相当普遍， 但是有令人惊讶数目的黑客（包括所有我知道的最棒的）都是不错的作家。

阅读科幻小说。参加科幻小说讨论会。（一个碰到黑客和未来会成为黑客的人的好方法）

学禅，并且/或者练功习武。（精神修炼看来是惊人相似。）

练就能分析音乐的听觉，学会鉴赏特别的音乐。学会玩某种乐器，或唱歌。

提高对双关语、文字游戏的鉴赏能力。

这些事情，你已经做的越多，你就越是天生做黑客的材料。 至于为什么偏偏是这些事情，原因并不完全清楚， 但它们都涉及用到左－右脑能力的综合，这似乎是关键所在 （黑客们既需要清晰的逻辑思维，有时又需要偏离逻辑跳出问题的表象）。

最后，还有一些不要去做的事情。

不要使用愚蠢的，哗众取宠的ID或昵称。

不要卷入Usenet（或其他地方的论坛）的骂战。

不要自称为“cyberpunk（网络叛客）”，也不要浪费时间和那些人打交道。

不要让你寄出的Email或张贴的帖子充满错误的拼写和乱七八糟的语法。

做以上的事情，只会招来嘲笑。黑客们个个记忆超群—— 你将需要数年的时间让他们忘记你犯下的错误。

网名的问题值得深思。将身份隐藏在虚假的名字后是骇客、解密者、d00dz 及其他低等生物幼稚愚蠢的行为特点。黑客不会做这些事； 他们对他们所作的感到骄傲，而且乐于人们将作品与他们的 真名相联系。 因此, 若你现在用假名，放弃它。在黑客文化里它会令你你失败的。

其它资源

Peter Seebach 维护着一个非常好的 Hacker FAQ， 专给那些不懂如何与黑客打交道的经理看的。如果Peter的站点不能访问，下面这个 Excite搜索应该有一份拷贝。

我也著有 黑客文化简史。

我写了一份 大教堂与市集，对于Linux及开放源代码文化现象有详细的解释。 我也在这个话题上进一步阐述导致的结局—— 开拓智域。

Rick Moen写了一份很好的关于 如何运转一个Linux用户组的文档。

我和Rick Moen合作完成了另一份关于 提问的智慧的文章，可以让你事半功倍的获得帮助。

如果你想知道PC、UNIX及Internet基本概念和工作原理，参考 The Unix and Internet Fundamentals HOWTO。

当你释放出一个软件或为其打补丁，试着按 软件发行惯例 HOWTO去做。 （以上的提到的文章的中文版大多都可以在www.aka.org.cn和www.linuxforum.net找到。）

FAQ（常问问题解答）

问：你能教我做黑客吗？
问：那么，我要如何开始？
问：我得什么时候开始学？现在会不会太迟了？
问：要学多久才能学会黑客道？
问：Visual Basic及Delphi是好的入门语言吗？
问：你能帮我“黑”掉一个站点吗？或者教我怎么黑它？
问：我怎么样才能得到别人帐号的密码？
问：我如何入侵/查看/监视别人的Email？
问：我如何才能在IRC聊天室里偷到频道op的特权？
问：我被黑了。你能帮我避免以后再被攻击吗？
问：我的Windows软件出现问题了。你能帮我吗？
问：我在哪里能找到可以与之交流的真正的黑客？
问：你能推荐一些有关黑客的好书吗？
问：成为一名黑客我需要擅长数学吗？
问：我该从那种语言学起？
问：我需要什么样的机器配置？
问：我得因此憎恨和反对Microsoft吗？
问：但开放源代码软件不会使程序员丢饭碗吗？
问：我要如何开始？哪里有免费的Unix？
问：你能教我做黑客吗？

答：自从第一次发布这份文档，我每周都会收到一些请求， （频繁的话一天几封）要我“教会他们做黑客”。遗憾的是，我 没有时间和精力来做这个；我自己的黑客项目，及我作为一个开放源代码倡导者 的四处奔波已经占用了我110%的时间。

即便我想教你，黑客也依然基本上是一项自行修炼的的态度和技术。 当真正的黑客想帮助你的时候，如果你乞求他们一汤匙一汤匙“喂”你的话， 你会发现他们不会尊重你。

先去学一些东西。显示你在尝试，你能靠自己去学习。然后再去向你遇到的黑客请教特殊的问题。

如果你发E-mail给一位黑客寻求他的帮助，这是两件首要记住的事情。 第一，写出来的文字显得懒且粗心的人通常非常懒于思考且非常马大哈，不能成为好黑客—— 因此注意拼写正确，使用正确的语法及发音，否则你可能会无人理睬。 第二，不要试图要求回复到一个ISP帐号，而那个帐号与你 的发信地址不同。这样做的人一般是使用盗用帐号，不会有人有兴趣为虎作伥帮助窃贼的。

问：那么，我要如何开始？

答：对你而言最佳的入门方式也许是去参加LUG（Linux用户组）的聚会。 你可以找到在 LDP的综合Linux信息页面上找到类似的组织；也许有一个在你家附近的， 而且非常有可能与一所大学或学校挂钩。如果你提出要求，LUG成员兴许会给你一套Linux， 当然此后会帮你安装并带你入门。

问：我得什么时候开始学？现在会不会太迟了？

答：你有动力学习的时候就是好时候。大多数人看来都是在15－20岁之间开始感兴趣的，但 据我所知，在此年龄段之外的例外也是有的。

问：要学多久才能学会黑客道？

答：这取决于你的聪明程度和努力程度。大多数人只要他们专注， 就能在18个月到2年之间学会一套令人尊敬的技能。但是，不要以为就此结束了； 如果你是一个真正的黑客，你要用你的余生来学习和完善你的技术。

问：Visual Basic及Delphi是好的入门语言吗？

答：不，因为他们不是可移植的。他们不是那些语言的开放源代码实现， 所以你被限制在厂商选择支持的那些平台里。接受这样一种垄断局面不是黑客的态度。

Visual Basic特别糟糕。它是Microsoft的私有语言这个事实就足够让它脸面全无， 不像其他的Basic，它是一种设计糟糕的语言会教给你坏的编程习惯。

其中一个坏习惯是会依赖于单一厂商的函数库、控件及开发工具。 一般而言，任何不能够支持至少Linux或者一种BSD，或其他第三方操作系统的语言，都是 一种不适合应付黑客工作的语言。

问：你能帮我“黑”掉一个站点吗？或者教我怎么黑它？

答：No。任何读完这份FAQ后还问这个问题的人，都是无可救药的蠢材， 即使有时间指教我也不会理睬。任何发给我的此类E-mail都会被忽略或被痛骂一顿。

问：我怎么样才能得到别人帐号的密码？

答：这是骇客行为。滚得远远的，白痴。

问：我如何入侵/查看/监视别人的Email？

答：这是骇客行为。在我面前消失，混蛋。

问：我如何才能在IRC聊天室里偷到频道op的特权？

答：这是骇客行为。去S吧，冥顽不灵的家伙。

问：我被黑了。你能帮我避免以后再被攻击吗？

答：不行。目前为止，每次问我这个问题的，都是一些运行Microsoft Windows的菜鸟。 不可能有效的保护Windows系统免受骇客攻击；太多缺陷的代码和架构使保护Windows的努力有如 隔靴搔痒。唯一可靠的预防来自转移到Linux或其他设计得至少足够安全的系统。

问：我的Windows软件出现问题了。你能帮我吗？

答：当然。进入DOS方式，然后键入“format c:”。你遇到的任何问题将会在几分钟之内消失。

问：我在哪里能找到可以与之交流的真正的黑客？

答：最佳办法是在你附近找一个Unix或Linux的用户组，参加他们的聚会。 （你可以在Metalab的LDP站点 找到一些指向用户组的链接。）

我过去曾说过不能在IRC上找到真正的黑客，但我发觉现在情况有所改变。 显然一些真正的黑客的社区像GIMP及Perl，也有IRC频道了。）

问：你能推荐一些有关黑客的好书吗？

答：我维护着一份Linux Reading List HOWTO，也许你会觉得有用。 Loginataka也很有意思。

关于Python的介绍，请访问在Python站点上的 入门资料。

问：成为一名黑客我需要擅长数学吗？

答：不用。黑客道很少使用常规的数学或算术，不过你绝对需要能逻辑性地思考和进行精密的推理。

尤其是你不会用到微积分或电路分析（我们把这些留给电子工程师们 :-)）。 一些有限数学（包括布尔代数，集合论，组合数学，图论）的背景知识会有帮助。

问：我该从那种语言学起？

答：HTML——如果你还不懂的话。市面上有一大堆的封面精美，宣传得天花乱坠的 糟糕的 HTML书籍，不幸的是很少有好的。我最喜欢的是 HTML: The Definitive Guide。

但 HTML 不完全是一种编程语言。当你准备开始编程时，我推荐从 Python起步。 你会听到一大群人推荐 Perl，并且 Perl 依然比 Python 流行得多，但是 难学得多且（以我之见）设计得不是很好。

C 确实重要，但它要比 Python 或 Perl 难多了。不要尝试先学 C。

Windows用户不要满足于 Visual Basic。 它会教给你坏习惯，而且它不可以移植，只能在Windows下运行。避免它。

问：我需要什么样的机器配置？

答：过去个人电脑能力相当不够并且内存小，结果给黑客的学习过程设置 了人为的障碍。不过一段时间以前开始就不是这样了；任何配置比一台 Intel 486DX50 好的 机器都有足够的能力进行开发工作，X，及 Internet 通讯，同时你现在买的最小的磁盘 都大得富足了。（依Barret之见，现在要至少Pentium 166MMX才够。）

选择用来学习的机器时重要的一点是注意配件是否是Linux兼容的（或BSD兼容，如果你选择学 BSD）。同刚才提到的一样，大多数现在的机器都是符合的；唯一的值得注意的区域在于 modem和打印机；有些具备为Windows设计的配件的机器不会在Linux下工作。

关于硬件兼容性有一个FAQ；最新版本在 这里。

问：我得因此憎恨和反对Microsoft吗？

答：不，你不必如此。不是因为Microsoft不令人讨厌，而是因为黑客文化早在 Microsoft出现之前就存在了，且将在Microsoft成为历史后依然存在。 你耗费在憎恨Microsoft的任何力气不如花在爱你的技术上。写好的代码—— 那会相当有效地打击Microsoft又不会让你得到恶报应。

问：但开放源代码软件不会使程序员丢饭碗吗？

答：看起来不太可能——目前为止，开放源代码软件产业似乎创造了更多的就业机会而不是 减少就业机会。如果写一个程序比起不写来是纯经济收益的话，那么在写完后， 程序员应该得到报酬不管程序是否是开放源代码。 并且，无论写出多么“免费自由”的软件，都存在更多对新的，定制的软件的需求。 我有这方面更多的论述，放在开放源代码 网站资料中。

问：我要如何开始？哪里有免费的Unix？

答：在本份文档的某个地方我已经提到过何处可以得到最常用的免费Unix。 要做一名黑客，你需要自立自强，以及自学能力。现在开始吧……


How To Become A Hacker

Eric Steven Raymond

Thyrsus Enterprises

    <esr@thyrsus.com>
    

Copyright © 2001 Eric S. Raymond

Revision History
Revision 1.42	22 Oct 2010	esr
Added "Historical note".
Revision 1.40	3 Nov 2008	esr
Link fixes.
Revision 1.39	14 Aug Jan 2008	esr
Link fixes.
Revision 1.38	8 Jan 2008	esr
Deprecate Java as a language to learn early.
Revision 1.37	4 Oct 2007	esr
Recommend Ubuntu as a Unix distro for newbies.
Table of Contents

Why This Document?
What Is a Hacker?
The Hacker Attitude
1. The world is full of fascinating problems waiting to be solved.
2. No problem should ever have to be solved twice.
3. Boredom and drudgery are evil.
4. Freedom is good.
5. Attitude is no substitute for competence.
Basic Hacking Skills
1. Learn how to program.
2. Get one of the open-source Unixes and learn to use and run it.
3. Learn how to use the World Wide Web and write HTML.
4. If you don't have functional English, learn it.
Status in the Hacker Culture
1. Write open-source software
2. Help test and debug open-source software
3. Publish useful information
4. Help keep the infrastructure working
5. Serve the hacker culture itself
The Hacker/Nerd Connection
Points For Style
Historical Note: Hacking, Open Source, and Free Software
Other Resources
Frequently Asked Questions

Why This Document?

As editor of the Jargon File and author of a few other well-known documents of similar nature, I often get email requests from enthusiastic network newbies asking (in effect) "how can I learn to be a wizardly hacker?". Back in 1996 I noticed that there didn't seem to be any other FAQs or web documents that addressed this vital question, so I started this one. A lot of hackers now consider it definitive, and I suppose that means it is. Still, I don't claim to be the exclusive authority on this topic; if you don't like what you read here, write your own.

If you are reading a snapshot of this document offline, the current version lives at http://catb.org/~esr/faqs/hacker-howto.html.

Note: there is a list of Frequently Asked Questions at the end of this document. Please read these—twice—before mailing me any questions about this document.

Numerous translations of this document are available: Arabic Bulgarian, Catalan, Chinese (Simplified), Danish, Dutch, Estonian, Farsi, Finnish, German, Greek Hebrew, Italian Japanese, Norwegian, Polish, Portuguese (Brazilian), Romanian Russian Spanish, Turkish, and Swedish. Note that since this document changes occasionally, they may be out of date to varying degrees.

The five-dots-in-nine-squares diagram that decorates this document is called a glider. It is a simple pattern with some surprising properties in a mathematical simulation called Life that has fascinated hackers for many years. I think it makes a good visual emblem for what hackers are like — abstract, at first a bit mysterious-seeming, but a gateway to a whole world with an intricate logic of its own. Read more about the glider emblem here.

What Is a Hacker?

The Jargon File contains a bunch of definitions of the term ‘hacker’, most having to do with technical adeptness and a delight in solving problems and overcoming limits. If you want to know how to become a hacker, though, only two are really relevant.

There is a community, a shared culture, of expert programmers and networking wizards that traces its history back through decades to the first time-sharing minicomputers and the earliest ARPAnet experiments. The members of this culture originated the term ‘hacker’. Hackers built the Internet. Hackers made the Unix operating system what it is today. Hackers run Usenet. Hackers make the World Wide Web work. If you are part of this culture, if you have contributed to it and other people in it know who you are and call you a hacker, you're a hacker.

The hacker mind-set is not confined to this software-hacker culture. There are people who apply the hacker attitude to other things, like electronics or music — actually, you can find it at the highest levels of any science or art. Software hackers recognize these kindred spirits elsewhere and may call them ‘hackers’ too — and some claim that the hacker nature is really independent of the particular medium the hacker works in. But in the rest of this document we will focus on the skills and attitudes of software hackers, and the traditions of the shared culture that originated the term ‘hacker’.

There is another group of people who loudly call themselves hackers, but aren't. These are people (mainly adolescent males) who get a kick out of breaking into computers and phreaking the phone system. Real hackers call these people ‘crackers’ and want nothing to do with them. Real hackers mostly think crackers are lazy, irresponsible, and not very bright, and object that being able to break security doesn't make you a hacker any more than being able to hotwire cars makes you an automotive engineer. Unfortunately, many journalists and writers have been fooled into using the word ‘hacker’ to describe crackers; this irritates real hackers no end.

The basic difference is this: hackers build things, crackers break them.

If you want to be a hacker, keep reading. If you want to be a cracker, go read the alt.2600 newsgroup and get ready to do five to ten in the slammer after finding out you aren't as smart as you think you are. And that's all I'm going to say about crackers.


The Hacker Attitude

1. The world is full of fascinating problems waiting to be solved.
2. No problem should ever have to be solved twice.
3. Boredom and drudgery are evil.
4. Freedom is good.
5. Attitude is no substitute for competence.
Hackers solve problems and build things, and they believe in freedom and voluntary mutual help. To be accepted as a hacker, you have to behave as though you have this kind of attitude yourself. And to behave as though you have the attitude, you have to really believe the attitude.

But if you think of cultivating hacker attitudes as just a way to gain acceptance in the culture, you'll miss the point. Becoming the kind of person who believes these things is important for you — for helping you learn and keeping you motivated. As with all creative arts, the most effective way to become a master is to imitate the mind-set of masters — not just intellectually but emotionally as well.

Or, as the following modern Zen poem has it:


    To follow the path:
    look to the master,
    follow the master,
    walk with the master,
    see through the master,
    become the master.
So, if you want to be a hacker, repeat the following things until you believe them:

1. The world is full of fascinating problems waiting to be solved.

Being a hacker is lots of fun, but it's a kind of fun that takes lots of effort. The effort takes motivation. Successful athletes get their motivation from a kind of physical delight in making their bodies perform, in pushing themselves past their own physical limits. Similarly, to be a hacker you have to get a basic thrill from solving problems, sharpening your skills, and exercising your intelligence.

If you aren't the kind of person that feels this way naturally, you'll need to become one in order to make it as a hacker. Otherwise you'll find your hacking energy is sapped by distractions like sex, money, and social approval.

(You also have to develop a kind of faith in your own learning capacity — a belief that even though you may not know all of what you need to solve a problem, if you tackle just a piece of it and learn from that, you'll learn enough to solve the next piece — and so on, until you're done.)

2. No problem should ever have to be solved twice.

Creative brains are a valuable, limited resource. They shouldn't be wasted on re-inventing the wheel when there are so many fascinating new problems waiting out there.

To behave like a hacker, you have to believe that the thinking time of other hackers is precious — so much so that it's almost a moral duty for you to share information, solve problems and then give the solutions away just so other hackers can solve new problems instead of having to perpetually re-address old ones.

Note, however, that "No problem should ever have to be solved twice." does not imply that you have to consider all existing solutions sacred, or that there is only one right solution to any given problem. Often, we learn a lot about the problem that we didn't know before by studying the first cut at a solution. It's OK, and often necessary, to decide that we can do better. What's not OK is artificial technical, legal, or institutional barriers (like closed-source code) that prevent a good solution from being re-used and force people to re-invent wheels.

(You don't have to believe that you're obligated to give all your creative product away, though the hackers that do are the ones that get most respect from other hackers. It's consistent with hacker values to sell enough of it to keep you in food and rent and computers. It's fine to use your hacking skills to support a family or even get rich, as long as you don't forget your loyalty to your art and your fellow hackers while doing it.)

3. Boredom and drudgery are evil.

Hackers (and creative people in general) should never be bored or have to drudge at stupid repetitive work, because when this happens it means they aren't doing what only they can do — solve new problems. This wastefulness hurts everybody. Therefore boredom and drudgery are not just unpleasant but actually evil.

To behave like a hacker, you have to believe this enough to want to automate away the boring bits as much as possible, not just for yourself but for everybody else (especially other hackers).

(There is one apparent exception to this. Hackers will sometimes do things that may seem repetitive or boring to an observer as a mind-clearing exercise, or in order to acquire a skill or have some particular kind of experience you can't have otherwise. But this is by choice — nobody who can think should ever be forced into a situation that bores them.)

4. Freedom is good.

Hackers are naturally anti-authoritarian. Anyone who can give you orders can stop you from solving whatever problem you're being fascinated by — and, given the way authoritarian minds work, will generally find some appallingly stupid reason to do so. So the authoritarian attitude has to be fought wherever you find it, lest it smother you and other hackers.

(This isn't the same as fighting all authority. Children need to be guided and criminals restrained. A hacker may agree to accept some kinds of authority in order to get something he wants more than the time he spends following orders. But that's a limited, conscious bargain; the kind of personal surrender authoritarians want is not on offer.)

Authoritarians thrive on censorship and secrecy. And they distrust voluntary cooperation and information-sharing — they only like ‘cooperation’ that they control. So to behave like a hacker, you have to develop an instinctive hostility to censorship, secrecy, and the use of force or deception to compel responsible adults. And you have to be willing to act on that belief.

5. Attitude is no substitute for competence.

To be a hacker, you have to develop some of these attitudes. But copping an attitude alone won't make you a hacker, any more than it will make you a champion athlete or a rock star. Becoming a hacker will take intelligence, practice, dedication, and hard work.

Therefore, you have to learn to distrust attitude and respect competence of every kind. Hackers won't let posers waste their time, but they worship competence — especially competence at hacking, but competence at anything is valued. Competence at demanding skills that few can master is especially good, and competence at demanding skills that involve mental acuteness, craft, and concentration is best.

If you revere competence, you'll enjoy developing it in yourself — the hard work and dedication will become a kind of intense play rather than drudgery. That attitude is vital to becoming a hacker.


Basic Hacking Skills

1. Learn how to program.
2. Get one of the open-source Unixes and learn to use and run it.
3. Learn how to use the World Wide Web and write HTML.
4. If you don't have functional English, learn it.
The hacker attitude is vital, but skills are even more vital. Attitude is no substitute for competence, and there's a certain basic toolkit of skills which you have to have before any hacker will dream of calling you one.

This toolkit changes slowly over time as technology creates new skills and makes old ones obsolete. For example, it used to include programming in machine language, and didn't until recently involve HTML. But right now it pretty clearly includes the following:

1. Learn how to program.

This, of course, is the fundamental hacking skill. If you don't know any computer languages, I recommend starting with Python. It is cleanly designed, well documented, and relatively kind to beginners. Despite being a good first language, it is not just a toy; it is very powerful and flexible and well suited for large projects. I have written a more detailed evaluation of Python. Good tutorials are available at the Python web site.

I used to recommend Java as a good language to learn early, but this critique has changed my mind (search for “The Pitfalls of Java as a First Programming Language” within it). A hacker cannot, as they devastatingly put it “approach problem-solving like a plumber in a hardware store”; you have to know what the components actually do. Now I think it is probably best to learn C and Lisp first, then Java.

There is perhaps a more general point here. If a language does too much for you, it may be simultaneously a good tool for production and a bad one for learning. It's not only languages that have this problem; web application frameworks like RubyOnRails, CakePHP, Django may make it too easy to reach a superficial sort of understanding that will leave you without resources when you have to tackle a hard problem, or even just debug the solution to an easy one.

If you get into serious programming, you will have to learn C, the core language of Unix. C++ is very closely related to C; if you know one, learning the other will not be difficult. Neither language is a good one to try learning as your first, however. And, actually, the more you can avoid programming in C the more productive you will be.

C is very efficient, and very sparing of your machine's resources. Unfortunately, C gets that efficiency by requiring you to do a lot of low-level management of resources (like memory) by hand. All that low-level code is complex and bug-prone, and will soak up huge amounts of your time on debugging. With today's machines as powerful as they are, this is usually a bad tradeoff — it's smarter to use a language that uses the machine's time less efficiently, but your time much more efficiently. Thus, Python.

Other languages of particular importance to hackers include Perl and LISP. Perl is worth learning for practical reasons; it's very widely used for active web pages and system administration, so that even if you never write Perl you should learn to read it. Many people use Perl in the way I suggest you should use Python, to avoid C programming on jobs that don't require C's machine efficiency. You will need to be able to understand their code.

LISP is worth learning for a different reason — the profound enlightenment experience you will have when you finally get it. That experience will make you a better programmer for the rest of your days, even if you never actually use LISP itself a lot. (You can get some beginning experience with LISP fairly easily by writing and modifying editing modes for the Emacs text editor, or Script-Fu plugins for the GIMP.)

It's best, actually, to learn all five of Python, C/C++, Java, Perl, and LISP. Besides being the most important hacking languages, they represent very different approaches to programming, and each will educate you in valuable ways.

But be aware that you won't reach the skill level of a hacker or even merely a programmer simply by accumulating languages — you need to learn how to think about programming problems in a general way, independent of any one language. To be a real hacker, you need to get to the point where you can learn a new language in days by relating what's in the manual to what you already know. This means you should learn several very different languages.

I can't give complete instructions on how to learn to program here — it's a complex skill. But I can tell you that books and courses won't do it — many, maybe most of the best hackers are self-taught. You can learn language features — bits of knowledge — from books, but the mind-set that makes that knowledge into living skill can be learned only by practice and apprenticeship. What will do it is (a) reading code and (b) writing code.

Peter Norvig, who is one of Google's top hackers and the co-author of the most widely used textbook on AI, has written an excellent essay called Teach Yourself Programming in Ten Years. His "recipe for programming success" is worth careful attention.

Learning to program is like learning to write good natural language. The best way to do it is to read some stuff written by masters of the form, write some things yourself, read a lot more, write a little more, read a lot more, write some more ... and repeat until your writing begins to develop the kind of strength and economy you see in your models.

Finding good code to read used to be hard, because there were few large programs available in source for fledgeling hackers to read and tinker with. This has changed dramatically; open-source software, programming tools, and operating systems (all built by hackers) are now widely available. Which brings me neatly to our next topic...

2. Get one of the open-source Unixes and learn to use and run it.

I'll assume you have a personal computer or can get access to one. (Take a moment to appreciate how much that means. The hacker culture originally evolved back when computers were so expensive that individuals could not own them.) The single most important step any newbie can take toward acquiring hacker skills is to get a copy of Linux or one of the BSD-Unixes or OpenSolaris, install it on a personal machine, and run it.

Yes, there are other operating systems in the world besides Unix. But they're distributed in binary — you can't read the code, and you can't modify it. Trying to learn to hack on a Microsoft Windows machine or under any other closed-source system is like trying to learn to dance while wearing a body cast.

Under Mac OS X it's possible, but only part of the system is open source — you're likely to hit a lot of walls, and you have to be careful not to develop the bad habit of depending on Apple's proprietary code. If you concentrate on the Unix under the hood you can learn some useful things.

Unix is the operating system of the Internet. While you can learn to use the Internet without knowing Unix, you can't be an Internet hacker without understanding Unix. For this reason, the hacker culture today is pretty strongly Unix-centered. (This wasn't always true, and some old-time hackers still aren't happy about it, but the symbiosis between Unix and the Internet has become strong enough that even Microsoft's muscle doesn't seem able to seriously dent it.)

So, bring up a Unix — I like Linux myself but there are other ways (and yes, you can run both Linux and Microsoft Windows on the same machine). Learn it. Run it. Tinker with it. Talk to the Internet with it. Read the code. Modify the code. You'll get better programming tools (including C, LISP, Python, and Perl) than any Microsoft operating system can dream of hosting, you'll have fun, and you'll soak up more knowledge than you realize you're learning until you look back on it as a master hacker.

For more about learning Unix, see The Loginataka. You might also want to have a look at The Art Of Unix Programming.

To get your hands on a Linux, see the Linux Online! site; you can download from there or (better idea) find a local Linux user group to help you with installation.

During the first ten years of this HOWTO's life, I reported that from a new user's point of view, all Linux distributions are almost equivalent. But in 2006-2007, an actual best choice emerged: Ubuntu. While other distros have their own areas of strength, Ubuntu is far and away the most accessible to Linux newbies.

You can find BSD Unix help and resources at www.bsd.org.

A good way to dip your toes in the water is to boot up what Linux fans call a live CD, a distribution that runs entirely off a CD without having to modify your hard disk. This will be slow, because CDs are slow, but it's a way to get a look at the possibilities without having to do anything drastic.

I have written a primer on the basics of Unix and the Internet.

I used to recommend against installing either Linux or BSD as a solo project if you're a newbie. Nowadays the installers have gotten good enough that doing it entirely on your own is possible, even for a newbie. Nevertheless, I still recommend making contact with your local Linux user's group and asking for help. It can't hurt, and may smooth the process.

3. Learn how to use the World Wide Web and write HTML.

Most of the things the hacker culture has built do their work out of sight, helping run factories and offices and universities without any obvious impact on how non-hackers live. The Web is the one big exception, the huge shiny hacker toy that even politicians admit has changed the world. For this reason alone (and a lot of other good ones as well) you need to learn how to work the Web.

This doesn't just mean learning how to drive a browser (anyone can do that), but learning how to write HTML, the Web's markup language. If you don't know how to program, writing HTML will teach you some mental habits that will help you learn. So build a home page. Try to stick to XHTML, which is a cleaner language than classic HTML. (There are good beginner tutorials on the Web; here's one.)

But just having a home page isn't anywhere near good enough to make you a hacker. The Web is full of home pages. Most of them are pointless, zero-content sludge — very snazzy-looking sludge, mind you, but sludge all the same (for more on this see The HTML Hell Page).

To be worthwhile, your page must have content — it must be interesting and/or useful to other hackers. And that brings us to the next topic...

4. If you don't have functional English, learn it.

As an American and native English-speaker myself, I have previously been reluctant to suggest this, lest it be taken as a sort of cultural imperialism. But several native speakers of other languages have urged me to point out that English is the working language of the hacker culture and the Internet, and that you will need to know it to function in the hacker community.

Back around 1991 I learned that many hackers who have English as a second language use it in technical discussions even when they share a birth tongue; it was reported to me at the time that English has a richer technical vocabulary than any other language and is therefore simply a better tool for the job. For similar reasons, translations of technical books written in English are often unsatisfactory (when they get done at all).

Linus Torvalds, a Finn, comments his code in English (it apparently never occurred to him to do otherwise). His fluency in English has been an important factor in his ability to recruit a worldwide community of developers for Linux. It's an example worth following.

Being a native English-speaker does not guarantee that you have language skills good enough to function as a hacker. If your writing is semi-literate, ungrammatical, and riddled with misspellings, many hackers (including myself) will tend to ignore you. While sloppy writing does not invariably mean sloppy thinking, we've generally found the correlation to be strong — and we have no use for sloppy thinkers. If you can't yet write competently, learn to.


Status in the Hacker Culture

1. Write open-source software
2. Help test and debug open-source software
3. Publish useful information
4. Help keep the infrastructure working
5. Serve the hacker culture itself
Like most cultures without a money economy, hackerdom runs on reputation. You're trying to solve interesting problems, but how interesting they are, and whether your solutions are really good, is something that only your technical peers or superiors are normally equipped to judge.

Accordingly, when you play the hacker game, you learn to keep score primarily by what other hackers think of your skill (this is why you aren't really a hacker until other hackers consistently call you one). This fact is obscured by the image of hacking as solitary work; also by a hacker-cultural taboo (gradually decaying since the late 1990s but still potent) against admitting that ego or external validation are involved in one's motivation at all.

Specifically, hackerdom is what anthropologists call a gift culture. You gain status and reputation in it not by dominating other people, nor by being beautiful, nor by having things other people want, but rather by giving things away. Specifically, by giving away your time, your creativity, and the results of your skill.

There are basically five kinds of things you can do to be respected by hackers:

1. Write open-source software

The first (the most central and most traditional) is to write programs that other hackers think are fun or useful, and give the program sources away to the whole hacker culture to use.

(We used to call these works “free software”, but this confused too many people who weren't sure exactly what “free” was supposed to mean. Most of us now prefer the term “open-source” software).

Hackerdom's most revered demigods are people who have written large, capable programs that met a widespread need and given them away, so that now everyone uses them.

But there's a bit of a fine historical point here. While hackers have always looked up to the open-source developers among them as our community's hardest core, before the mid-1990s most hackers most of the time worked on closed source. This was still true when I wrote the first version of this HOWTO in 1996; it took the mainstreaming of open-source software after 1997 to change things. Today, "the hacker community" and "open-source developers" are two descriptions for what is essentially the same culture and population — but it is worth remembering that this was not always so. (For more on this, see the section called “Historical Note: Hacking, Open Source, and Free Software”.)

2. Help test and debug open-source software

They also serve who stand and debug open-source software. In this imperfect world, we will inevitably spend most of our software development time in the debugging phase. That's why any open-source author who's thinking will tell you that good beta-testers (who know how to describe symptoms clearly, localize problems well, can tolerate bugs in a quickie release, and are willing to apply a few simple diagnostic routines) are worth their weight in rubies. Even one of these can make the difference between a debugging phase that's a protracted, exhausting nightmare and one that's merely a salutary nuisance.

If you're a newbie, try to find a program under development that you're interested in and be a good beta-tester. There's a natural progression from helping test programs to helping debug them to helping modify them. You'll learn a lot this way, and generate good karma with people who will help you later on.

3. Publish useful information

Another good thing is to collect and filter useful and interesting information into web pages or documents like Frequently Asked Questions (FAQ) lists, and make those generally available.

Maintainers of major technical FAQs get almost as much respect as open-source authors.

4. Help keep the infrastructure working

The hacker culture (and the engineering development of the Internet, for that matter) is run by volunteers. There's a lot of necessary but unglamorous work that needs done to keep it going — administering mailing lists, moderating newsgroups, maintaining large software archive sites, developing RFCs and other technical standards.

People who do this sort of thing well get a lot of respect, because everybody knows these jobs are huge time sinks and not as much fun as playing with code. Doing them shows dedication.

5. Serve the hacker culture itself

Finally, you can serve and propagate the culture itself (by, for example, writing an accurate primer on how to become a hacker :-)). This is not something you'll be positioned to do until you've been around for while and become well-known for one of the first four things.

The hacker culture doesn't have leaders, exactly, but it does have culture heroes and tribal elders and historians and spokespeople. When you've been in the trenches long enough, you may grow into one of these. Beware: hackers distrust blatant ego in their tribal elders, so visibly reaching for this kind of fame is dangerous. Rather than striving for it, you have to sort of position yourself so it drops in your lap, and then be modest and gracious about your status.


The Hacker/Nerd Connection

Contrary to popular myth, you don't have to be a nerd to be a hacker. It does help, however, and many hackers are in fact nerds. Being something of a social outcast helps you stay concentrated on the really important things, like thinking and hacking.

For this reason, many hackers have adopted the label ‘geek’ as a badge of pride — it's a way of declaring their independence from normal social expectations (as well as a fondness for other things like science fiction and strategy games that often go with being a hacker). The term 'nerd' used to be used this way back in the 1990s, back when 'nerd' was a mild pejorative and 'geek' a rather harsher one; sometime after 2000 they switched places, at least in U.S. popular culture, and there is now even a significant geek-pride culture among people who aren't techies.

If you can manage to concentrate enough on hacking to be good at it and still have a life, that's fine. This is a lot easier today than it was when I was a newbie in the 1970s; mainstream culture is much friendlier to techno-nerds now. There are even growing numbers of people who realize that hackers are often high-quality lover and spouse material.

If you're attracted to hacking because you don't have a life, that's OK too — at least you won't have trouble concentrating. Maybe you'll get a life later on.


Points For Style

Again, to be a hacker, you have to enter the hacker mindset. There are some things you can do when you're not at a computer that seem to help. They're not substitutes for hacking (nothing is) but many hackers do them, and feel that they connect in some basic way with the essence of hacking.

Learn to write your native language well. Though it's a common stereotype that programmers can't write, a surprising number of hackers (including all the most accomplished ones I know of) are very able writers.

Read science fiction. Go to science fiction conventions (a good way to meet hackers and proto-hackers).

Train in a martial-arts form. The kind of mental discipline required for martial arts seems to be similar in important ways to what hackers do. The most popular forms among hackers are definitely Asian empty-hand arts such as Tae Kwon Do, various forms of Karate, Kung Fu, Aikido, or Ju Jitsu. Western fencing and Asian sword arts also have visible followings. In places where it's legal, pistol shooting has been rising in popularity since the late 1990s. The most hackerly martial arts are those which emphasize mental discipline, relaxed awareness, and control, rather than raw strength, athleticism, or physical toughness.

Study an actual meditation discipline. The perennial favorite among hackers is Zen (importantly, it is possible to benefit from Zen without acquiring a religion or discarding one you already have). Other styles may work as well, but be careful to choose one that doesn't require you to believe crazy things.

Develop an analytical ear for music. Learn to appreciate peculiar kinds of music. Learn to play some musical instrument well, or how to sing.

Develop your appreciation of puns and wordplay.

The more of these things you already do, the more likely it is that you are natural hacker material. Why these things in particular is not completely clear, but they're connected with a mix of left- and right-brain skills that seems to be important; hackers need to be able to both reason logically and step outside the apparent logic of a problem at a moment's notice.

Work as intensely as you play and play as intensely as you work. For true hackers, the boundaries between "play", "work", "science" and "art" all tend to disappear, or to merge into a high-level creative playfulness. Also, don't be content with a narrow range of skills. Though most hackers self-describe as programmers, they are very likely to be more than competent in several related skills — system administration, web design, and PC hardware troubleshooting are common ones. A hacker who's a system administrator, on the other hand, is likely to be quite skilled at script programming and web design. Hackers don't do things by halves; if they invest in a skill at all, they tend to get very good at it.

Finally, a few things not to do.

Don't use a silly, grandiose user ID or screen name.

Don't get in flame wars on Usenet (or anywhere else).

Don't call yourself a ‘cyberpunk’, and don't waste your time on anybody who does.

Don't post or email writing that's full of spelling errors and bad grammar.

The only reputation you'll make doing any of these things is as a twit. Hackers have long memories — it could take you years to live your early blunders down enough to be accepted.

The problem with screen names or handles deserves some amplification. Concealing your identity behind a handle is a juvenile and silly behavior characteristic of crackers, warez d00dz, and other lower life forms. Hackers don't do this; they're proud of what they do and want it associated with their real names. So if you have a handle, drop it. In the hacker culture it will only mark you as a loser.


Historical Note: Hacking, Open Source, and Free Software

When I originally wrote this how-to in late 1996, some of the conditions around it were very different from the way they look today. A few words about these changes may help clarify matters for people who are confused about the relationship of open source, free software, and Linux to the hacker community. If you are not curious about this, you can skip straight to the FAQ and bibliography from here.

The hacker ethos and community as I have described it here long predates the emergence of Linux after 1990; I first became involved with it around 1976, and, its roots are readily traceable back to the early 1960s. But before Linux, most hacking was done on either proprietary operating systems or a handful of quasi-experimental homegrown systems like MIT's ITS that were never deployed outside of their original academic niches. While there had been some earlier (pre-Linux) attempts to change this situation, their impact was at best very marginal and confined to communities of dedicated true believers which were tiny minorities even within the hacker community, let alone with respect to the larger world of software in general.

What is now called "open source" goes back as far as the hacker community does, but until 1985 it was an unnamed folk practice rather than a conscious movement with theories and manifestos attached to it. This prehistory ended when, in 1985, arch-hacker Richard Stallman ("RMS") tried to give it a name — "free software". But his act of naming was also an act of claiming; he attached ideological baggage to the "free software" label which much of the existing hacker community never accepted. As a result, the "free software" label was loudly rejected by a substantial minority of the hacker community (especially among those associated with BSD Unix), and used with serious but silent reservations by a majority of the remainder (including myself).

Despite these reservations, RMS's claim to define and lead the hacker community under the "free software" banner broadly held until the mid-1990s. It was seriously challenged only by the rise of Linux. Linux gave open-source development a natural home. Many projects issued under terms we would now call open-source migrated from proprietary Unixes to Linux. The community around Linux grew explosively, becoming far larger and more heterogenous than the pre-Linux hacker culture. RMS determinedly attempted to co-opt all this activity into his "free software" movement, but was thwarted by both the exploding diversity of the Linux community and the public skepticism of its founder, Linus Torvalds. Torvalds continued to use the term "free software" for lack of any alternative, but publicly rejected RMS's ideological baggage. Many younger hackers followed suit.

In 1996, when I first published this Hacker HOWTO, the hacker community was rapidly reorganizing around Linux and a handful of other open-source operating systems (notably those descended from BSD Unix). Community memory of the fact that most of us had spent decades developing closed-source software on closed-source operating systems had not yet begun to fade, but that fact was already beginning to seem like part of a dead past; hackers were, increasingly, defining themselves as hackers by their attachments to open-source projects such as Linux or Apache.

The term "open source", however, had not yet emerged; it would not do so until early 1998. When it did, most of hacker community adopted it within the following six months; the exceptions were a minority ideologically attached to the term "free software". Since 1998, and especially after about 2003, the identification of 'hacking' with 'open-source (and free software) development' has become extremely close. Today there is little point in attempting to distinguish between these categories, and it seems unlikely that will change in the future.

It is worth remembering, however, that this was not always so.


Other Resources

Paul Graham has written an essay called Great Hackers, and another on Undergraduation, in which he speaks much wisdom.

There is a document called How To Be A Programmer that is an excellent complement to this one. It has valuable advice not just about coding and skillsets, but about how to function on a programming team.

I have also written A Brief History Of Hackerdom.

I have written a paper, The Cathedral and the Bazaar, which explains a lot about how the Linux and open-source cultures work. I have addressed this topic even more directly in its sequel Homesteading the Noosphere.

Rick Moen has written an excellent document on how to run a Linux user group.

Rick Moen and I have collaborated on another document on How To Ask Smart Questions. This will help you seek assistance in a way that makes it more likely that you will actually get it.

If you need instruction in the basics of how personal computers, Unix, and the Internet work, see The Unix and Internet Fundamentals HOWTO.

When you release software or write patches for software, try to follow the guidelines in the Software Release Practice HOWTO.

If you enjoyed the Zen poem, you might also like Rootless Root: The Unix Koans of Master Foo.


Frequently Asked Questions

Q: How do I tell if I am already a hacker?
Q: Will you teach me how to hack?
Q: How can I get started, then?
Q: When do you have to start? Is it too late for me to learn?
Q: How long will it take me to learn to hack?
Q: Is Visual Basic a good language to start with?
Q: Would you help me to crack a system, or teach me how to crack?
Q: How can I get the password for someone else's account?
Q: How can I break into/read/monitor someone else's email?
Q: How can I steal channel op privileges on IRC?
Q: I've been cracked. Will you help me fend off further attacks?
Q: I'm having problems with my Windows software. Will you help me?
Q: Where can I find some real hackers to talk with?
Q: Can you recommend useful books about hacking-related subjects?
Q: Do I need to be good at math to become a hacker?
Q: What language should I learn first?
Q: What kind of hardware do I need?
Q: I want to contribute. Can you help me pick a problem to work on?
Q: Do I need to hate and bash Microsoft?
Q: But won't open-source software leave programmers unable to make a living?
Q: Where can I get a free Unix?
Q:

How do I tell if I am already a hacker?

A:

Ask yourself the following three questions:

Do you speak code, fluently?

Do you identify with the goals and values of the hacker community?

Has a well-established member of the hacker community ever called you a hacker?

If you can answer yes to all three of these questions, you are already a hacker. No two alone are sufficient.

The first test is about skills. You probably pass it if you have the minimum technical skills described earlier in this document. You blow right through it if you have had a substantial amount of code accepted by an open-source development project.

The second test is about attitude. If the five principles of the hacker mindset seemed obvious to you, more like a description of the way you already live than anything novel, you are already halfway to passing it. That's the inward half; the other, outward half is the degree to which you identify with the hacker community's long-term projects.

Here is an incomplete but indicative list of some of those projects: Does it matter to you that Linux improve and spread? Are you passionate about software freedom? Hostile to monopolies? Do you act on the belief that computers can be instruments of empowerment that make the world a richer and more humane place?

But a note of caution is in order here. The hacker community has some specific, primarily defensive political interests — two of them are defending free-speech rights and fending off "intellectual-property" power grabs that would make open source illegal. Some of those long-term projects are civil-liberties organizations like the Electronic Frontier Foundation, and the outward attitude properly includes support of them. But beyond that, most hackers view attempts to systematize the hacker attitude into an explicit political program with suspicion; we've learned, the hard way, that these attempts are divisive and distracting. If someone tries to recruit you to march on your capitol in the name of the hacker attitude, they've missed the point. The right response is probably “Shut up and show them the code.”

The third test has a tricky element of recursiveness about it. I observed in the section called “What Is a Hacker?” that being a hacker is partly a matter of belonging to a particular subculture or social network with a shared history, an inside and an outside. In the far past, hackers were a much less cohesive and self-aware group than they are today. But the importance of the social-network aspect has increased over the last thirty years as the Internet has made connections with the core of the hacker subculture easier to develop and maintain. One easy behavioral index of the change is that, in this century, we have our own T-shirts.

Sociologists, who study networks like those of the hacker culture under the general rubric of "invisible colleges", have noted that one characteristic of such networks is that they have gatekeepers — core members with the social authority to endorse new members into the network. Because the "invisible college" that is hacker culture is a loose and informal one, the role of gatekeeper is informal too. But one thing that all hackers understand in their bones is that not every hacker is a gatekeeper. Gatekeepers have to have a certain degree of seniority and accomplishment before they can bestow the title. How much is hard to quantify, but every hacker knows it when they see it.

Q:

Will you teach me how to hack?

A:

Since first publishing this page, I've gotten several requests a week (often several a day) from people to "teach me all about hacking". Unfortunately, I don't have the time or energy to do this; my own hacking projects, and working as an open-source advocate, take up 110% of my time.

Even if I did, hacking is an attitude and skill you basically have to teach yourself. You'll find that while real hackers want to help you, they won't respect you if you beg to be spoon-fed everything they know.

Learn a few things first. Show that you're trying, that you're capable of learning on your own. Then go to the hackers you meet with specific questions.

If you do email a hacker asking for advice, here are two things to know up front. First, we've found that people who are lazy or careless in their writing are usually too lazy and careless in their thinking to make good hackers — so take care to spell correctly, and use good grammar and punctuation, otherwise you'll probably be ignored. Secondly, don't dare ask for a reply to an ISP account that's different from the account you're sending from; we find people who do that are usually thieves using stolen accounts, and we have no interest in rewarding or assisting thievery.

Q:

How can I get started, then?

A:

The best way for you to get started would probably be to go to a LUG (Linux user group) meeting. You can find such groups on the LDP General Linux Information Page; there is probably one near you, possibly associated with a college or university. LUG members will probably give you a Linux if you ask, and will certainly help you install one and get started.

Q:

When do you have to start? Is it too late for me to learn?

A:

Any age at which you are motivated to start is a good age. Most people seem to get interested between ages 15 and 20, but I know of exceptions in both directions.

Q:

How long will it take me to learn to hack?

A:

That depends on how talented you are and how hard you work at it. Most people who try can acquire a respectable skill set in eighteen months to two years, if they concentrate. Don't think it ends there, though; in hacking (as in many other fields) it takes about ten years to achieve mastery. And if you are a real hacker, you will spend the rest of your life learning and perfecting your craft.

Q:

Is Visual Basic a good language to start with?

A:

If you're asking this question, it almost certainly means you're thinking about trying to hack under Microsoft Windows. This is a bad idea in itself. When I compared trying to learn to hack under Windows to trying to learn to dance while wearing a body cast, I wasn't kidding. Don't go there. It's ugly, and it never stops being ugly.

There is a specific problem with Visual Basic; mainly that it's not portable. Though there is a prototype open-source implementations of Visual Basic, the applicable ECMA standards don't cover more than a small set of its programming interfaces. On Windows most of its library support is proprietary to a single vendor (Microsoft); if you aren't extremely careful about which features you use — more careful than any newbie is really capable of being — you'll end up locked into only those platforms Microsoft chooses to support. If you're starting on a Unix, much better languages with better libraries are available. Python, for example.

Also, like other Basics, Visual Basic is a poorly-designed language that will teach you bad programming habits. No, don't ask me to describe them in detail; that explanation would fill a book. Learn a well-designed language instead.

One of those bad habits is becoming dependent on a single vendor's libraries, widgets, and development tools. In general, any language that isn't fully supported under at least Linux or one of the BSDs, and/or at least three different vendors' operating systems, is a poor one to learn to hack in.

Q:

Would you help me to crack a system, or teach me how to crack?

A:

No. Anyone who can still ask such a question after reading this FAQ is too stupid to be educable even if I had the time for tutoring. Any emailed requests of this kind that I get will be ignored or answered with extreme rudeness.

Q:

How can I get the password for someone else's account?

A:

This is cracking. Go away, idiot.

Q:

How can I break into/read/monitor someone else's email?

A:

This is cracking. Get lost, moron.

Q:

How can I steal channel op privileges on IRC?

A:

This is cracking. Begone, cretin.

Q:

I've been cracked. Will you help me fend off further attacks?

A:

No. Every time I've been asked this question so far, it's been from some poor sap running Microsoft Windows. It is not possible to effectively secure Windows systems against crack attacks; the code and architecture simply have too many flaws, which makes securing Windows like trying to bail out a boat with a sieve. The only reliable prevention starts with switching to Linux or some other operating system that is designed to at least be capable of security.

Q:

I'm having problems with my Windows software. Will you help me?

A:

Yes. Go to a DOS prompt and type "format c:". Any problems you are experiencing will cease within a few minutes.

Q:

Where can I find some real hackers to talk with?

A:

The best way is to find a Unix or Linux user's group local to you and go to their meetings (you can find links to several lists of user groups on the LDP site at ibiblio).

(I used to say here that you wouldn't find any real hackers on IRC, but I'm given to understand this is changing. Apparently some real hacker communities, attached to things like GIMP and Perl, have IRC channels now.)

Q:

Can you recommend useful books about hacking-related subjects?

A:

I maintain a Linux Reading List HOWTO that you may find helpful. The Loginataka may also be interesting.

For an introduction to Python, see the tutorial on the Python site.

Q:

Do I need to be good at math to become a hacker?

A:

No. Hacking uses very little formal mathematics or arithmetic. In particular, you won't usually need trigonometry, calculus or analysis (there are exceptions to this in a handful of specific application areas like 3-D computer graphics). Knowing some formal logic and Boolean algebra is good. Some grounding in finite mathematics (including finite-set theory, combinatorics, and graph theory) can be helpful.

Much more importantly: you need to be able to think logically and follow chains of exact reasoning, the way mathematicians do. While the content of most mathematics won't help you, you will need the discipline and intelligence to handle mathematics. If you lack the intelligence, there is little hope for you as a hacker; if you lack the discipline, you'd better grow it.

I think a good way to find out if you have what it takes is to pick up a copy of Raymond Smullyan's book What Is The Name Of This Book?. Smullyan's playful logical conundrums are very much in the hacker spirit. Being able to solve them is a good sign; enjoying solving them is an even better one.

Q:

What language should I learn first?

A:

XHTML (the latest dialect of HTML) if you don't already know it. There are a lot of glossy, hype-intensive bad HTML books out there, and distressingly few good ones. The one I like best is HTML: The Definitive Guide.

But HTML is not a full programming language. When you're ready to start programming, I would recommend starting with Python. You will hear a lot of people recommending Perl, and Perl is still more popular than Python, but it's harder to learn and (in my opinion) less well designed.

C is really important, but it's also much more difficult than either Python or Perl. Don't try to learn it first.

Windows users, do not settle for Visual Basic. It will teach you bad habits, and it's not portable off Windows. Avoid.

Q:

What kind of hardware do I need?

A:

It used to be that personal computers were rather underpowered and memory-poor, enough so that they placed artificial limits on a hacker's learning process. This stopped being true in the mid-1990s; any machine from an Intel 486DX50 up is more than powerful enough for development work, X, and Internet communications, and the smallest disks you can buy today are plenty big enough.

The important thing in choosing a machine on which to learn is whether its hardware is Linux-compatible (or BSD-compatible, should you choose to go that route). Again, this will be true for almost all modern machines. The only really sticky areas are modems and wireless cards; some machines have Windows-specific hardware that won't work with Linux.

There's a FAQ on hardware compatibility; the latest version is here.

Q:

I want to contribute. Can you help me pick a problem to work on?

A:

No, because I don't know your talents or interests. You have to be self-motivated or you won't stick, which is why having other people choose your direction almost never works.

Try this. Watch the project announcements scroll by on Freshmeat for a few days. When you see one that makes you think "Cool! I'd like to work on that!", join it.

Q:

Do I need to hate and bash Microsoft?

A:

No, you don't. Not that Microsoft isn't loathsome, but there was a hacker culture long before Microsoft and there will still be one long after Microsoft is history. Any energy you spend hating Microsoft would be better spent on loving your craft. Write good code — that will bash Microsoft quite sufficiently without polluting your karma.

Q:

But won't open-source software leave programmers unable to make a living?

A:

This seems unlikely — so far, the open-source software industry seems to be creating jobs rather than taking them away. If having a program written is a net economic gain over not having it written, a programmer will get paid whether or not the program is going to be open-source after it's done. And, no matter how much "free" software gets written, there always seems to be more demand for new and customized applications. I've written more about this at the Open Source pages.

Q:

Where can I get a free Unix?

A:

If you don't have a Unix installed on your machine yet, elsewhere on this page I include pointers to where to get the most commonly used free Unix. To be a hacker you need motivation and initiative and the ability to educate yourself. Start now...


