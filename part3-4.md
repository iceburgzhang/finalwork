## 利用git将gitbook部署到GitHub上

+ 在GitHub上建立一个仓库，填写仓库的名称
+ 本地生成电子书后，执行以下命令，将电子书的内容制作成静态网页，变保存在docs目录中       
    `gitbook build .../.../docs`
+ 结合GitHub Page     
  新建一个Git代码库    
    `git init`
+ 将本地仓库与远程库关联     
 `git remote add origin <URl>`
+ 将本地代码库中所有文件添加到暂存区  
`git add .` 
+ 提交，添加注释    
`git commit -m 'test'` 
+ 将本地推送到GitHub   
    `git push -u origin master`


