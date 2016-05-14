# IFETask

## task1--->零基础HTML编码 : 
- 完成一个HTML页面代码编写（不写CSS，不需要关注样式，只关注文档结构）
- [demo](http://mrkylinzhou.github.io/IFETask/task01/index.html "demo")

## task2--->零基础HTML及CSS编码（一） : 
- 基于第一个任务“零基础HTML编码”的代码，在步骤一的代码基础上增加CSS样式代码的编写
- [demo](http://mrkylinzhou.github.io/IFETask/task02/index.html "demo")

## task3--->三栏式布局 : 
- 使用 HTML 与 CSS 实现三栏式布局
- 左右两栏宽度固定，中间一栏根据父元素宽度填充满，最外面的框应理解为浏览器。背景色为 #eee 区域的高度取决于三个子元素中最高的高度
- [demo](http://mrkylinzhou.github.io/IFETask/task03/index.html "demo")

## task4--->定位和居中问题 :
- 灰色元素水平垂直居中，有两个四分之一圆位于其左上角和右下角
- [demo](http://mrkylinzhou.github.io/IFETask/task04/index.html "demo")

## task5--->零基础HTML及CSS编码（二） :
- 基于第一个任务“零基础HTML编码”的代码，在步骤一的代码基础上增加CSS样式代码的编写
- 头部和底部的黑色区域始终是100%宽
- 页面右侧部分为固定宽度，左侧保持与浏览器窗口变化同步自适应变化
- 左侧的各个模块里面的内容宽度跟随左侧整体宽度同步自适应变化
- 10张图片需要永远都完整展现，所以会随着宽度变窄，从两行变成三行甚至更多，也有可能随着宽度变宽，变成一行
- [demo](http://mrkylinzhou.github.io/IFETask/task05/index.html "demo")

## task6--->通过HTML及CSS模拟报纸排版 :
- 参考设计稿，实现页面开发
- [demo](http://mrkylinzhou.github.io/IFETask/task06/index.html "demo")

## task8--->响应式网格（栅格化）布局 :
- 使用 HTML 与 CSS 实现类似 BootStrap 的响应式 12 栏网格布局，根据屏幕宽度，元素占的栏数不同
- [demo](http://mrkylinzhou.github.io/IFETask/task08/index.html "demo") 

## task10--->Flexbox 布局练习 :
- 学习如何flex进行布局，学习如何根据屏幕宽度调整布局策略
- 屏幕宽度小于 640px 时，调整 Flexbox 的属性以实现第四个元素移动到最前面的效果，而不要改动第一个元素的边框颜色与高度实现效果图
- [demo](http://mrkylinzhou.github.io/IFETask/task10/index.html "demo") 

## task12--->学习CSS 3的新特性 :
- 实现单双行列不同颜色，且前三行特殊表示的表格
- 实现正常状态和focus状态宽度不一致的input文本输入框，且鼠标焦点进入输入框时，宽度的变化以动画呈现
- 不使用JavaScript，实现一个Banner图轮流播放的效果，且点击右下角的1，2，3可以切换到对应Banner图片
- [demo](http://mrkylinzhou.github.io/IFETask/task12/index.html "demo") 

## task13--->零基础JavaScript编码（一） :
- 用户可以在输入框中输入任何内容，点击“确认填写”按钮后，用户输入的内容会显示在“您输入的值是”文字的右边
- [demo](http://mrkylinzhou.github.io/IFETask/task13/index.html "demo") 

## task14--->零基础JavaScript编码（二） :
- 页面加载后，将提供的空气质量数据数组，按照某种逻辑（比如空气质量大于60）进行过滤筛选，最后将符合条件的数据按照一定的格式要求显示在网页上
- [demo](http://mrkylinzhou.github.io/IFETask/task14/index.html "demo") 

## task15--->零基础JavaScript编码（三） :
- 读取页面上已有的source列表，从中提取出城市以及对应的空气质量
- 将数据按照某种顺序排序后，在resort列表中按照顺序显示出来
- [demo](http://mrkylinzhou.github.io/IFETask/task15/index.html "demo") 

## task16--->零基础JavaScript编码（四） :
- 用户输入城市名称和空气质量指数后，点击“确认添加”按钮后，就会将用户的输入在进行验证后，添加到下面的表格中，新增一行进行显示
- 用户输入的城市名必须为中英文字符，空气质量指数必须为整数
- 用户输入的城市名字和空气质量指数需要进行前后去空格及空字符处理（trim）
- 用户输入不合规格时，需要给出提示（允许用alert，也可以自行定义提示方式）
- 用户可以点击表格列中的“删除”按钮，删掉那一行的数据
- [demo](http://mrkylinzhou.github.io/IFETask/task16/index.html "demo") 

## task17--->零基础JavaScript编码（五） :
- 用户可以选择查看不同的时间粒度，以选择要查看的空气质量指数是以天为粒度还是以周或月为粒度
- 天：显示每天的空气质量指数
- 周：以自然周（周一到周日）为粒度，统计一周7天的平均数为这一周的空气质量数值，如果数据中缺少一个自然周的几天，则按剩余天进行计算
- 月：以自然月为粒度，统一一个月所有天的平均数为这一个月的空气质量数值
- 用户可以通过select切换城市
- 通过在"aqi-chart-wrap"里添加DOM，来模拟一个柱状图图表，横轴是时间，纵轴是空气质量指数。天、周、月的数据只根据用户的选择显示一种。
- 天：每天的数据是一个很细的矩形
- 周：每周的数据是一个矩形
- 月：每周的数据是一个很粗的矩形
- 鼠标移动到柱状图的某个柱子时，用title属性提示这个柱子的具体日期和数据
- [demo](http://mrkylinzhou.github.io/IFETask/task17/index.html "demo") 

## task18--->基础JavaScript练习（一） :
- 模拟一个队列，队列的每个元素是一个数字，初始队列为空
- 有一个input输入框，以及4个操作按钮
- 点击"左侧入"，将input中输入的数字从左侧插入队列中；
- 点击"右侧入"，将input中输入的数字从右侧插入队列中；
- 点击"左侧出"，读取并删除队列左侧第一个元素，并弹窗显示元素中数值；
- 点击"右侧出"，读取并删除队列又侧第一个元素，并弹窗显示元素中数值；
- 点击队列中任何一个元素，则该元素会被从队列中删除
- [demo](http://mrkylinzhou.github.io/IFETask/task18/index.html "demo") 

## task19--->基础JavaScript练习（二） :
- 基于任务18
- 限制输入的数字在10-100
- 队列元素数量最多限制为60个，当超过60个时，添加元素时alert出提示
- 队列展现方式变化如图，直接用高度表示数字大小
- 实现一个简单的排序功能，如冒泡排序（不限制具体算法），用可视化的方法表达出来
- [demo](http://mrkylinzhou.github.io/IFETask/task19/index.html "demo") 

## task20--->基础JavaScript练习（三） :
- 基于任务18进行升级
- 将新元素输入框从input改为textarea
- 允许一次批量输入多个内容，格式可以为数字、中文、英文等，可以通过用回车，逗号（全角半角均可），顿号，空格（全角半角、Tab等均可）等符号作为不同内容的间隔
- 增加一个查询文本输入框，和一个查询按钮，当点击查询时，将查询词在各个元素内容中做模糊匹配，将匹配到的内容进行特殊标识，如文字颜色等。举例，内容中有abcd，查询词为ab或bc，则该内容需要标识
- [demo](http://mrkylinzhou.github.io/IFETask/task20/index.html "demo") 

## task21--->基础JavaScript练习（四） :
- 基于任务20，将任务20的代码进行抽象、封装，然后在此基础上实现如图中的两个需求：Tag输入和兴趣爱好输入
- 实现一个tag输入框
- 要求遇到用户输入空格，逗号，回车时，都自动把当前输入的内容作为一个tag放在输入框下面。
- Tag不能有重复的，遇到重复输入的Tag，自动忽视。
- 每个Tag请做trim处理
- 最多允许10个Tag，多于10个时，按照录入的先后顺序，把最前面的删掉
- 当鼠标悬停在tag上时，tag前增加删除二字，点击tag可删除
- 如示例图下方，实现一个兴趣爱好输入的功能
- 通过一个Textarea进行兴趣爱好的输入，可以通过用回车，逗号（全角半角均可），顿号，空格（全角半角、Tab等均可）等符号作为间隔。
- 当点击“确认兴趣爱好”的按钮时，将textarea中的输入按照你设定的间隔符，拆解成一个个的爱好，显示在textarea下方
- 爱好不能重复，所以在下方呈现前，需要做一个去重
- 每个爱好内容需要做trim处理
- 最多允许10个兴趣爱好，多于10个时，按照录入的先后顺序，把最前面的删掉
- [demo](http://mrkylinzhou.github.io/IFETask/task21/index.html "demo") 

## task22--->JavaScript和树（一） :
- 在页面中展现一颗二叉树的结构
- 提供一个按钮，显示开始遍历，点击后，以动画的形式呈现遍历的过程
- 二叉树的遍历算法和方式自定，前序中序后序皆可，但推荐可以提供多种算法的展示（增加多个按钮，每个按钮对应不同的算法）
- 当前被遍历到的节点做一个特殊显示（比如不同的颜色）
- 每隔一段时间（500ms，1s等时间自定）再遍历下一个节点
- [demo](http://mrkylinzhou.github.io/IFETask/task22/index.html "demo") 

## task23--->JavaScript和树（二） :
- 基于任务22，将二叉树变成了多叉树，并且每一个节点中带有内容
- 提供一个按钮，显示开始遍历，点击后，以动画的形式呈现遍历的过程
- 当前被遍历到的节点做一个特殊显示（比如不同的颜色）
- 每隔一段时间（500ms，1s等时间自定）再遍历下一个节点
- 增加一个输入框及一个“查询”按钮，点击按钮时，开始在树中以动画形式查找节点内容和输入框中内容一致的节点，找到后以特殊样式显示该节点，找不到的话给出找不到的提示。查询过程中的展示过程和遍历过程保持一致
- [demo](http://mrkylinzhou.github.io/IFETask/task23/index.html "demo") 

## task24--->JavaScript和树（三） :
- 基于任务23，添加节点的选择、增加与删除的功能
- 点击某个节点元素，则该节点元素呈现一个特殊被选中的样式
- 增加一个删除按钮，当选中某个节点元素后，点击删除按钮，则将该节点及其所有子节点删除掉
- 增加一个输入框及一个“添加”按钮当选中某个节点元素后，点击增加按钮，则在该节点下增加一个子节点，节点内容为输入框中内容，插入在其子节点的最后一个位置
- [demo](http://mrkylinzhou.github.io/IFETask/task24/index.html "demo") 

## task29--->表单（一）单个表单项的检验 :
- 在页面中实现一个输入框与按钮，要求点击验证按钮后，对输入框中内容进行格式校验，并在其下方显示校验结果
- 校验规则：
- 1.字符数为4~16位
- 2.每个英文字母、数字、英文符号长度为1
- 3.每个汉字，中文符号长度为2
- [demo](http://mrkylinzhou.github.io/IFETask/task29/index.html "demo") 

## task30--->表单（二）多个表单项的动态校验 :
- 基于上一个任务（任务29），在页面中添加多个表单
- 要求:
- 表单获得焦点时，下方显示表单填写规则
- 表单失去焦点时校验表单内容
- 校验结果正确时，表单边框显示绿色，并在下方显示验证通过的描述文字
- 校验结果错误时，表单边框显示红色，并在下方显示验证错误的描述文字
- 点击提交按钮时，对页面中所有输入进行校验，校验结果显示方式同上。若所有表单校验通过，弹窗显示“提交成功”，否则显示“提交失败”
- [demo](http://mrkylinzhou.github.io/IFETask/task30/index.html "demo") 

# task31--->表单（三）联动 :
- 在页面中完成两个单选框，切换单选框的不同选项时下方显示的表单随之切换。
- 当选择在校生时，出现两个select下拉菜单，一个选择城市，一个选择学校，当选择非在校生时，出一个文本输入框
- 学校下拉菜单里的学校名单均为城市下拉菜单中所选的城市中的大学，当城市发生变化时，学校一起发生变化
- 城市及学校的数据随意编造即可，无需真实完整
- [demo](http://mrkylinzhou.github.io/IFETask/task31/index.html "demo") 