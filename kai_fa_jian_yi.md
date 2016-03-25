# 开发建议

------------------------
* 所有的非AtionBar的界面均采用Fragment（片段式）来实现，在Activity中只做Fragment对象的管理以及ActionBar的处理工作
* 多线程编程时，采用Loader来代替AsyncTask和Thread
* 按功能对Activity和Fragment进行分包（可以考虑将相同功能模块的Activity和Fragment放在同一个包下）
* 不要使用静态全局变量，如果确实需要，可以考虑将其作为Application的成员变量（慎用）
* 如果仅希望一段代码在UI线程执行，可以考虑使用activity.runOnUiThread方法
* 不要在Activity或者Fragment中写跟界面无关的代码
* 不要捕获不处理的异常

