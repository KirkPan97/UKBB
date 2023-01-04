# Metlab课题组———UKBB项目协作仓库
## Github仓库使用方式和管理规范

### 1. 软件和网络要求
  推荐使用 Github Desktop 软件进行操作，相比使用 Git 命令操作有更好的交互性。  
  Github Desktop 软件下载：https://desktop.github.com/
    
### 2. 关联本地仓库
  打开 Github Dsktop 软件，依次选择 File -> Clone repository；  
  选择Github.com选项卡，在第一个地址栏填写本仓库网址（https://github.com/KirkPan97/UKBB/ ） 、在Local path地址栏填写本地仓库存放地址；
  
  <img width="381" alt="image" src="https://user-images.githubusercontent.com/102509476/210510974-27df51e6-c63b-4e80-8ba8-76b2e16474eb.png">
  点击Clone按钮即可将仓库内容同步到本地。

### 3. 文件上传（push）
  由于本项目参与者不涉及共同开发，统一使用master分支上传文件，需要确认Github网页和Desktop软件对应位置选择的是master分支；
  协作者无论在本地还是网站，应只修改自己文件夹中的内容，避免更改他人代码或造成版本冲突。
  
  <img width="734" alt="image" src="https://user-images.githubusercontent.com/102509476/210517762-0b309d20-5a7a-4b97-ac34-b94f58692b27.png">
  <img width="563" alt="image" src="https://user-images.githubusercontent.com/102509476/210515407-da8b9eb8-45b6-42ea-a4d3-8126a585debd.png">

#### 3.1 本地修改
  在本地创建或修改文件后，Github Desktop 中将自动出现修改内容，可在页面左下角填写本次修改的主要内容和描述，点击 Commit to master；
  
  <img width="189" alt="image" src="https://user-images.githubusercontent.com/102509476/210513423-31199c1f-cb05-42dd-b6a2-71a112fa08e0.png">  
  <img width="534" alt="image" src="https://user-images.githubusercontent.com/102509476/210517058-da73adc7-443a-4f42-ad05-4b1b3012a779.png">
  页面上方 Fetch origin 按钮变为 Push origin 并伴有向上箭头，主页面出现蓝色对话框提示将本地更新内容上推至网页。
  
  <img width="536" alt="image" src="https://user-images.githubusercontent.com/102509476/210518189-733a8e12-bee2-4ef7-8e68-c6dfacf60eaf.png">  
  即可将修改更新至网站仓库，同时留下修改记录。

  
#### 3.2 网页端修改
  可以使用仓库主页的 Add file 按钮在网页端新建文件或将本地文件拖拽上传；
  在网页端直接修改文件。

### 4. 文件下载（pull）
  在 Github Desktop 页面点击 Fetch origin 按钮以刷新查看仓库内容有无更新； 
  <img width="534" alt="image" src="https://user-images.githubusercontent.com/102509476/210517058-da73adc7-443a-4f42-ad05-4b1b3012a779.png">

  在线上仓库内容发生变动的情况下，Fetch origin 按钮变为 Pull origin 并伴有向下箭头，主页面也出现蓝色对话框，提示将更新内容下拉至本地。 

  <img width="534" alt="image" src="https://user-images.githubusercontent.com/102509476/210517128-581b7e83-045b-4666-8a49-9a4ed7152682.png">  
  点击 Pull origin 即可完成下载。

