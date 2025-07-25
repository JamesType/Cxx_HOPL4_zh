# 在纷繁多变的世界里茁壮成长：C+&#x200d;+ 2006–2020

这是 C+&#x200d;+ 之父 Bjarne Stroustrup 的 [HOPL4 论文](https://www.stroustrup.com/hopl20main-p5-p-bfc9cd4--final.pdf)的中文版。

[HOPL](https://dl.acm.org/conference/hopl) 是 History of Programming Languages（编程语言历史）的缩写，是 [ACM](https://www.acm.org/)（Association of Computing Machines，国际计算机协会）旗下的一个会议，约每十五年举办一次。Bjarne 的这篇论文是他为 2021 年 [HOPL IV 会议](https://hopl4.sigplan.org/)准备的论文，也是他的第三篇 HOPL 论文。在这三篇前后间隔近三十年的论文里，Bjarne 记录了 C+&#x200d;+ 的完整历史，从 1979 年到 2020 年。这篇 HOPL4 论文尤其重要，因为它涵盖了 C+&#x200d;+98 之后的所有 C+&#x200d;+ 版本，从 C+&#x200d;+11 直到 C+&#x200d;+20。如果你对更早期的历史也感兴趣的话，则可以参考[他的其他 HOPL 论文](https://www.stroustrup.com/papers.html)，及他在 1994 年出版的《C+&#x200d;+ 语言的设计和演化》（*The Design and Evolution of C+&#x200d;+*）。

鉴于这篇论文对于 C+&#x200d;+ 从业者的重要性，[全球 C+&#x200d;+ 及系统软件技术大会](http://cpp-summit.org/)的主办方 [Boolan](http://boolan.com/) 组织了一群译者，把这篇重要论文翻译成了中文，让 C+&#x200d;+ 开发人员对 C+&#x200d;+ 的设计原则和历史有一个系统的了解。下面是论文的完整摘要：

> 到 2006 年时，C+&#x200d;+ 已经在业界广泛使用了 20 年。它既包含了自 1970 年代初引入 C 语言以来一直没有改变的部分，又包含了在二十一世纪初仍很新颖的特性。从 2006 年到 2020 年，C+&#x200d;+ 开发者人数从约 300 万增长到了约 450 万。在这段时期里，有新的编程模型涌现出来，有硬件架构的演变，有新的应用领域变得至关重要，也有好些语言在争夺主导地位，背后有雄厚的资金支持和专业的营销。C+&#x200d;+——一种没有真正商业支持的、老得多的语言——是如何在这些挑战面前继续茁壮成长的？
>
> 本文重点关注 ISO C+&#x200d;+ 标准在 2011 年、2014 年、2017 年和 2020 年的修订版中的重大变化。标准库在篇幅上约占 C+&#x200d;+20 标准的四分之三，但本文的主要重点仍是语言特性和它们所支持的编程技术。
>
> 本文包含了长长的特性清单，其中记录了 C+&#x200d;+ 的成长。我会对重要的技术要点进行讨论，并用简短的代码片段加以说明。此外，本文还展示了一些失败的提案，以及导致其失败的讨论。它提供了一个视角，如何看待这些年来令人眼花缭乱的事实和特性。我的重点是塑造语言的想法、人和流程。
>
> 讨论主题包括各种方向上的努力，包括：通过演进式变化保留 C+&#x200d;+ 的本质，简化 C+&#x200d;+ 的使用，改善对泛型编程的支持，更好地支持编译期编程，扩展对并发和并行编程的支持，以及保持对几十年前的代码的稳定支持。
>
> ISO C+&#x200d;+ 标准是通过一个共识流程演化而来的。无可避免，在方向、设计理念和原则方面，不同的提案间存在竞争和（通常是礼貌性的）冲突。委员会现在比以往任何时候都更大、更活跃，每年有多达 250 人参加三次为期一周的会议，还有更多的人以电子方式参加。我们试图（并不总是成功）减轻各种不良影响，包括“委员会设计”、官僚主义，以及对各种语言时尚的过度热衷。
>
> 具体的语言技术话题包括内存模型、并发并行、编译期计算、移动语义、异常、lambda 表达式和模块。要设计一种机制来指定模板对其参数的要求，既足够灵活和精确，又不会增加运行期开销，实践证明这很困难。设计“概念”来做到这一点的反复尝试可以追溯到 1980 年代，并触及到 C+&#x200d;+ 和泛型编程的许多关键设计问题。
>
> 文中的描述基于个人对关键事件和设计决策的参与，并以 ISO C+&#x200d;+ 标准委员会档案中的数千篇论文和数百份会议记录作为支持。

下面是论文的一级目录：

1. [前言](01.md)
2. [背景：C+&#x200d;+ 的 1979–2006](02.md)
3. [C+&#x200d;+ 标准委员会](03.md)
4. [C+&#x200d;+11：感觉像是门新语言](04.md)
5. [C+&#x200d;+14：完成 C+&#x200d;+11](05.md)
6. [概念](06.md)
7. [错误处理](07.md)
8. [C+&#x200d;+17：大海迷航](08.md)
9. [C+&#x200d;+20：方向之争](09.md)
10. [2020 年的 C+&#x200d;+](10.md)
11. [回顾](11.md)

---

参加论文翻译工作的译者有（按拼音序）：

- 陈常筠
- 高辉
- 何荣华
- 何一娜
- 侯晨
- 侯金亭
- 彭亚
- 王奎
- 王绍新
- 吴咏炜
- 徐宁
- 杨文波
- 于波
- 余水清
- 翟华明
- 章爱国
- 张云潮

论文翻译的校对和体例统一工作由吴咏炜、杨文波、张云潮完成。最后的发布由吴咏炜完成。

我们翻译的是论文的正文部分，英文原文超过 140 页。最后的参考文献部分，由于翻译的意义不大，没有译出。不过，这也带来了一个小小的负面后果：虽然我们对论文内部的交叉引用可以用脚本生成链接，但对指向参考文献的链接就完全无能为力了。所以，如果想要阅读参考文献的话，只能请你到[英文原文](https://www.stroustrup.com/hopl20main-p5-p-bfc9cd4--final.pdf)结尾的 References 部分自行查找了。

翻译过程中我们发现了一些原文中的小问题，并在译文中进行了修正或标注（绝大部分已经经过 Bjarne 老爷子确认）。当然，在翻译过程中引入翻译错误或其他技术问题，恐怕也在所难免——不过，跟 ACM 上发表论文不同，这个网页仍然是可以修正的。所以，如果你，亲爱的读者，发现问题的话，请不吝提交 pull request，我们会尽快检查并进行修正。
