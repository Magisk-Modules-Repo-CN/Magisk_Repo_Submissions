# Magisk Repo Submissions
这是开发人员向 [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo) 提交他们的 Magisk 模块的地方。

## 指南:
1. 请先阅读[完整文档](https://github.com/Magisk-Modules-Repo/Magisk/blob/master/docs/README.MD)。 您应该对 Magisk 和 "git" 都有足够的了解，以便进行提交。
2. 在您的 Github 帐号中新建一个 repo ，上传您模块的文件到 repo 。 如果不想从头开始，那么请 fork 或 clone [Magisk 模块模板]（https://github.com/Magisk-Modules-Repo/magisk-module-template），并在那里添加文件。
3. **只有 `master` 分支对用户可见！** 如果您选择使用模块模板, 您必须手动创建 `master` 分支. **没有 `master` 分支的提交是不被允许的**
4. 通过 [创建一个 issue](https://github.com/Magisk-Modules-Repo/Magisk_Repo_Submissions/issues/new) 提交一个请求。 规则和格式将在下一节中详细说明。
5. 合作邀请将被发送到您的电子邮箱，请接受它，以便您有权限更新您的模块 repo 。 **您应该在 [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo) 上更新您的模块, 而不是您自己的 repo ！** 如果您的 repo 被 clone ，您可以删除自己 Github 帐号中的 repo ，因为它将不再被使用。
6. 当您升级您的 repo 完成后，请递增 `module.prop` 中的 `versionCode` 项。 Magisk Manager 将此值与本地安装的模块进行比较，以确定是否有可用更新。

## 请求格式
所有的请求都是通过 issues 完成的，并通过一个服务器进行处理 (代码在这个 repo 中)。您可以进行两个操作：

#### 提交：
创建一个新的 issue，标题以 **`[Submission]`** 开头, 然后提供一个链接到 **您的 repo**。

#### 移除:
如果您决定从在线 repo 中删除您的模块, 创建一个新的 issue ，标题以  **`[Removal]`** 开头, 然后提供一个链接到 **您在 [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo) 上的 repo**。
