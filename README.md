# PK Atlas · 学习与职业工作台

中文互动学习网站，面向 PK scientist、pharmacometrics、systems pharmacology 及临床药理学相关职业发展。

## 功能

- 六条主题路径：Clinical PK / NCA、PopPK / PKPD、PBPK、MIDD / 转化药理、监管申报与质量、计算与建模工具。
- 比较 preclinical PBPK、preclinical PKPD、clinical PK/NCA 和 clinical PK/PD 的职责、输入、交付物与审阅重点。
- 学习资源、笔记与完成状态：书籍、文献、视频、case study、SOP、CPAP、CSR、ICH GCP / ICH E6、ALCOA+、Phoenix WinNonlin、NONMEM、R 和 MATLAB。
- 岗位差距自评、每周任务、案例练习、复习清单与面试回答。
- 浏览器自动保存，支持 JSON 备份导出与导入。

## 运行

本项目为无依赖的静态 HTML / CSS / JavaScript 网站。入口为根目录 `index.html`，无需构建。

推荐在项目目录执行：

```sh
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 可选：GitHub Pages

本次仅上传源码，未启用 GitHub Pages。仓库管理员可在仓库 Settings → Pages 中选择从 main 分支的根目录发布。发布状态与最终访问地址以 GitHub Pages 页面显示为准。

原 Sites 站点：https://pk-career-lab-bohan.guidingsardine64.chatgpt.site

GitHub Pages 与 Sites 的访问控制独立。GitHub Pages 发布后的站点通常公开访问，源码不包含 Sites 的私人登录保护。

## 学习数据与迁移

学习记录存放在当前浏览器的 localStorage，不会提交到 GitHub，也不会跨浏览器或域名自动同步。请在“学习资源库”导出备份，再在新地址导入。清除浏览器数据前请备份。

本项目不包含真实受试者数据、内部 SOP 文件或研究报告。资源库中的 SOP / CPAP / CSR 内容是学习任务提示；请使用获得授权或自行创建的模板。案例为教学练习，实际项目应遵循 protocol、CPAP 和适用流程。

## 修改

编辑 `index.html` 即可更改内容和功能。GitHub 中的更改不会自动同步到原 Sites 站点；两个部署需要分别更新。
