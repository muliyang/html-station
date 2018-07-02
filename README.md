# html-station
    // new  repository  : 创建一个远程的仓库；
    // git remote -v  查看当前仓库和远程仓库的关联；

    // git remote add n[自定义]  + 仓库地址 ： 把远程仓库和当前仓库进行关联；
    // git fetch n[自定义]  master: 从远程仓库把资源拉取到本地；
    // git pull n master =  git fetch + git merge; (拉取还进行合并)

    // 把本地仓库资源上传到远程仓库；
    // git add  . / -A ： 把工作区提交到暂存区
    // git commit -m"注释" ： 把暂存区提交到历史区；
    // git push 仓库名n【自定义】 master ：把历史区的代码提交到远程仓库；
    // git pull origin master --allow-unrelated-histories；处理远程和本地冲突的；

    // 如果文件夹是空的，那么不会提交到远程仓库；

    // git clone + 仓库地址： 把远程仓库克隆到本地；
    
    // git  init : 初始化git ；让当前文件夹被git所管理；
    // git  status : 查看当前git仓库状态；
    // git  add  .  / -A  : 把工作区代码提交到暂存区；
    // git  commit  -m"注释"
    // 在工作区的文件时红色的，在暂存区中是绿色的； 而且git不能直接从工作区提交到历史区；
    // git  log  : 查看日志 ； 各个版本号；

    // git  reset  HEAD 删除暂存区之前的提交状态

    // git  checkout  1.txt : 把暂存区文件覆盖本地的文件；

    // git  diff  : 工作区和暂存区的比较
    // git  diff  --cached :暂存区和历史区比较
    // git  diff  master : 工作区和历史区比较；
