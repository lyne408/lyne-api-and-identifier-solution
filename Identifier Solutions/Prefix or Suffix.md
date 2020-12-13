# Prefix or Suffix

## Use Prefix or Suffix?

<conclusion>
推荐使用 **suffix**.
</conclusion>

<reason>
功能性描述应放在前面.
重心在功能, 而非额外的修饰.
额外的修饰应作为后置定语.
</reason>

<example>
- `pathModule`

- `mkdirLocal()`
	局部函数 mkdir
</example>

## Part of Speech 词性

如果是 noun 后缀, 没有争议. 如 `pathModule`.

如果是 adjective 或 adverb, 可能存在歧义. 如 `mkdirLocal()` 与 `mkdirLocally()`

<conclusion>
用 adjective 修饰标识符, 如 `mkdirLocal()` 表示局部函数 `mkdir()`.
用 adverb 修饰功能, 如 `mkdirRecursively()` 表示递归地创建目录.
</conclusion>
