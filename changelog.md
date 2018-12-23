### 1. 安装`wepy-plugin-imagemin`和`wepy-plugin-uglifyjs`:
  1. 使用wepy-cli创建的application并没有安装这俩包，导致配置文件里的对图片和js的处理无效，所以必须手动安装
      ```
        npm i wepy-plugin-imagemin wepy-plugin-uglifyjs -D
      ```