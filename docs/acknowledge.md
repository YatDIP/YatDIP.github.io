---
hide:
  - navigation
  - toc
---

# 致谢与版权

## 致谢

笔者自 2024 年起便与《数字图像处理》这门课程结下不解之缘。在深入学习的过程中，我愈发深刻地体会到，这门课程不仅是传统计算机视觉的基石，更是当今运用多模态大语言模型（LLMs）完成图像理解任务的核心先修基础。

在此，我要特别感谢当时讲授本课程的赖剑煌老师。赖老师在课堂上并未局限于浅层的知识灌输，而是不断启发我去对底层算法进行更加深度的追问与思考，这种治学态度令我受益匪浅。同时，也非常感谢当时的助教叶标华博士。叶博士尽心负责，不仅在习题讲解上细致入微，更在我实验受阻时倾囊相授。正是这种师徒间尽心负责、薪火相传的精神，不仅为我提供了持续学习的动力，更指引了我探究这门学科的正确方向。

建立本网站的契机，源于近日与一位好友的深谈。他在建设《数据结构》课程项目时提到，希望在当今大模型飞速发展的环境下，帮助学生重新培养不可替代的算法思维。这一理念与我不谋而合。虽然在当前时代，我们可以轻易借助大模型直接生成图像处理的代码，但本课程网站的建设初衷，是希望探讨**如何在这种人机协同的新范式下，完善自身的研究思想**。面对一个未知问题，我们首先应该思考什么？如何精准定义问题？又该如何优雅地借助大模型来优化和验证我们的算法设计？这种回归本质的思维方式，是技术浪潮中每个人都应当修炼的内功。

一路走来，感谢不断栽培、引导并带领我向前的各位师长与同窗。谨以此站，献给所有在数字图像处理领域孜孜以求的探索者。

## 版权说明

本站致力于分享严谨的学术解析及高质量的开源算法代码。为了保护创作者的合法权益，并坚守高校学术诚信底线，本网站对内容与代码采取“**双轨制（Dual-Track）**”版权协议。请在访问、转载或使用本站任何资源前，仔细阅读并遵守以下条款。

### 1. 博客文章与图文内容 (CC BY-NC-ND 4.0)

本站的所有原创文字讲义、排版设计以及原理演示图表，均严格受 **[CC BY-NC-ND 4.0 (署名-非商业性使用-禁止演绎)](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh-hans)** 协议保护。

这意味着您可以自由地阅读和分享本站的文章，但必须遵守以下底线：

* **必须规范署名 (BY)**：任何形式的转载均必须保留原作者信息，并在文章醒目位置附带指向本站原文的首发链接。
* **严禁商业性使用 (NC)**：任何人或机构不得将本站的讲义内容用于任何商业盈利目的。这包括但不限于：未经授权的考研辅导班内部讲义、知识付费专栏的搬运、以及营销号的洗稿引流等。
* **禁止恶意演绎 (ND)**：未经书面明确授权，严禁对文章内容进行二次修改（如擅自删减核心段落、篡改学术术语）后重新发布。

### 2. 开源代码与技术实现 (AGPL-3.0 + 附加学术条款)

为了促进技术交流的同时防止代码被恶意商业化抄袭或违规提交，本博客内涉及的所有开源实验代码及项目框架，均受 **GNU AGPL-3.0** 开源协议及其**附加学术条款 (Additional Terms for Academic Use)** 的严格约束。

**附加学术条款 (Additional Terms for Academic Use)：**

通过访问、使用或分发本站的软件代码，您默认同意以下规则：

1. **绝对的非商业性 (Non-Commercial Use)**：未经版权所有者书面许可，严禁商业化使用。包括但不限于出售、出租代码，或将本站提供的算法框架集成到闭源的商业系统中。
2. **恪守学术诚信 (Academic Integrity)**：严禁学术剽窃（Do not plagiarize）。您不得在未提供清晰署名（如在源码注释中保留原出处）的情况下，将本站代码作为您自己的课程作业或学术作品直接提交。如需直接提交使用，请务必提前通过邮件获取书面许可。违规者不仅将被剥夺代码使用权，还可能面临学术纪律处分。

**权利终止与维权声明：**

本站基于 GitHub 构建与托管，每一次代码与博文的提交（Commit）均附带全网公开、不可篡改的时间戳与哈希值。在司法与学术仲裁实践中，这具有绝对优先的版权归属证据效力。对于任何试图绕过上述协议的商业洗稿或学术抄袭行为，课程组将立即通过可信第三方机构进行电子证据保全，并保留向侵权者所在高校学术委员会发送实名举报信，或依法追究其法律责任的权利。

*如有关版权许可或商业授权咨询，请发送电子邮件至：`futk@mail2.sysu.edu.cn`。*

