# Great plan of 2017

# Preact
# React
# Koa
# Vue
# Node
# Git
  - https://github.com/Gazler/githug
  - http://www.jianshu.com/p/482b32716bbe
  - http://backlogtool.com/git-guide/cn/


## 标签
  - 轻标签

  ```
  $ git tag <tagname>
  ```

  添加apple标签

  ```
  $ git tag apple
  ```
  如果没有使用参数而执行tag，可以显示已有标签列表。

  ```
  $ git tag
  ```
  - 注解标签

  若要添加注解标签，可以在tag命令指定 -a选项执行。
  执行后会启动编辑区，请输入注解，
  也可以指定-m选项来添加注解。
  ```
  $ git tag -a <tagname>
  ```

  在HEAD指向的提交里添加名为banana的标签，请执行以下的命令。

  ```
  $ git tag -am "连猴子都懂的Git" banana
  ```

  如果在tag命令指定-n选项执行，可以显示标签的列表和注解。

  ```
  $ git tag -n
  apple           first commit
  banana          连猴子都懂的Git
  ```

  － 删除标签
  
  ```
  $ git tag -d <tagname>
  ```

## 新建分支

  新建一个开发分支 develop
  ```
  $ git branch -b develop
  ```

## 提交分支

  分支修改后，就可以提交commit了。
  ```
  $ git add .
  $ git status
  $ git commit --verbose
  ```

## 合并分支

  该命令将 **指定分支** 导入到HEAD指定的分支。
  ```
  $ git merge <commit>
  ```

  合并 develop 分支到 release
  ```
  // Switched to branch 'release'
  
  $ git checkout release
  $ git merge develop
  ```

## 删除分支

  branch命令指定-d选项，删除指定分支.
  ```
  $ git branch -d <branchname>

  // 删除temp分支
  $ git branch -d temp
  ```

## Git规范

  **提交 commit 的类型，包括以下几种:**

  - feat: 新功能
  - fix: 修复问题
  - docs: 修改文档
  - style: 修改代码格式，不影响代码逻辑
  - refactor: 重构代码，理论上不影响现有功能
  - perf: 提升性能
  - test: 增加修改测试用例
  - chore: 修改工具相关（包括但不限于文档、代码生成等）
  - deps: 升级依赖

  修改文件的范围（包括但不限于 doc, middleware, proxy, core, config, plugin）
  用一句话清楚的描述这次提交做了什么
  
  **分支的划分**

  - 主分支(master)
  - 开发分支(develop)
  - 特征分支(feature)
  - 发布分支(release)
  - 修复分支(hotfix)

  master和develop是长期分支，master分支上是稳定版本的演进，develop保持最新代码；而feature/release/hotfix是研发过程中的短期辅助分支，开发后需要清除；

  **约定版本号**

  简单而言，在这个版本规范中，版本以X.Y.Z的形式存在，其中X表示不向下兼容的框架级改动版本，Y表示向下兼容的功能性新增版本，Z表示向下兼容的内部问题修复版本。

  ```
  v1.2.4
  ```


# CI
# UAE
  - http://doc.ucweb.local/pages/viewpage.action?pageId=13435490

# Mongodb

# npm

# UCBrowser
  识别为UC浏览器，在链接的后面加上参数：
  pf=178&ut=AAKUj5W%2BQ928%2FdAiH8%2FMuMMJu3TCCW%2FAjvMxSqu4QrdECw%3D%3D