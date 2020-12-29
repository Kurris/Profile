# WindowsTerminal

- **安装插件** 
    ```shell
    Install-Module posh-git -Scope CurrentUser
    Install-Module oh-my-posh -Scope CurrentUser
    
    --管理员
    Install-Module posh-git
    Install-Module oh-my-posh
    ```
    
- **使用插件**
	```shell
	Import-Module posh-git
	Import-Module oh-my-posh
	Set-Theme PowerLine
	```
	



- **个人配置**
  ```json
    "defaults":
          {
  	"tabTitle" : "Ligy",
  	"useAcrylic" : true,
  	"historySize" : 5000,
  	"backgroundImage":"https://github.com/Kurris/Profile/blob/main/image/star.jfif",
  	"backgroundImageOpacity": 0.6,
  	"acrylicOpacity" : 0.5,
  	"fontFace" : "JetBrains Mono",
  	"cursorShape" : "vintage",//光标类型  可选 bar empytBox filledBox vintage
  	"cursorColor" : "#3CB371",
  	"fontFace" : "jetbrains Mono",
  	"fontSize":10,
          },
  ```

  