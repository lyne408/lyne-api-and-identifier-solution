# lyne-api-and-identifier-solution

Personal identifier and API standard, WIP.

lyne408 个人使用的 identifier 和 API 方案, 即个人规范, WIP.

API 包含 `class`, `function`, `property` 等, 这些都有 identifier.

本项目用以解决以下问题.

## Issues

- 是使用 "-", 还是 "_", 还是 camel 连接多 word 的标识符

- 有些标识符可能存在很大歧义

	比如 `fileName`, 不其是否包含文件扩展名.
	
	本方案约定 `fileName` 表示不包含扩展名, `fullFileName` 表示包含扩展名.

- 不同编程语言的 API 的标识符有所差异, 开发人员习惯也不同.

	比如表示 字符串包含某个子串的 API:
	
	JavaScript 采用 `includes()`, C# 采用 `Contains()`.
