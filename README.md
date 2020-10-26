# picbed-go
上一个仓库太乱了，重新整理并完善一下


**cGo 上 GitHub 图床配置：**
- 设定仓库名的时候，是按照“账户名/仓库名的格式填写”
- 分支名统一填写“main”
- 将之前的Token黏贴在这里
- 存储的路径：可以写为`img/`，图片上传后就会存入`ouidea/picbed`的`img/`文件夹里
- 自定义域名的作用是在上传图片后成功后，PicGo会根据“自定义域名+上传的图片名”生成访问链接，设置格式为
`https://raw.githubusercontent.com/用户名/RepositoryName/分支名`

**jsDelivr CDN 全球加速**

简单说就是替换上一步的自定义域名
将链接换为 `https://cdn.jsdelivr.net/gh/{user}/{repo}/图片路径`