<details>
<summary><b>⚖️ 点击展开查看核心开源协议 (GNU AGPL-3.0 License) 完整法律文本</b></summary>

```text
                    GNU AFFERO GENERAL PUBLIC LICENSE
                       Version 3, 19 November 2007

 Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.

                            Preamble

  The GNU Affero General Public License is a free, copyleft license for
software and other kinds of works, specifically designed to ensure
cooperation with the community in the case of network server software.

  The licenses for most software and other practical works are designed
to take away your freedom to share and change the works.  By contrast,
our General Public Licenses are intended to guarantee your freedom to
share and change all versions of a program--to make sure it remains free
software for all its users.

  When we speak of free software, we are referring to freedom, not
price.  Our General Public Licenses are designed to make sure that you
have the freedom to distribute copies of free software (and charge for
them if you wish), that you receive source code or can get it if you
want it, that you can change the software or use pieces of it in new
free programs, and that you know you can do these things.

  Developers that use our General Public Licenses protect your rights
with two steps: (1) assert copyright on the software, and (2) offer
you this License which gives you legal permission to copy, distribute
and/or modify the software.

  A secondary benefit of defending all users' freedom is that
improvements made in alternate versions of the program, if they
receive widespread use, become available for other developers to
incorporate.  Many developers of free software are heartened and
encouraged by the resulting cooperation.  However, in the case of
software used on network servers, this result may fail to come about.
The GNU General Public License permits making a modified version and
letting the public access it on a server without ever releasing its
source code to the public.

  The GNU Affero General Public License is designed specifically to
ensure that, in such cases, the modified source code becomes available
to the community.  It requires the operator of a network server to
provide the source code of the modified version running there to the
users of that server.  Therefore, public use of a modified version, on
a publicly accessible server, gives the public access to the source
code of the modified version.

  An older license, called the Affero General Public License and
published by Affero, was designed to accomplish similar goals.  This is
a different license, not a version of the Affero GPL, but Affero has
released a new version of the Affero GPL which permits relicensing under
this license.

  The precise terms and conditions for copying, distribution and
modification follow.

                       TERMS AND CONDITIONS

  0. Definitions.

  "This License" refers to version 3 of the GNU Affero General Public License.

  "Copyright" also means copyright-like laws that apply to other kinds of
works, such as semiconductor masks.

  "The Program" refers to any copyrightable work licensed under this
License.  Each licensee is addressed as "you".  "Licensees" and
"recipients" may be individuals or organizations.

  To "modify" a work means to copy from or adapt all or part of the work
in a fashion requiring copyright permission, other than the making of an
exact copy.  The resulting work is called a "modified version" of the
earlier work or a work "based on" the earlier work.

  A "covered work" means either the unmodified Program or a work based
on the Program.

  To "propagate" a work means to do anything with it that, without
permission, would make you directly or secondarily liable for
infringement under applicable copyright law, except executing it on a
computer or modifying a private copy.  Propagation includes copying,
distribution (with or without modification), making available to the
public, and in some countries other activities as well.

  To "convey" a work means any kind of propagation that enables other
parties to make or receive copies.  Mere interaction with a user through
a computer network, with no transfer of a copy, is not conveying.

  An interactive user interface displays "Appropriate Legal Notices"
to the extent that it includes a convenient and prominently visible
feature that (1) displays an appropriate copyright notice, and (2)
tells the user that there is no warranty for the work (except to the
extent that warranties are provided), that licensees may convey the
work under this License, and how to view a copy of this License.  If
the interface presents a list of user commands or options, such as a
menu, a prominent item in the list meets this criterion.

  1. Source Code.

  The "source code" for a work means the preferred form of the work
for making modifications to it.  "Object code" means any non-source
form of a work.

  A "Standard Interface" means an interface that either is an official
standard defined by a recognized standards body, or, in the case of
interfaces specified for a particular programming language, one that
is widely used among developers working in that language.

  The "System Libraries" of an executable work include anything, other
than the work as a whole, that (a) is included in the normal form of
packaging a Major Component, but which is not part of that Major
Component, and (b) serves only to enable use of the work with that
Major Component, or to implement a Standard Interface for which an
implementation is available to the public in source code form.  A
"Major Component", in this context, means a major essential component
(kernel, window system, and so on) of the specific operating system
(if any) on which the executable work runs, or a compiler used to
produce the work, or an object code interpreter used to run it.

  The Corresponding Source need not include anything that users
can regenerate automatically from other parts of the Corresponding
Source.

  The Corresponding Source for a work in source code form is that
same work.

  2. Basic Permissions.
  (详细许可条款与约束规定请遵循自由软件基金会颁布的标准 AGPL-3.0 文件内容。)
```
</details>
