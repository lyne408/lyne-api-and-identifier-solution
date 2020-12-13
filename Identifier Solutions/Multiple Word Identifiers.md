# multi-word identifier solution

"多 word 标识符" 规范 by lyne408.

编程时常常遇到一个标识符, 由多个单词构成.

## 连接多个 word 的方式

- "_" 连接

- "-" 连接

- camel


## 需求

- performance

	pass 掉 "_" 和 "-", 字符越多处理越慢.
	
	即便是非用户可见的字符串 literal, 比如仅开发使用的 enum 字符串, 字符串越少, 性能也越加.
	
	不区分大小写, 会降低性能, 所应严格区分大小写.

- 在编辑器鼠标双击能选中整个字符串(或是标识符)

	pass 掉 "-" 连接

- SEO

	当代 SE 应是可以把 url 中的 camel 处理成多个单词的.
	Google 搜索时, 若键入的是 camel, Google 会建议搜索构成该 camel 多个单词.

## solution

使用 camel.

**是否优先遵从编程语言相关的 code style?**

本方案只是要求多 word 标识符用 camel. 并没有限制其它的.

C# 的 public method 首字母大写, 也是 camel 吧.

至于 html, xml, 大众习惯上虽然使用 "-", 但本方案推荐 camel.