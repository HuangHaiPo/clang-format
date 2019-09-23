# .clang-format
.clang-format是XcodeClangFormat格式化工具自定义格式化规则文件(Xcode自定义代码格式化样式文件)。
文件内容如下，也可以自己修改。[具体讲解可以看这篇文章](https://www.cnblogs.com/PaulpauL/p/5929753.html)。

```
# 工具 https://github.com/mapbox/XcodeClangFormat
# 函数名详细地址 英文 http://clang.llvm.org/docs/ClangFormatStyleOptions.html
# 函数名详细地址 中文 https://www.cnblogs.com/PaulpauL/p/5929753.html

# 基于样式
BasedOnStyle: LLVM

# 对齐注释
AlignTrailingComments: true

# 指针和引用的对齐方式
PointerAlignment: Right

# 用于缩进的列数
IndentWidth: 4

# switch的case缩进
IndentCaseLabels: true

# OC里面，在@property后加空格
ObjCSpaceAfterProperty: true

# OC里面，在Protocol前后加空格
ObjCSpaceBeforeProtocolList: true

# 单行注释前的空格数
SpacesBeforeTrailingComments: 1

# 连续的空行保留几行
MaxEmptyLinesToKeep: 1

# 保留block里面的空行
KeepEmptyLinesAtTheStartOfBlocks: false

# 每行字符的限制，0表示没有限制
ColumnLimit: 0

# []中添加空格
SpacesInSquareBrackets: false

# ()中添加空格
SpacesInParentheses : false

# 容器类前添加空格
SpacesInContainerLiterals: true

# 赋值运算符前加空格
SpaceBeforeAssignmentOperators: true

# 在空括号中加空格
SpaceInEmptyParentheses: false

# 在<>中间插入空格
SpacesInAngles: false

# 换行的时候对齐操作符
AlignOperands: true

# 括号中的(),{},[]代码对齐方式
#AlignAfterOpenBracket: Align

#ContinuationIndentWidth: 0

# 赋值=对齐
AlignConsecutiveAssignments: false

# 声明参数对齐
AlignConsecutiveDeclarations: false

# 运算符位置
BreakBeforeBinaryOperators: None

# 允许短的函数放在同一行
#AllowShortFunctionsOnASingleLine: None

# 允许case在同一行
AllowShortCaseLabelsOnASingleLine: false

# 允许if在同一行
AllowShortIfStatementsOnASingleLine: false

# 允许while在同一行
AllowShortLoopsOnASingleLine: false

# 允许将简单的语句块放到同一行
AllowShortBlocksOnASingleLine: false

#缩进函数名
IndentWrappedFunctionNames: false

# 形参 如果为false要么都在同一行，要么各有一行
BinPackParameters: false

# 实参 如果为false要么都在同一行，要么各有一行
BinPackArguments: false

# 大括号换行
BreakBeforeBraces: Custom
BraceWrapping:
  # class定义后面
  AfterClass: true
  # 控制语句后面
  AfterControlStatement: false
  # enum定义后面
  AfterEnum: false
  # 函数定义后面
  AfterFunction: false
  # 命名空间定义后面
  AfterNamespace: false
  # struct定义后面
  AfterStruct: false
  # union定义后面
  AfterUnion: false
  # catch之前
  BeforeCatch: false
```