# 作品集网站上线步骤（GitHub Pages，$0）

你的 GitHub 用户名：`mirandatan814`
网站上线后的地址：**https://mirandatan814.github.io**

## 第一步：创建网站仓库（5 分钟）

1. 登录 https://github.com/mirandatan814
2. 点右上角 **+** → **New repository**
3. Repository name 必须填：`mirandatan814.github.io`（一字不差，这是 GitHub 认定的"个人主页仓库"）
4. 选 **Public**，勾选 **Add a README file**，点 **Create repository**

## 第二步：上传网站文件（5 分钟）

1. 进刚建好的 `mirandatan814.github.io` 仓库，点 **Add file** → **Upload files**
2. 把本压缩包里所有文件（`index.html`、`work.html`、`skills.html`、`about.html`、`case-study-template.html`、`styles.css`）一起拖进去
   - ⚠️ 不要上传这个 README.md（它是给你看的说明）
3. 点 **Commit changes**，等 1–2 分钟
4. 打开 https://mirandatan814.github.io 就能看到网站了 🎉

## 第三步：改成你的内容

所有要改的地方，文件里都标了 `✏️` 中文注释，直接搜 `✏️` 一个个改就行。主要改：

- `index.html`：首页一句话介绍、LinkedIn 链接
- `about.html`：个人介绍、邮箱
- `work.html` + `case-study-template.html`：案例内容
- `skills.html`：每个 skill 卡片的 `href` 换成你将来建的 skill 仓库地址

改完后重新上传同名文件覆盖即可（GitHub 网页上点文件 → 右上角 ✏️ pencil 图标可直接在线编辑，更方便）。

## 第四步：加新案例（以后）

1. 复制 `case-study-template.html` → 改名 `case-xxx.html`（英文小写）
2. 按模板里的 5 个部分填写：背景与研究问题 → 方法 → 关键发现 → 影响 → 反思
3. 在 `work.html` 里复制一张卡片，`href` 指向新文件名

## 第五步：发布 AI skill（以后）

每个 skill 单独建一个仓库，例如 `screening-skill`，里面放：

```
screening-skill/
  SKILL.md      ← skill 说明 + agent 执行步骤（必须）
  README.md     ← 一句话介绍
  templates/    ← 可选：模板文件
```

然后在 `skills.html` 里把对应卡片的链接指向该仓库。

## 文件清单

| 文件 | 说明 |
|---|---|
| `index.html` | 首页：介绍 + 精选案例 + skill 预览 |
| `work.html` | 案例列表页 |
| `case-study-template.html` | 案例模板（背景/方法/发现/影响/反思五段式） |
| `skills.html` | AI Skills 页 |
| `about.html` | 关于我 + 联系方式 |
| `styles.css` | 全站样式（改 `:root` 可换配色） |

---

*以后想更好看：可以用 v0 / Lovable 生成页面，把代码传到这个仓库覆盖即可，托管永远免费。*
