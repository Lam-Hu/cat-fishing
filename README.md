# 小猫寻鱼

三关收集小游戏。目标是让小猫吃饱：第一关熟悉收集，第二关加入限时与巡逻狗，第三关在普通鱼与金鱼之间选择路线。

## 运行

双击 `index.html`，并保持 `style.css`、`game.js` 与它在同一目录。电脑用方向键或 WASD，手机可使用页面下方方向按钮。第一、二关通关后可点击下一关，也可以从菜单自由选关。

## 修改

把整个文件夹交给 TRAE。关卡数据位于 `game.js` 顶部的 `VERSIONS`；可以改角色、收集物、场景、目标或规则。先说明想要的行为，再试玩验证。学生作品不要求制作三关。

## 发布

将 `index.html`、`style.css`、`game.js`、`.nojekyll` 放在 GitHub 仓库根目录。仓库 Settings → Pages → Deploy from a branch → main → /(root)。部署完成后分享生成的 Pages 网址。

画面由 Canvas 和 CSS 绘制，音效由 WebAudio 合成，没有第三方图片、字体或音频依赖。课堂演示文档和讲稿不在本作品中。
