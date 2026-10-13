# Mypl 
# 母语编程语言
# My Programming Language

> 母语编程。底层是概念，表层是母语。编译后是同一棵抽象语法树。
> Mother-tongue programming. Concepts underneath, mother tongues on the surface. Compiled into the same AST.

名字里的 My 有两层含义：
The My in the name has two meanings:

- My = 我的语言
- My = My Language

- MY = 母语（Mu Yu）的拼音首字母
- MY = Initials of Mu Yu (mother tongue)

组织名后缀 -dev 不是"还没做完"，而是承诺：
The -dev suffix is not "not done yet", but a promise:

> -dev 不是状态，是承诺。发展，永不止步。
> -dev isn't a status. It's a promise. Always evolving.

一门语言如果宣称自己"完成"了，那它就死了。
A language that claims to be "complete" is dead.

Mypl 永远在 -dev，永远在生长。
Mypl is always in -dev, always growing.

## 设计哲学
## Design Philosophy

- 底层是概念，表层是母语。
- Concepts underneath, mother tongues on the surface.

- 中文、英文、日文、俄文只是同一概念的不同表面写法。
- Chinese, English, Japanese, and Russian are just different surface spellings of the same concept.

- 编译器内核只认词法单元枚举和抽象语法树，不认任何自然语言字符串。
- The compiler core only recognizes Token enums and AST, never natural-language strings.

- 母语优先，极简核心，持续进化，开发者友好。
- Mother-tongue first, minimal core, continuous evolution, developer-friendly.

## 示例
## Example

中文：
Chinese:

my
设 x = 10
显(x)


英文：
English:

my
let x = 10
print(x)


两种写法编译后抽象语法树完全一样。
Two writings, exactly the same AST after compilation.

## 项目状态
## Project Status

早期开发阶段。当前重点：词法器 + 关键字表。
Early development. Current focus: Lexer + keyword tables.

## 许可证
## License

Apache-2.0
Apache-2.0

Mypl — 用母语，写世界。
Mypl — Write the world in your mother tongue.
