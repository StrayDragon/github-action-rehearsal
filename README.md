🤔 记录一些 :octocat:Github Actions 的实践

<!--
TODO: 英文文档和链接
--> 

## PR

### 在PR中打上特定tag触发处理逻辑
- [x] 自动使用`black`格式化PR中修改的python文件, 并commit更改到该PR [here](./.github/workflows/snippet-pr-with-label-trigger-commit-actions.yml)
- [x] 自动使用`black`格式化PR中修改的python文件, 并创建一个新的PR包含更改 [here](./.github/workflows/snippet-merged-pr-with-label-trigger-pr-actions.yml)

