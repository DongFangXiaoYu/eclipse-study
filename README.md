# eclipse-
eclipse快捷键的使用


	Ctrl+Shift+L				显示所有快捷键
	Ctrl+K						参照选中的词(Word)快速定位到下一个
	Ctrl+Shift+K				参照选中的词(Word)快速定位到上一个
	
	Ctrl+O						快速显示OutLine 
	Ctrl+T						快速显示当前类的继承结构
	Ctrl+Shift+X				把选中文本全部改为大写
	Ctrl+Shift+Y				把选中文本全部改为小写
	Ctrl+Shift+F				按照当前的配置文件格式化源代码
	Ctrl+L						弹出行定位框以便定位到某一行
	Ctrl+Numpad_Divide
	Ctrl+/(小键盘)				使代码折叠可用
	Ctrl+Numpad_Multify
	Ctrl+*(小键盘)				展开当前类中的所有代码
	Ctrl+Shift+Numpad_Divide
	Ctrl+Shift+/(小键盘)		折叠所有,如果不能全部成功折叠,
								将光标移到文档最后试着或多按几次
								折叠当前类中的所有代码
	Ctrl+1						快速修正,需要导包的时候出现导包提示界面,
	Ctrl+Q						定位到最后编辑的地方
	Ctrl+Shift+m				导入当前行上需要的包(add import)
	Ctrl+Shift+o				导入所有需要的包(organize imports)
	Shift+Enter					在当前行的下一行插入行
	Shift+Ctrl+Enter			在当前行的上一行插入行
	Alt+/						语法补充快捷
	Ctrl+MouseLeft				当按住Ctrl时,将Mouse移动到一个类或类的方法或属性时,
								左键点击会进入到源文件内进行查看
								如果没找到源文件,而需要指定Sourece,
								比如说JDK自身的src.zip文件或源文件所在的文件夹
	Ctrl+/	==	Ctrl+Shift+C	注释选定行或取消注释
	Ctrl+Shift+/				用*...... */注释选定行
	Ctrl+Shift+\				取消/*...... */注释
	Ctrl+D						删除当前行
	Shift+<						在当前位置插入成对的尖括号:<>
	Ctrl+Alt+down				复制当前行到下一行 
	Ctrl+Alt+up					复制当前行到上一行
	Ctrl+Alt+J					Join Lines连接行
	Alt+down					当前行和下面一行交换位值 
	Alt+up						当前行和上面一行交换位值 
								选定光标所在的行通过用这两个快捷各执行一次来完成
	Alt+left					前一个编辑的代码页面或在当前页面中上一个光标的位置 
	Alt+right					下一个编辑的代码页面或在当前页面中下一个光标位置
								(当使用了Alt+←后)
	Alt+Shift+O					(或点击工具栏中的Toggle Mark Occurrences按钮)
								当点击某个标记时可使本页面中其他地方的此标记黄色凸显,
								并且窗口的右边框会出现白色的方块,点击此方块会跳到此标记处								
	
	Shift+Home					选定光标处到行首的内容
	Shift+End					选定光标处到行尾的内容
	
	Ctrl+Shift+Home				选定光标处到首行行首的内容
	Ctrl+Shift+End				选定光标处到尾行行尾的内容
	Ctrl+Shift+P				定位到与之成对匹配的括号{或)
								(从前面定位后面时,光标要在匹配符之后,从后往前定位,反之) 
	Tab与Shift+Tab				选中要移动的代码后,按Tab键右移,按Shift+Tab键左移
	Ctrl+up	
	Ctrl+down					上下滚动编辑页面
查找:
	Ctrl+Shift+R				相当于Navigate->Open Resource...
								输入Java源文件名或类名,会按通配的方式列出符合条件的.java源文件
	Ctrl+J						正向增量查找(按下Ctrl+J文件你所输入的每个字母,
								编辑器都提供快速匹配定位到某个单词,如果没有,
								则在stutes line中显示没有找到了,查一个单词时,特别实用,
								这个功能Idea两年前就有了)
								
	Ctrl+Shift+J				反向增量查找(和上条相文件只不过是从后往前查) 
窗口:
	Ctrl+M						窗口最大化与恢复大小转换
								最大化当前的Edit或View(再按则恢复)
	
	Ctrl+W						关闭当前Editor
	Ctrl+Shift+F4				关闭所有打开的Editor 
								
	Ctrl+E						快速显示当前Editor的下拉文档列表
	Ctrl+Shift+E				显示管理当前打开的所有的View的管理器(可以选择关闭,激活等操作)								 
	F2							当鼠标放在一个标记处出现Tooltip时候,
								按下F2会铆钉显示的 Tooltip 框
	F3							跳到声明或定义(源文件)处
	Alt+Enter					显示当前选择资源(工程,or 文件 or文件)的属性
	
	Ctrl+PgUp					
	Ctrl+PgDown					切换代码窗口的各个文档,
								如果切换到头就会打开"Show List"下拉框
								在此下拉框里显示有最近曾打开的文件,
								连续按可移动选中项
								对于XML文件是切换代码和图示窗口
	
	Alt+Shit+w					在光标处弹出选择view的菜单
								在Package窗口下,弹出Navigator与Properties的选择菜单
												
	Alt+Shift+Q,Q				弹出"Show View"选择界面
	Alt+Shift+Q,T				Show View(View:	Hierarch)
	Alt+Shift+Q,B				Show View(View: Breakpoints)
	Alt+Shift+Q,H				Show View(View: Cheat Sheets)
	Alt+Shift+Q,C				Show View(View: Console)
	Alt+Shift+Q,L				Show View(View: Error Log)
	Alt+Shift+Q,Z				Show View(View: History)
	Alt+Shift+Q,J				Show View(View: Javadoc)
	Alt+Shift+Q,O				Show View(View: Outline)
	Alt+Shift+Q,P				Show View(View: Package Explorer)
	Alt+Shift+Q,X				Show View(View: Problems)
	Alt+Shift+Q,S				Show View(View: Search)
	Alt+Shift+Q,Y				Show View(View: Synchronize)
	Alt+Shift+Q,V				Show View(View: Variables)
Debug:
	F5							单步调试进入函数内部
	
	F6							单步调试不进入函数内部
	F7							由函数内部返回到调用处
	
	F8							一直执行到下一个断点
Refactor 重构(一般以Alt+Shift开头):
	Alt+Shift+R		重命名被选中的变量
	Alt+Shift+M		抽取方法 
	Alt+Shift+C		修改函数结构
	Alt+Shift+L		抽取本地变量
	Alt+Shift+F		把Class中的local变量变为field变量(MyEclipse中需要自定义)
	Alt+Shift+I		合并变量(可能这样说有点不妥Inline)
	Alt+Shift+V		移动方法和变量不怎么常用
	Alt+Shift+Z		重构的后悔药(Undo) 
