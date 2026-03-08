<div style="position: relative; width: 100%; height: 450px; border-radius: 10px; overflow: hidden;">
  
  <!-- 1. 底层图片：使用 img 标签，设置为绝对定位填满容器 -->
  <img src="https://raw.githubusercontent.com/namelesswwee/namelesswwee/main/1123.jpg" 
       style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover;" 
       alt="Profile Background">

  <!-- 2. 遮罩层：半透明黑色，让文字更清晰 -->
  <div style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; background: rgba(0, 0, 0, 0.4);"></div>

  <!-- 3. 内容层：文字内容，浮在最上层 -->
  <div style="position: relative; z-index: 1; padding: 40px; color: white; text-align: center;">
    <h1>Hi 👋, I'm 你的名字</h1>
    <h3>一个热爱编程的开发者</h3>
    
    <p>
      这里写你的简介<br/>
      这里写你的技能<br/>
      这里写你的目标
    </p>

    <p>
      💻 正在学习：Java / Python / 前端<br/>
      📫 邮箱：your@email.com
    </p>
  </div>

</div>
