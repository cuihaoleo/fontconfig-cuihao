# fontconfig-cuihao
将 CJK 字体分类为黑体、明体（宋体）、仿宋、楷体四类，黑体对应西文衬线字体，后三类对应非衬线字体。

然后根据应用程序提供给 fontconfig 的语言设置，机智地选择合适的 CJK 字体。

实际上也没什么卵用，因为多数应用程序都不会区分所显示字体的语言。

Firefox 可以用，然而你也可以在其设置页里直接指定各种语言使用的字体。根本不用写 Fontconfig 啦。

