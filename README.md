# developer-guide

## 开发者代码提交流程和规范


### 分支规范（branch）


所有仓库都必须具备两个分支 `master` 和 `dev`

    master 分支需与生产环境一致
    
    dev 分支需为开发版的最新代码
    
    
 ### 代码开发与提交流程
 

1. 每天 `上班后` 统一  `pull` 项目的最新代码（本组织仓库中的 `dev` 分支）到本地开始开发工作。


2. 每天 `下班前` 统一发起 `pull request` 提交当天写的代码。


3. `code reviewer` 下班之前需要审查并批准组员提交的 `pull request`，审核批准完毕后方可下班。


4. `pull request` 时请注明`做了哪些改动`，`会产生什么效果`。 「具体格式待定，前期先以流水账的形式列出」


5. `code reviewer` 需要保证 dev 分支为项目库`统一的`、`最新的` 开发版代码。


### 小组


多人小组：具有项目写权限的 `code reviewer` 也需要通过 `fork + pull request` 的流程进行开发。


单人：可以直接 `push` 代码到非 `master` 和 `dev` 分支，自己进行 `pull request`。


### 注意事项


为避免冲突，所有项目参与者 🚫 禁止以直接 `push` 的方式向本组织代码仓库提交代码。


对 `dev` 仓库代码的更新，必须以 `fork + pull request` 的形式进行。


禁止 🈲 向 `master push` 代码， `master` 只允许接受来自 dev 分支的合并。


另外请注意：❤️ 上下班的定义为，`上午` 和 `下午` 。 每人每天需要有两次 `pull` 最新分支 + `pull request` 提交开发的代码到开发仓库。


### commit 规范

为方便 code reviewer，commit 请以少量多次的方式进行，清晰书写 commit 信息。「具体格式待定」

### github 账号保护


本组织的所有github账号必须 `开启双因素验证`

