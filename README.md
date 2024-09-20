# 我的宏基因组分析流程学习笔记

本文档用来记录我从零开始学习宏基因组分析流程中学会的知识点、方法、遇到的困难。

推荐所有研究微生物组学的人都去读一下这篇发表在Microbiome上的文章: The vocabulary of microbiome research: a proposal，先明确microbiota、 metataxonomics、metagenome、metabiome的概念。
> Marchesi, J.R., Ravel, J. The vocabulary of microbiome research: a proposal. Microbiome 3, 31 (2015). https://doi.org/10.1186/s40168-015-0094-5

一句话理解宏基因组(metagenome)，你采集的样本里面所有生物的DNA的总和。

样本：水💧，粪便💩，空气💨，物体表面。

生物：人👨‍👩‍👧‍👧， 动物🐶， 植物🌻，微生物🦠（细菌、真菌、病毒、衣原体、支原体...）

为了得到这些DNA的序列，我们选择了高通量测序，例如illumina的二代测序，Pacbio和Nanopore的三代测序。现在我们一般花钱让专业的测序公司帮我们进行测序，从公司那里得到原始测序数据。

大家可能已经了解过了二代测序和三代测序的原理，不了解原理的读者可以去B站或者Youtube搜索一下illumina公司制作的二代测序原理视频。

> B站：[illumina测序原理](https://www.bilibili.com/video/BV1W44y1373N)，[Nanopore测序原理](https://www.bilibili.com/video/BV1kL4y1i7Jx)，[Pacbio测序原理](https://www.bilibili.com/video/BV1iL4y1i7Tf)
> Youtube: [illumina测序原理](https://www.youtube.com/watch?v=fCd6B5HRaZ8)，[Nanopore测序原理](https://www.youtube.com/watch?v=RcP85JHLmnI)，[Pacbio测序原理](https://www.youtube.com/watch?v=_lD8JyAbwEo)

如果读者英文听不太明白，可以去关注陈巍老师的频道。
>Bilibili: [陈巍学基因](https://space.bilibili.com/17326115)
Youtube: [David Chen](https://www.youtube.com/@davidchen4753)

上述视频看完我们就对高通量测序有了初步了解，要想进行数据分析还要深入了解其中的步骤。
::: info 提示
这是为了在得到原始测序数据之后进行质量控制时，让我们知道要去除哪些序列。
:::
## Quality Control: 去除糟粕，保留精华


## References