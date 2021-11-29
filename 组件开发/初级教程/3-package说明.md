# 概念

# `npm run start`

- 编译组件项目代码，把生成的文件放入 `dist/{version}/tmp/widgets/`和 mendix 测试项目`tests/testProject/deployment/web/widgets/`
- zip 压缩`dist/{version}/tmp/widgets/`到 `dist/{version}/{packagePath}.{widgetName}.mpk`和`tests/testProject/widgets/{packagePath}.{widgetName}.mpk`
- 当源代码文件变化时重复上述活动并通知 mendix 测试项目刷新页面

# `npm run build`

- 编译组件项目代码，把生成的文件放入 `dist/{version}/tmp/widgets/`和 mendix 测试项目`tests/testProject/deployment/web/widgets/`
- zip 压缩`dist/{version}/tmp/widgets/`到 `dist/{version}/{packagePath}.{widgetName}.mpk`和`tests/testProject/widgets/{packagePath}.{widgetName}.mpk`
- 只运行一次
