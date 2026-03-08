<div style="position: relative; width: 100%; height: 400px; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.2);">
  
  <!-- 1. 模拟背景的图片 (最底层) -->
  <!-- 注意：src 换成你自己的图片链接 -->
  <img src="https://raw.githubusercontent.com/namelesswwee/namelesswwee/main/1123.jpg" 
       alt="Background" 
       style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; z-index: 0;">

  <!-- 2. 半透明遮罩层 (中间层，让文字更清晰) -->
  <!-- 可以调整 rgba 中的 0.5 来改变黑暗程度 (0.0 - 1.0) -->
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.5); z-index: 1;"></div>

  <!-- 3. 文字内容 (最上层) -->
  <div style="position: relative; z-index: 2; height: 100%; display: flex; flex-direction: column; justify-content: center; align-items: center; color: white; padding: 20px; text-align: center;">
    
    <h1 style="margin: 0; font-size: 2.5rem; text-shadow: 2px 2px 4px rgba(0,0,0,0.5);">Hi 👋, I'm 你的名字</h1>
    <h3 style="margin: 10px 0; font-weight: 300; opacity: 0.9;">一个热爱编程的开发者</h3>
    
    <p style="max-width: 600px; line-height: 1.6; margin-top: 20px;">
      这里写你的简介，例如：全栈工程师 | 开源爱好者 | 技术博主<br/>
      专注于构建高质量的用户体验和高效的后台系统。
    </p>

    <div style="margin-top: 25px; display: flex; gap: 15px; flex-wrap: wrap; justify-content: center;">
      <span style="background: rgba(255,255,255,0.2); padding: 5px 15px; border-radius: 20px; backdrop-filter: blur(5px);">💻 Java</span>
      <span style="background: rgba(255,255,255,0.2); padding: 5px 15px; border-radius: 20px; backdrop-filter: blur(5px);">🐍 Python</span>
      <span style="background: rgba(255,255,255,0.2); padding: 5px 15px; border-radius: 20px; backdrop-filter: blur(5px);">⚛️ React</span>
    </div>

    <p style="margin-top: 20px; font-size: 0.9rem; opacity: 0.8;">
      📫 联系我：your@email.com
    </p>

  </div>
</div>
