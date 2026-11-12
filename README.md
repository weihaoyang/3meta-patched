# 3meta patched

这是 [3meta 2.6.0](https://github.com/3metaJun/3meta) 的修改版，保留原作者 MIT 许可证和 [上游说明](README.upstream.md)。它用于为奇门研究统一提供固定版本，而无需安装后修改其他依赖的文件。

## 修改范围

- 年月精确干支可由调用方指定；保留节气与强制阴阳遁回退。
- 值使从中五宫起算，中五寄坤二，寄宫含两个天盘干时逐一检查六仪击刑。
- 修改同时作用于 CommonJS 与 ESM 构建；未发布未经同步修正的浏览器压缩构建。

这些计算口径及异文见 [奇门仓库](https://github.com/weihaoyang/qimen-core) 与其测试。修改版源码为上游 npm 分发的 JavaScript 和声明文件；上游 TypeScript 源代码及其提交历史见上游项目。

本仓许可证为 [MIT](LICENSE)，版权所有者及原声明保持不变。
