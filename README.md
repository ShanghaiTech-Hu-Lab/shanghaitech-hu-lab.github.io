# Huzoo

## brief

这一个基于Hexo搭建的网站.  

## git architecture

master branch (default)存放供github pages展示的网页.  
hexo 存放工程文件.  

## Quickly start

1. 安装node.js  
```bash  
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash  
nvm install 20  
```

2. 安装hexo  
```bash  
npm install -g hexo-cli  
```

3. clone仓库  
```bash  
git clone --branch hexo git@github.com:ShanghaiTech-Hu-Lab/shanghaitech-hu-lab.github.io.git huzoo  
```

4. 安装依赖  
```bash  
cd huzoo  
npm install   
```

5. 提交更改  
**确保你拥有ShanghaiTech-Hu-Lab org的编辑权限**  
```bash  
hexo g # 生成静态网页文件  
hexo d # 通过git部署(网页文件推送到github)  
git commit -m "update"  
git push origin hexo  # 工程文件推送到github  
```

## Tutorials

[hexo官方文档](https://hexo.io/zh-cn/docs/commands)


