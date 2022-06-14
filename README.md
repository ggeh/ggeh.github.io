
<p>...</p>

<p align="center">
    英汉翻译质量评估标注指南
</p>
<p align="center">
    Annotation Guidelines for English-Chinese Translation Quality Assessment
</p>

<p align="center">
    <strong><u><a id="Overview">总览</a></u></strong>
</p>
<p>
<a href="#Intro">引言</a>
<ul>
	<li><a href="#Brat">UAM Corpus Tool的基本操作</a></li>
	<li><a href="#Rules">总体标注规则</a></li>
	<li><a href="#Resources">当您不确定时：资源推荐</a></li>
</ul>
</p>
<p>
<a href="#AccAn">第一步：标注可接受度</a>
</p>
<ul>
	<li><a href="#AccCats">可接受度错误类型</a></li>
</ul>
<p>
<a href="#PrepStep2">下一步的文本准备工作</a>
</p>
<p>
<a href="#AdAn">第二步：标注忠实度</a>
</p>
<ul>
	<li><a href="#AdCats">忠实度错误类型</a></li>
</ul>
<p>
<a href="#Consolidation">第三步：确认标注</a>
</p>
<ul>
	<li><a href="#Linking">制定“统一标准”</a></li>
</ul>
<p>
    <strong><u></u></strong>
</p>
<p align="center">
    <strong><u><a id="Intro">引言</a></u><a href="#Overview" title="Back to Overview">&#8617;</a></strong>
</p>
<p>
翻译质量评估是一项非常复杂的任务，评估的目的不同，评估的方式也会不同。本次翻译质量评估的目的是对比不同翻译模式下（人工翻译、机器翻译和机器翻译译后编辑）的翻译质量有何异同，尤其是在细粒度方面（fine-grained），即翻译错误类型上的异同。传统翻译质量评估在错误罚分（severity score）上往往比较主观，且局限于句子层面，忽视了衔接、连贯等语篇方面的评分。本次翻译质量评估错误类型分类（categorization of translation errors）和错误权重（error weights）是基于英汉语言特征、Daems et al.（2017）的英-荷翻译质量评估模型和Burchardt & Lommel（2014）的MQM[ MQM最新的翻译错误类型分类参见：http://www.qt21.eu/mqm-definition/definition-2015-12-30.html]多维度翻译质量评估模型；本次翻译错误类型标注模式参照Daems et al.（2017）[Daems et al.（2017b）的翻译质量评估错误类型分类和标注方法参见：https://users.ugent.be/~jvdaems/TQA_guidelines_2.0.html]的两步翻译质量错误类型标注模式（a two-step TQA approach）和基于用户定义的错误类型权重（user-defined error weights）分类标准。 
</p>
<p>
    <u>翻译错误类型分类</u>
</p>
<p>
    本次翻译错误分为两大类：忠实度（Adequacy）和可接受度（Acceptability）。
</p>
<p>
    <u>错误权重（Error weights）</u>
</p>
<p>
    错误权重的分类和判定工作由研究者确定，而非由标注员（annotators）确定。本课题参照Daems et al.（2017）所制定的翻译错误权重层级，并根据本课题的文本类型（科学类新闻）和英汉之间的差异，将术语错误和术语不一致等错误权重作出适当修正。忠实度和可接受度中不同错误类型的错误权重可参见忠实度（Adequacy）和可接受度（Acceptability）。以下是本课题的5级错误权重分类标准：
</p>
<p>	
<ul>
	<li>0：不属于真正的问题（not an actual problem）：这一类别的问题由两类因素决定，一类是由任务本身决定，例如：显化（explicitation）；另一类是由翻译环境所致，例如一些被试由于键盘输入法临时卡顿，导致打字错误（typo）。在真实工作环境中，这种情况不会发生。</li>
	<li>1：轻微问题（minor problems）: 译文依旧可以毫不费力地理解，而且译文所传递的信息与原文相一致。但译文存在一个小错误或者可读性略受一点影响，例如：拼写错误、标点符号错误、语域问题和重复错误。</li>
	<li>2: 中度问题（medium problems）: 原文和译文所传递的意思略有偏差，例如：词汇层面漏译；或者译文不怎么需要费力就可以理解，但在一些语法、风格或衔接与连贯性上不完全正确，例如：一致性错误和词汇衔接错误。</li>
	<li>3: 重要错误（major problems）: 译文与原文传递的意思有一些偏差，例如选词不当、句法层面漏译和衔接错误；或者译文由于语法结构不正确或突兀的表达，导致可读性较差，例如：语序错误和搭配错误。</li>
	<li>4: 严重错误（critical problems）: 此类错误是指对译文的可读性和准确性产生严重影响的错误，例如：词义错误、语义矛盾、术语错误和逻辑错误。</li>
</ul>
</p>
