# 工记 隐私政策与用户协议（公开托管页）

HarmonyOS 应用「工记」(`com.zeng1071230.worklog`) 用于 AppGallery Connect「自定义隐私政策」的公开页面。

- 隐私政策：`index.html`
- 隐私权利说明：`rights.html`
- 用户协议：`agreement.html`

内容不是手写的：由应用工程 `tools/gen_privacy_site.mjs` 从 `entry/src/main/ets/app/PrivacyDocs.ets` 生成。
修改政策请改 `PrivacyDocs.ets` 后重跑生成脚本并把产出的 HTML 同步到这里，不要直接编辑本仓库的 HTML。
