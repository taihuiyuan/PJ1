PJ1说明
==========

姓名：邰荟媛

学号：19302010077

-------------------

## 作业提交
### Github地址
https://github.com/taihuiyuan/PJ1

### Github Pages 地址
https://taihuiyuan.github.io/PJ1/

-------------------

## 项目完成情况
### 首页
#### `导航栏`
导航栏条目显示正确  
点击导航栏条目跳转  
鼠标移动到条目上有样式变化  
个人中心实现下拉菜单，可点击可跳转  
鼠标移动到下拉菜单的条目上显示高亮，条目内容前有合适的图标  
在不同的页面中导航栏显示相同，并且当前页面条目高亮
#### `图片展示`
图片布局合理，每张图片都带有图片标题和图片描述的缩略版  
点击图片后，跳转到相应图片的详情页
#### `页脚`
页脚展示版权信息以及喜好内容
#### `辅助图标`
按钮随着页面的滑动始终固定在页面右下角  
回到页面顶部按钮功能完成，图片刷新按钮有响应

### 浏览页
#### `搜索栏`
能正确输入文字，点击搜索按钮有响应
#### `快速浏览栏`
显示热门国家、热门城市、热门内容，点击条目有响应
#### `筛选栏`
点击筛选栏，出现下拉菜单，可以选择筛选条件  
国家与城市筛选实现二级联动
#### `图片展示`
图片布局合理，大小一致  
点击图片后，跳转到图片详情页

### 搜索页
#### `筛选栏`
两个搜索按钮可以选择其中一个进行搜索  
能正确输入文字，点击搜索按钮有响应
#### `图片展示`
每一项结果的左边是缩略图，右边是标题和描述，标题与描述有区分。  
搜索结果排布整齐，正确  
描述文字中，多行文字溢出显示省略号  
点击图片后，跳转到图片详情页

### 上传页面
#### `上传部分`
可以从本地选择图片进行上传  
未上传图片时显示提示文字，上传完成后在页面内显示图片
#### `输入部分`
用户可以输入图片标题、图片描述、拍摄国家、拍摄城市  
用户点击下方的提交按钮有响应，提交成功后跳转到我的照片界面

### 我的照片
#### `图片展示`
图片展示部分与搜索页的四条要求相同  
修改按钮和删除按钮布局合理并且有响应

### 我的收藏
#### `图片展示`
图片展示部分与搜索页的四条要求相同  
删除按钮布局合理并且有响应

### 图片详情页
#### `图片展示`
展示图片、图片标题、拍摄者、图片描述、主题、拍摄国家、拍摄城市  
布局合理，展示美观  
展示该照片已被收藏的数量，并有一个收藏按钮，点击有响应

### 登录&注册
#### `表单`
注册表单中可以填写用户名、邮箱、密码、确认密码   
登录表单中可以填写用户名、密码  
密码和确认密码部分不得显示明文，点击登录 / 注册能够跳转到主页 / 登陆界面 
登陆界面有引导注册提示信息并可以正常跳转

-------------------

## Bonus
### 更复杂的图片处理
#### 完成情况
整个⽹站中未使⽤square⽂件夹中的图⽚，只使⽤normal⽂件夹中的⾃由版式图⽚进⾏排版，在各页面展示成固定板式的图片
#### 解决办法
在包裹img的div的css中加上overflow:hidden;再调整img的位置、大小，进行适当的剪裁。

### 响应式布局
#### 完成情况
在不过分改变浏览器宽度的情况下，不会出现太⼤的排版和设计上的错乱。
适合大部分移动设备
#### 解决办法
在网页代码的头部，加入一行viewport元标签  
用相对宽度，字体大小用相对大小  
流动布局，各个区块的位置是浮动的  
图片自适应，使用相对宽度和相对高度
@madia媒体查询
