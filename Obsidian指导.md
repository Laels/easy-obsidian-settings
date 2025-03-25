---
author:
  - Lael
Create Date: 2025-03-25T21:13:00
---
# Obsidian基础教程
[详细课程](https://www.bilibili.com/video/BV1H44y1n71k/?spm_id_from=333.337.search-card.all.click&vd_source=8ddc94278f2742d7308722ebc9a65b2e)
[介绍课](https://www.bilibili.com/video/BV18a411r7mt/?spm_id_from=333.337.search-card.all.click&vd_source=8ddc94278f2742d7308722ebc9a65b2e)
## 特点
Obsidian能在知识点间建立链接
1. 支持Markdown
2. 双链笔记先驱
3. 丰富的插件系统
4. 强大的自定义模板
5. 纯文本
6. 本地化资料库
7. 支持同步（官方收费贵）
8. 支持发布（需要收费）
9. …



## 用途
- 码字工具
	- 内容为基础
	- 链接为核心

## 核心插件
- 工作区
- PPT
- 标签

## [Markdown语法](https://markdown.com.cn/basic-syntax/ "最好的markdown教程")

>[!important]
> 
**核心是语法**，所有的渲染均根据语法，因此同一个markdown文件在**任何支持markdown**的软件上显示的**效果**大致是一样的。
- 标准 `markdown` 语法在**普通段落**换行是需要在<font color="#ff0000">行末尾空两格</font>

## markdown基本语法
- # 标题
- **加粗**
- *斜体*
- ==高亮==
- ~~删除符~~
- <u>下划线</u>
- 上标：2<sup>2</sup>
- 下标：O<sub>1</sub>
- 列表
	- 有序列表
		1. a
		2. a
	- 无序列表
		- a
- [引用](https://www.baidu.com/)
- Latex
    - $f(x) = \sum_{k=0}^{n} \frac{f^{(k)}(a)}{k!} (x-a)^k + o\left((x-a)^n\right)$

$$f(x) = \sum_{k=0}^{n} \frac{f^{(k)}(a)}{k!} (x-a)^k + o\left((x-a)^n\right)$$
- 行内代码： `printf("Hello world")`
- 代码块
```c
printf("hello world");
```
- [ ] 任务列表
- 表格

| 这是一个表格 |     |     |     |     |
| ------ | --- | --- | --- | --- |
|        |     |     |     |     |
|        |     |     |     |     |
|        |     |     |     |     |
|        |     |     |     |     |
|        |     |     |     |     |


> 这是一个Blockquote

>[!bug]
> 这是一个callout

>[!example]
> 这也是一个callout

- 分割符
---
<p align="left">居左</p>
<center>居中</center>
<p align="right">居右</p>

## 双链
- 指向文章   `[[...]]`
	- 创建别名`[[...|别名]]`
	- 直接展现内容`![[...]]`
- 指向段落   `[[...#]]`
- 指向块       `[[...#^]]`

## 模板
- 通过模板可以省去一些重复性的工作，如日记模板，周记模板
[模板通配符](https://help.obsidian.md/Plugins/Templates)
## 搜索
- 搜索技巧
	- 空格 搜索包含多个关键词的文档 与
	-  OR 搜索包含某个关键词的文档 或
	-  - 非
	- 指定搜索范围
		- block以段落为单位搜索关键词
	- 搜索任务
		- 搜索任务 task:""
		- 搜索未完成任务 task-todo:""
		- 搜索未完成任务 task-done:""
- 保存查询
- 利用代码块 query

## 快捷键
- navigate back: `Ctrl` + `Alt` + `←`
    - navigate forward: `Ctrl` + `Alt` + `→`




# 插件
- marmind: 思维导图
- ~~Admonitions: 插入 callout~~
- ~~File Color:改变文件颜色~~
- Hotkey for specific files: [快捷键打开特定文件](https://www.bilibili.com/video/BV1Ws4y1j73L/?share_source=copy_web&vd_source=e7ab7a4e1246773db62d95e045426819&t=258)
- ~~Hover Editor: 强化版悬浮弹窗~~
- keyshots: Keyshots is an [Obsidian](https://obsidian.md/) plugin that adds **classic hotkey/shortcuts commands** from **popular IDEs** like Visual Studio Code or JetBrains Family.
- list callou: 能够为列表着色
- ~~Media Extened: 为 md 文件提供媒体播放增强功能~~[Obsidian 插件：Media Extended](https://pkmer.cn/Pkmer-Docs/10-obsidian/obsidian%E7%A4%BE%E5%8C%BA%E6%8F%92%E4%BB%B6/readme/media-extended_readme/)
- Image Magician：使得 Obsidian 能支持相对路径 HTML 语法的
- ~~Mind map:思维导图~~
- ~~Obsidian memos: 灵感记录插件~~
- Pandoc: 转换格式插件
- periodic-notes：记录插件 [PKMer\_Obsidian 插件：Periodic Notes 日记增强插件，管理周期性笔记](https://pkmer.cn/Pkmer-Docs/10-obsidian/obsidian%E7%A4%BE%E5%8C%BA%E6%8F%92%E4%BB%B6/obsidian-periodic-notes/)
    - 日记： [日记模板](https://www.bilibili.com/video/BV1fT4m1U7JS/?share_source=copy_web&vd_source=e7ab7a4e1246773db62d95e045426819)
- ~~Relative Numbers: 相对行号~~
- Template 与 Templater: 模板类插件，能够简化重复性操作[在Obsidian中构建高效笔记模板，从Templates到Templater！\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1c64y1W7c2/?vd_source=8ddc94278f2742d7308722ebc9a65b2e)
    - Capture捕获想法到今天日记中【在Obsidian中构建高效笔记模板，从Templates到Templater！】 【精准空降到 29:46】 https://www.bilibili.com/video/BV1c64y1W7c2/?share_source=copy_web&vd_source=e7ab7a4e1246773db62d95e045426819&t=1786
- tidy footnote: 脚标重排序
- easy typing: 拖慢编辑速度
- Various Complements: 自动补全插件，可添加自己单独的字典
- ~~Vim IM Select: 使用 vim 时自动切换中英文~~
- ~~Vimrc Support: 提供 vim 支持~~
- ~~Zoom: 能够编辑大纲~~
- Heading shifter：标题可以按 `Tab` 或 `Shift Tab` 调整
- ~~Better Footnote:显示脚标内容~~
- Footnote Shortcut:快速添加脚标
    - Ctrl + Shift + 6
- ~~Cloze: 支持高亮文本、粗体文本、下划线文本、斜体文本的完型填空~~
- ~~Text Generate 调用AI~~
    - Ctrl + J
- commandr:自定义菜单栏

# Latex
Latex suite： Latex编辑辅助工具

| Trigger   | Replacement        |
| --------- | ------------------ |
| mk        | $ $                |
| dm        | \$$  <br>  <br>\$$ |
| sr        | ^{2}               |
| cb        | ^{3}               |
| rd        | ^{ }               |
| _         | _{ }               |
| sq        | \sqrt{ }           |
| x/y `Tab` | \frac{x}{y}        |
| //        | \frac{ }{ }        |
| te `Tab`  | \text{ }           |
| x 1       | x_{1}              |
| x,.       | \mathbf{x}         |
| x.,       | \mathbf{x}         |
| xdot      | \dot{x}            |
| xhat      | \hat{x}            |
| xbar      | \bar{x}            |
| xvec      | \vec{x}            |
| xtilde    | \tilde{x}          |
| xund      | \underline{x}      |
| ee        | e^{ }              |

运行将光标移动到括号 {} 内的代码段时，按下 Tab 可退出括号。

| Trigger | Replacement | Trigger | Replacement |
| ------- | ----------- | ------- | ----------- |
| @a      | \alpha      | eta     | \eta        |
| @b      | \beta       | mu      | \mu         |
| @g      | \gamma      | nu      | \nu         |
| @G      | \Gamma      | xi      | \xi         |
| @d      | \delta      | Xi      | \Xi         |
| @D      | \Delta      | pi      | \pi         |
| @e      | \epsilon    | Pi      | \Pi         |
| : e      | \varepsilon | rho     | \rho        |
| @z      | \zeta       | tau     | \tau        |
| @t      | \theta      | phi     | \phi        |
| @T      | \Theta      | Phi     | \Phi        |
| @k      | \kappa      | chi     | \chi        |
| @l      | \lambda     | psi     | \psi        |
| @L      | \Lambda     | Psi     | \Psi        |
| @s      | \sigma      |         |             |
| @S      | \Sigma      |         |             |
| @o      | \omega      |         |             |
| ome     | \omega      |         |             |
对于带有短名称（2-3 个字符）的希腊字母，只需输入它们的名称，例如“pi”→“\pi”





# Callout
用法：`>[!note]`
Better insert Callout: `Alt` + `Shift` + `c`

| Type     | Aliases                     | 作用  |     |
| -------- | --------------------------- | --- | --- |
| note     | note, seealso               | 提示  |     |
| abstract | abstract, summary, tldr     | 摘要  |     |
| info     | info, todo                  | 消息  |     |
| tip      | tip, hint, important        | 建议  |     |
| success  | success, check, done        | 成就  |     |
| question | question, help, faq         | 问题  |     |
| warning  | warning, caution, attention | 警告  |     |
| failure  | failure, fail, missing      | 失败  |     |
| danger   | danger, error               | 危险  |     |
| bug      | bug                         | 毛病  |     |
| example  | example                     | 举例  |     |
| quote    | quote, cite                 | 应用  |     |

# Dataview
- Dataview 可以生成 MOC
    - 生成 **包含同样关键字的笔记** 的目录
    - 生成 **同一个标签的笔记** 的目录
    - 生成 **同一个作者的书目** 的目录
[Dataview](https://blacksmithgu.github.io/obsidian-dataview/)



# Minimal Theme

## Checklist

| Syntax  | Description |
| ------- | ----------- |
| `- [ ]` | to-do       |
| `- [/]` | incomplete  |
| `- [x]` | done        |
| `- [-]` | canceled    |
| `- [>]` | forwarded   |
| `- [<]` | scheduling  |
| `- [?]` | question    |
| `- [!]` | important   |
| `- [*]` | star        |
| `- ["]` | quote       |
| `- [l]` | location    |
| `- [b]` | bookmark    |
| `- [i]` | information |
| `- [S]` | savings     |
| `- [I]` | idea        |
| `- [p]` | pros        |
| `- [c]` | cons        |
| `- [f]` | fire        |
| `- [k]` | key         |
| `- [w]` | win         |
| `- [u]` | up          |
| `- [d]` | down        |



# 快捷键
## 概述 

Obsidian 支持通过键盘来快速完成一些操作。默认情况下，我们只为最常用的[命令](https://publish.obsidian.md/ryooo/T_%E5%B7%A5%E4%B8%9A%E6%8A%80%E6%9C%AF/obsidian/%E5%91%BD%E4%BB%A4%E9%9D%A2%E6%9D%BF)定义了快捷键。

## 查看快捷键 

查看某个命令对应的快捷键最快的方法是在[命令面板](https://publish.obsidian.md/ryooo/T_%E5%B7%A5%E4%B8%9A%E6%8A%80%E6%9C%AF/obsidian/%E5%91%BD%E4%BB%A4%E9%9D%A2%E6%9D%BF)中找到该命令。如果该命令下显示了相应的快捷键，说明已经设置快捷键。

## 基本快捷键 

### Windows 和 Linux 

#### 常见操作 

| 动作     | 快捷键                       |
| ------ | ------------------------- |
| 复制     | `Ctrl+C`                  |
| 剪切     | `Ctrl+X`                  |
| 粘贴     | `Ctrl+V`                  |
| 无格式粘贴  | `Ctrl+Shift+V`            |
| 撤销     | `Ctrl+Z`                  |
| 重做     | `Ctrl+Shift+Z` 或 `Ctrl+Y` |
| 复制段落   | `Ctrl+C`（未选择文本时）          |
| 剪切段落   | `Ctrl+X`（未选择文本时）          |
| 创建待办事项 | `Ctrl+l`                  |
| 切换视图   | `Ctrl+e`                  |
| 切换文件   | `Ctrl+o`                  |
| 快速创建脚注 | `Ctrl+Shift+6`            |

#### 文本编辑 

|动作|快捷键|
|---|---|
|插入新行|`Enter`|
|删除前一个字符|`Backspace`|
|删除后一个字符|`Delete`|
|删除前一个单词|`Ctrl+Backspace`|
|删除后一个单词|`Ctrl+Delete`|
|删除当前行|`Ctrl+Shift+K`（未选择文本时）|

#### 文本导航 

|动作|快捷键|
|---|---|
|将光标移动一个字符|`左/右箭头`|
|将光标移动到前一个单词的开头|`Ctrl+左箭头`|
|将光标移动到下一个单词的结尾|`Ctrl+右箭头`|
|将光标移动到当前行的开头|`Home`|
|将光标移动到当前行的结尾|`End`|
|将光标移动到上一行|`上箭头`|
|将光标移动到下一行|`下箭头`|
|将光标移动到笔记的开头|`Ctrl+Home`|
|将光标移动到笔记的结尾|`Ctrl+End`|
|将光标向上移动一页|`Page up`|
|将光标向下移动一页|`Page down`|

#### 文本选择 

|动作|快捷键|
|---|---|
|取消选择|`Escape`|
|全选|`Ctrl+A`|
|扩展选择一个字符|`Shift+左/右箭头`|
|扩展选择到前一个单词的开头|`Ctrl+Shift+左箭头`|
|扩展选择到下一个单词的结尾|`Ctrl+Shift+右箭头`|
|扩展选择到当前行的开头|`Shift+Home`|
|扩展选择到当前行的结尾|`Shift+End`|
|扩展选择到笔记的开头|`Ctrl+Shift+Home`|
|扩展选择到笔记的结尾|`Ctrl+Shift+End`|
|向上扩展选择一页|`Shift+Page up`|
|向下扩展选择一页|`Shift+Page down`|

### macOS 

#### 常见操作 

|动作|快捷键|
|---|---|
|复制|`Cmd+C`|
|剪切|`Cmd+X`|
|粘贴|`Cmd+V`|
|无格式粘贴|`Cmd+Shift+V`|
|撤销|`Cmd+Z`|
|重做|`Cmd+Shift+Z`|
|复制段落|`Cmd+C`（未选择文本时）|
|剪切段落|`Cmd+X`（未选择文本时）|

#### 文本格式化 

|动作|快捷键|
|---|---|
|加粗文本|`Cmd+B`|
|斜体文本|`Cmd+I`|

#### 文本编辑 

|动作|快捷键|
|---|---|
|插入新行|`Enter`|
|删除前一个字符|`Backspace`|
|删除后一个字符|`Delete`|
|删除前一个单词|`Option+Backspace`|
|删除后一个单词|`Option+Delete`|
|删除到当前行的开头|`Cmd+Backspace`|
|删除到当前行的结尾|`Cmd+Delete`|
|删除当前行|`Cmd+Shift+K`（未选择文本时）|

#### 文本导航 

|动作|快捷键|
|---|---|
|将光标移动一个字符|`左/右箭头`|
|将光标移动到前一个单词的开头|`Option+左箭头`|
|将光标移动到下一个单词的结尾|`Option+右箭头`|
|将光标移动到当前行的开头|`Cmd+左箭头`|
|将光标移动到当前行的结尾|`Cmd+右箭头`|
|将光标移动到上一行|`上箭头`|
|将光标移动到下一行|`下箭头`|
|将光标移动到笔记的开头|`Cmd+上箭头`|
|将光标移动到笔记的结尾|`Cmd+下箭头`|
|将光标向上移动一页|`Ctrl+上箭头`|
|将光标向下移动一页|`Ctrl+下箭头`|

#### 文本选择 

|动作|快捷键|
|---|---|
|取消选择|`Escape`|
|全选|`Cmd+A`|
|扩展选择一个字符|`Shift+左/右箭头`|
|扩展选择到前一个单词的开头|`Option+Shift+左箭头`|
|扩展选择到下一个单词的结尾|`Option+Shift+右箭头`|
|扩展选择到当前行的开头|`Cmd+Shift+左箭头`|
|扩展选择到当前行的结尾|`Cmd+Shift+右箭头`|
|扩展选择到笔记的开头|`Cmd+Shift+上箭头`|
|扩展选择到笔记的结尾|`Cmd+Shift+下箭头`|
|向上扩展选择一页|`Ctrl+Shift+上箭头`|
|向下扩展选择一页|`Ctrl+Shift+下箭头`|

### 属性相关 

见[笔记属性快捷键](https://publish.obsidian.md/ryooo/T_%E5%B7%A5%E4%B8%9A%E6%8A%80%E6%9C%AF/obsidian/%E7%AC%94%E8%AE%B0%E5%B1%9E%E6%80%A7%E5%BF%AB%E6%8D%B7%E9%94%AE)

## 自定义快捷键 

在 Obsidian 中，可以自定义快捷键。默认情况下，官方只为最常用的命令定义了快捷键。如果经常使用某个命令，则可以为其定义一个快捷键。

要添加快捷键、移除快捷键或将快捷键恢复为默认设置，请转到设置 => 快捷键 页面。建议你通过筛选来查找相关命令，因为命令实在太多了。

