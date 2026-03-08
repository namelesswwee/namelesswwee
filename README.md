
### ✅ 正确写法（直接写 HTML，不要包裹 ```html）：

```html
<div style="position: relative; width: 100%; height: 450px; border-radius: 10px; overflow: hidden; background-color: #333;">
  
  <img src="https://raw.githubusercontent.com/namelesswwee/namelesswwee/main/1123.jpg" 
       alt="Background" 
       style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; z-index: 0; display: block;">

  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.5); z-index: 1;"></div>

  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; z-index: 2; display: flex; flex-direction: column; justify-content: center; align-items: center; color: white; padding: 20px; box-sizing: border-box; text-align: center;">
    
    <h1 style="margin: 0 0 10px 0; font-size: 2.2rem; text-shadow: 2px 2px 4px rgba(0,0,0,0.8);">Hi 👋, I'm 你的名字</h1>
    <h3 style="margin: 0 0 20px 0; font-weight: 400; opacity: 0.9;">一个热爱编程的开发者</h3>
    
    <p style="margin: 0 0 15px 0; line-height: 1.5; max-width: 80%;">
      这里写你的简介<br/>
      这里写你的技能<br/>
      这里写你的目标
    </p>

    <p style="margin: 0; font-size: 0.95rem; opacity: 0.8;">
      💻 正在学习：Java / Python / 前端<br/>
      📫 邮箱：your@email.com
    </p>
    
  </div>
</div>
