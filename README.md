原作：emilyploszaj/emi（MIT许可证）。本仓库为其非官方fork，未经原作者认可或背书，沿用MIT许可证。

LMax-1.20 : 1.20/1.20.1的主要版本,1.20分支是旧的

更新日志及修复项请见[releases界面](https://github.com/LMaxRouterCN/LMaxs-Recipe-Viewer/releases)

emi作者在2026年10月31日就"我给issue里的求助者发了我的修复版emi"此事发表讲话:

```
———— 10楼 · emilyploszaj（EMI作者/维护者）· 2026-10-31 ————
请把这个修复直接提交成PR，而不是发布一个fork（没有源代码？）、让用户去
下载它、还建议他们用AI。如果你提不了PR，哪怕只是遵循MIT许可证、把你的
源代码改动上传，也能让我自己修掉这个问题。
```

**在我对其言语中事实性错误的反驳后,其表面上马上认错,然后在背地里将我拉黑**

```
———— 11楼 · LMaxRouterCN · 2026-10-31 ————
1. 我的fork有源代码。上游每一条分支都摆在那——1.18.2到1.21——外加我的
   修复分支。所以是哪种情况？你看见了readme分支，一条都没再点进去，就跑来
   发这条评论？还是压根没看？还是看了，发现README需要翻译，就关掉了页面
   ——因为现在把一段话贴进翻译软件都算"建议人用AI"了，截图发给ChatGPT让
   它翻译一下都算背叛人类了是吗？
2. MIT许可证不要求fork公开源代码。你每天都在MIT协议下发布这个项目。
   你是怎么做到不知道自己的许可证要求什么的？
3. PR在这——#1265。你10月7号关的。关PR这事我不反驳你：你没法直接点
   merge，你引用了贡献规范，那是你的自由。但你看代码了吗？你看了——你的
   原话："This is a reasonable feature PR."（这是一个合理的功能PR）。你读
   了代码。你称它合理。然后你把它关了。24天后你出现在这个帖子底下，教大家
   "直接提个PR修复就行"。整个修复不到20行。一个改动块。一个文件。任何
   键盘上有Ctrl+C和Ctrl+V的人都能修好它。包括你。如果你不愿意自己来
   Ctrl+C/Ctrl+V——那就等着。等我自己觉得可以完全遵守你的每一条规矩了，
   你自然会拿到你的PR。
4. 提醒我一下——这个bug开了多久了？你不修。我修好了，你依然看不见。
   我一开始发编译好的文件，你终于蹦出来了。还是选择性失明：你只看得见
   "他发了编译后的文件"，现在还试图把锅甩回我头上。你想干什么？如果你
   一直装死，我甚至都能理解你。但你偏偏挑这个时刻爬出来。你到底想干什么？
   恭喜——你成功让所有人看清了你是个什么人。
5. AI做得到。你做不到。
6. 我在给这个帖子存档，截图都留好了。删评论修不了bug。
7. 你到底在恐慌什么？
8. 是你先挑起对抗的。
9. 来啊，反击我。我不会像你一样逃跑躲藏。
```
```
———— 13楼 · emilyploszaj（EMI作者/维护者）· 2026-10-31 / 11-01（UTC）· issue #969 ————

【原文】You're right that I missed that you had more than a readme branch, not familiar with that practice and it's my mistake. I also don't know why I incorrectly remembered how MIT works, it's embarrassing of me to pretend to hold authority while making mistakes on the basics.

I'm not going to further engage with the rest of the large message here, excessively confrontational and hostile. I'm sorry, but this is a hobby and I have limited time and a lot of responsibilities.

To any other spectators, I'd prefer discussion here and in general on issues remains on topic and we don't go out of our ways to dunk on people.

For posterity, the PR mentioned is #1265 which was closed for targeting the wrong branch and the fix does appear simple. Leaving this in the comment for when I have time to take a further look at this bug and hopefully resolve it in all versions of EMI.

【译文】你说得对，我确实没注意到你不只有一个 readme 分支——我不了解这种做法，这是我的失误。我也不知道自己为什么把 MIT 许可证的规则记错了。一边端着权威的架子、一边在基础知识上犯错，这确实让我很难堪。那条长消息里的其余内容，我就不再继续回应了——对抗性过强、充满敌意。抱歉，但这毕竟只是我的业余爱好，我时间有限，还有许多别的责任要承担。致其他围观的各位：我希望这里——以及总体上所有 issue 里的讨论——都保持就事论事，也希望我们不要专门去嘲讽别人。留档备查：文中所提的 PR 是 #1265，因指向了错误的分支而被关闭，这个修复看起来确实简单。把这条留言放在这里，等我之后有时间再仔细看看这个 bug，并争取在 EMI 的所有版本中解决它。
```

这给你牛逼的,你心里极其清楚错在谁啊,那真是太可惜了,我失去了一个给你道歉的机会

<img width="1912" height="4224" alt="java lang IndexOutOfBoundsException  toIndex = 8 · Issue #969 · emilyploszaj emi" src="https://github.com/user-attachments/assets/6cee8a80-94d4-4aa8-a9a2-5a3a34c632f9" />
<img width="966" height="808" alt="屏幕截图 2026-11-01 015916" src="https://github.com/user-attachments/assets/a0dc9dab-8966-4670-8a54-9e9250c9ba01" />
<img width="941" height="504" alt="屏幕截图 2026-11-01 015901" src="https://github.com/user-attachments/assets/61fa40d8-df98-4b5d-a16a-15e876e20328" />

---

---

---


## 为什么会有这个 Fork / Why this fork exists

**中文**

本fork只为一个目的而存在：修复上游EMI的一个崩溃bug。

在1.20.1 Forge环境下，通过EMI/JEMI查看Mekanism激光牵引光束
（laser_tractor_beam）等配方时，`JemiRecipeHandler.createSlotsView`
中未经校验的 `subList` 结束索引会抛出 `IndexOutOfBoundsException`，
导致游戏崩溃。

该bug在上游被独立报告至少四次，至今全部未修复：

| 上游issue | 报告人 | 日期 | 状态 |
|---|---|---|---|
| #904 | Jacklz | 2025-03-24 | 仍开放 |
| #949 | CTNOriginals | 2025-05-14 | 仍开放 |
| #969 | LMaxRouterCN | 2025-05-27 | 仍开放 |
| MekanismEmpowered#5 | Meatwo310 | 2025-09-07 | — |

修复见commit `cedb10f`：将 `subList` 的结束索引钳制到输入列表长度
之内。单文件，16行。2026-10-04曾以PR #1265提交上游，2026-10-07被
维护者关闭（按仓库规范，PR应指向最新版本分支）。维护者其后在#969
确认 "the fix does appear simple"，并表示 "hopefully resolve it in
all versions of EMI"。

本fork面向1.20.1 Forge持续维护，沿用上游MIT许可证。基于
emilyploszaj的EMI，感谢原作。

**English**

This fork exists for one purpose: fixing a crash bug in upstream EMI.

On 1.20.1 Forge, viewing recipes such as Mekanism's laser_tractor_beam
via EMI/JEMI throws an `IndexOutOfBoundsException` from
`JemiRecipeHandler.createSlotsView` (an unchecked `subList` end index)
and crashes the game.

The bug has been independently reported upstream at least four times
and remains unfixed: #904 (2025-03-24), #949 (2025-05-14),
#969 (2025-05-27), all still open, plus MekanismEmpowered#5
(2025-09-07).

The fix (commit `cedb10f`) clamps the `subList` end index to the
input list size. One file, 16 lines. It was submitted upstream as
PR #1265 on 2026-10-04 and closed on 2026-10-07 (per repository
policy, PRs should target the latest version branch). The maintainer
later acknowledged in #969 that "the fix does appear simple" and
hopes to "resolve it in all versions of EMI".

