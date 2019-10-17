1.与仓库建立关联
git init
git add clone.txt  #这里是文档的名字
git commit -m "first commit"
git remote add origin https://github.com/Xiafeng666/Test.git
git push -u origin master
2.将仓库中已存在的内容进行了更改，上传
git add clone.txt 
git commit -m "change"
git push
3.将本地的新文件夹加入已关联仓库
git add baogao.docx
git commit -m "change"
git push
4.添加所有文件夹下所有文件到仓库中
git add .
git commit -m "change"
git push
4.克隆他人仓库
git clone https://github.com/ncepu-aiml-2019/st-201705000725/branches
5.删除仓库和本地中数据 #执行此命令后会移除本地文件
git rm clone.txt  
git commit -m “S”
git push 