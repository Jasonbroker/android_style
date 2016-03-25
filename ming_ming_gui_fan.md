# 命名规范

1. 类命名
------------------------
* 包
  + **包名必须全部小写，2个以内单词**
  + 最好为 1 个单数名词
  + **所有项目的包都要以“com.****”为父包**
* 类
  + **类中每个单词的首字母必须大写**
  + **每个类都以功能性名词结尾，如xxxActivity,xxxFragment,xxxView,xxxAdapter**
  + **每个类的都应该加上类注释，包括所有者、邮箱及日期**
* 接口
  + **如果接口表示一个事件，则应该取名为OnXxxListener**
  + 如果表示一种能力，应以"able"、"ible"结尾
* 方法
  + **大小写字母混合组成，第一个单词的首字母小写，其后单词的首字母大写**
  + **继承的方法可以省略注释，但是被继承方法必须有注释。**
* 变量
  + **如果是集合或数组，用复数名词，如pets,houses**
  + **成员变量能private就不要default，能default就不要protected，最好不要public**
  + 不要在activity中使用静态成员变量
  + 不推荐使用下划线
  + 局域变量名要尽量短，推荐用缩写，比如 StringBuilder sb
  + 非公有，非静态成员变量以m开头
  + 静态成员变量以s开头
  + 其他变量以小写字母开头
* 常量
  + 只能包含字母和\_，字母全部大写，单词之间用\_隔开
* 注释
  + **注释必须和代码保持同步**
  + **注释中的第一个句子要以（英文）句号、问号或者感叹号结束**
  + **如果注释中有超过一个段落，用\<P\> 标签分隔**
  + **如果注释中有多个章节，用 \<H2\> 标签声明每个章节的标题**
  + **如果注释需要换行，用 \<BR\> 标签**
  + **示例代码以 \<PRE\>\</PRE\> 包裹**

2. 资源命名规范
------------------------
* 尽量以结构开头，业务结尾，中间用下划线区分:
  + layout: activity\_house,fragment\_house,view\_house,listitem\_house
  + drawable: selector\_house,shap\_house
* 控件id：尽量以对应控件的各单词英文首字母结尾，如TextView就以tv结尾(house\_tv)，ImageView就以iv结尾(house\_iv)，CheckBox就以cb结尾(house\_cb)，Button就以btn结尾(house\_btn)等
* 菜单（menu）的id：建议以action开头,如action\_house

