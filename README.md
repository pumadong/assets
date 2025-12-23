# 使用 GitHub Pages + CDN (建立个人图床)

如果你希望将 GitHub 作为长期稳定的外链图床，建议配合 jsDelivr 加快访问速度。

配置流程：

创建一个专门存放图片的公共仓库（如 my-images）。

上传图片。

使用 jsDelivr 的链接格式进行访问，以绕过国内访问 GitHub 图片慢的问题： https://cdn.jsdelivr.net/gh/用户名/仓库名@分支名/路径/图片名.jpg