Maintained for 1.20.1 Forge under the upstream MIT license.
Based on EMI by emilyploszaj — credit where due.
```
# EMI 崩溃bug事件全记录

所有条目来自GitHub公开记录（REST API逐字核对），时间除注明外均为UTC。
最后更新：2026-11-01

## 前史
- 2025-03-24 · Jacklz 报告 #904 "Index out of bounds crash" → 至今开放
- 2025-05-14 · CTNOriginals 报告 #949（物品悬停崩溃）→ 至今开放
- 2025-05-15 · CTNOriginals 在 #949 指出同问题已在 #904 报告
- 2025-09-07 · Lapis256 从 MekanismEmpowered#5（日语报告：ME终端
  EMI+JEI配方崩溃）交叉引用至 #969

## 报告与修复
- 2025-05-27 · LMaxRouterCN 报告 #969，附崩溃日志与复现配方链接
- 2026-02-08 · LMaxRouterCN 完成修复（commit cedb10f，单文件16行），
  在 #969 与 #949 附上编译文件；同日说明因版本号改动与代码改动
  混入同一commit，暂缓提PR
- （#969、#949 在此期间无维护者回应）

## PR
- 2026-10-04 · LMaxRouterCN 提交 PR #1265（指向1.20分支）
- 2026-10-05 · link-fgfgui 引用 CONTRIBUTING.md 第17行：PR应指向
  最新版本分支
- 2026-10-07 · emilyploszaj 关闭 PR #1265，原话：
  "This is a reasonable feature PR, but as mentioned you'll need to
  PR to the latest version."

## 2026-10-30 ～ 11-01
- 2026-10-30 · Recentiv：因该bug崩溃两次，询问修复计划
- 2026-10-30 · LMaxRouterCN：修复在代码层面极简单，指向fork的
  releases页面
- 2026-10-30 · Recentiv：可惜我使用1.19.2版本
- 2026-10-31 · emilyploszaj：
  "Please just PR this fix instead of releasing a fork (without
  source code?), asking users to download it, and suggesting they
  use AI. If you can't PR, even just following the MIT license and
  uploading your source code changes would help me fix this issue
  myself."
  （该fork为标准GitHub fork，携带全部上游分支与源码）
- 2026-10-31 · LMaxRouterCN 九点回复（含存档声明，见 #969）
- 2026-10-31/11-01 · emilyploszaj 回复，承认两处错误，原话：
  "You're right that I missed that you had more than a readme branch,
  not familiar with that practice and it's my mistake."
  "I also don't know why I incorrectly remembered how MIT works, it's
  embarrassing of me to pretend to hold authority while making
  mistakes on the basics."
  同时表示不再回应其余内容，并将 #1265 留档：
  "For posterity, the PR mentioned is #1265 which was closed for
  targeting the wrong branch and the fix does appear simple. Leaving
  this in the comment for when I have time to take a further look at
  this bug and hopefully resolve it in all versions of EMI."

## 封禁
- 2026-11-01 0点-1点（北京时间）· LMaxRouterCN 发现被 emilyploszaj 账号级
  拉黑（GitHub用户级拉黑对外不可见；发现过程有界面截图存档）

## 当前状态（2026-11-01）
- #904 / #949 / #969：全部开放
- PR #1265：已关闭，未合并
- 上游修复：无
- 本fork（1.20.1 Forge）：修复可用，源码公开
```