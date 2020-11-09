# URFC-4: meta URFC: the process of URFC

## URFC 运行流程

### 创建

所有的URFC通过提交一个 Issue 来创建。Issue模板参考 `.github/ISSUE_TEMPLATE/rfc-cn.md`（中文）或者 `.github/ISSUE_TEMPLATE/rfc-en.md`（英文）。

RFC对应的编号即当时创建RFC时的Issue编号。

### 完善

通过issue的内容讨论来完善RFC内容，对于需要额外实现的，可以在组织内新建repo来进行进一步的设计和实现。

### 文档化

RFC有初步结论后，可以形成落实的RFC文档，通过创建Pull Request来把文档合并到当前仓库。

### 批准和合并

RFC文档化的Pull Request需要至少一个除PR作者外的成员批准。

### 更新和废弃

新的RFC可以补充旧RFC，或者废弃旧的RFC。但已经落实为文档的RFC，除了修复文案错误以外，不能再有改动。

