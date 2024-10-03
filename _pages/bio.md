---
layout: page
title: Keyu Jin
permalink: /bio/
---

<!-- 开始文本和图片布局的容器 -->
<div class="content-container" style="display: flex; align-items: flex-start; justify-content: flex-start; width: 70vw; margin: 0 auto; flex-direction: row;">

  <!-- 左侧：文本内容 -->
  <div class="text-content" style="flex: 1; padding-right: 30px;">
    <p style="font-size: 16px; line-height: 1.6;">
      Dr. Keyu Jin was a tenured professor of Economics at the LSE between 2009-2024. She is from Beijing, China and holds a B.A., M.A., and Ph.D. from <a href="https://www.harvard.edu/" style="color:red;">Harvard University</a>. Her research focuses on international macroeconomics and trade, and the Chinese economy, exploring questions such as technological competition between China and the rest of the world, what governments' optimal policies should be in the context of China's rapid growth and technological advancement, capital flows between China and the rest of the world, and the role of demographics. Her work also includes the international transmission of U.S. monetary and fiscal policy, and how it has changed over time. She is the author of <a href="https://www.keyujin.co/the-new-china-playbook/" style="color:red; font-style: italic;">The New China Playbook: Beyond Socialism and Capitalism</a>, which was a Financial Times Must Read of 2023. Her op-eds have appeared in the New York Times, the Financial Times, the Wall Street Journal, Time Magazine, and many more.
    </p>
  </div>

  <!-- 右侧：图片 -->
  <div class="image-content" style="flex: 1; padding-left: 30px;">
    <img src="{{ site.baseurl }}/images/12.jpeg" alt="Keyu Jin" style="max-width: 100%; height: auto;">
  </div>

</div>

<!-- 响应式样式，确保在小屏幕上图片在上，文字在下 -->
<style>
  /* 默认（PC端）布局：文字在左，图片在右 */
  .content-container {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
  }

  /* 在小屏幕（手机端）上，将布局改为图片在上，文字在下 */
  @media (max-width: 768px) {
    .content-container {
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    /* 调整文字和图片间距 */
    .text-content {
      padding-right: 0;
      padding-bottom: 20px; /* 让图片和文字间距更大 */
    }

    .image-content {
      padding-left: 0;
    }
  }
</style>
<!-- 结束文本和图片布局的容器 -->
