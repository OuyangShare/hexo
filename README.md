# hexo

快速搭建
npm install -g hexo-cli
hexo init

本地预览：
hexo s

部署：
npm install hexo-deployer-git --save

hexo clean（清除缓存）
hexo g（上传到仓库）
hexo d（部署）

相关配置：
_config.yml

deploy:
  type: git
  repo: {{ repo path }}
  branch: {{ branch name }}
  
URL
url: http:xxxxxxxx
permalink: :year/:month/:day/:title/
permalink_defaults: 
