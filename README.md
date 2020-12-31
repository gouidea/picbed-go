# picbed-go
上一个仓库太乱了，重新整理并完善一下


**PicGo 上 GitHub 图床配置：**
- 设定仓库名的时候，是按照“账户名/仓库名的格式填写”
- 设定分支名：main （之前是master）
- 将之前的Token黏贴在这里
- 存储的路径：可以写为`img/`，图片上传后就会存入`gouidea/picbed`的`img/`文件夹里
- 设定自定义域名：它的的作用是，在图片上传后，PicGo 会按照自定义域名+上传的图片名的方式生成访问链接。
  默认是`https://raw.githubusercontent.com/用户名/RepositoryName/分支名`
  使用 jsDelivr CDN 加速 GitHub 图床后可写为：`https://cdn.jsdelivr.net/gh/用户名/仓库名`
  

**搭建教程**
1.新建一个 GitHub 仓库

2.新建此仓库的访问令牌

3.配置 PicGo 设置

4.上传图片，转成 jsDelivr 地址
