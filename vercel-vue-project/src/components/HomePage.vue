<template>
  <div class="home-page">
    <header class="header">
      <h1>欢迎来到我的网站</h1>
      <nav>
        <a href="#">首页</a>
        <a href="#">关于我们</a>
        <a href="#">服务</a>
        <a href="#">联系我们</a>
      </nav>
    </header>

    <main class="main-content">
      <section class="hero">
        <h2>探索无限可能</h2>
        <p>在这里，我们创造未来，连接世界。</p>
        <button>了解更多</button>
      </section>

      <section class="features">
        <div class="feature-item">
          <h3>创新技术</h3>
          <p>采用最新的技术栈，提供极致的用户体验。</p>
        </div>
        <div class="feature-item">
          <h3>专业团队</h3>
          <p>拥有经验丰富的团队，致力于提供高质量的服务。</p>
        </div>
        <div class="feature-item">
          <h3>客户至上</h3>
          <p>始终以客户的需求为核心，提供个性化的解决方案。</p>
        </div>
      </section>
    </main>

    <footer class="footer">
      <p>&copy; 2024 我的公司. 保留所有权利.</p>
    </footer>
  </div>
</template>

<script>
/**
 * @name HomePage
 * @description 项目的首页组件，展示网站的主要内容和导航。
 */
export default {
  name: 'HomePage',
};
</script>

<style scoped>
.home-page {
  font-family: 'Arial', sans-serif;
  color: #333;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.header {
  background-color: #4A90E2;
  color: white;
  padding: 20px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.header h1 {
  margin: 0;
  font-size: 1.8em;
}

.header nav a {
  color: white;
  margin-left: 20px;
  text-decoration: none;
  font-size: 1em;
}

.header nav a:hover {
  text-decoration: underline;
}

.main-content {
  flex-grow: 1;
  padding: 40px;
  background-color: #f4f7f6;
}

.hero {
  text-align: center;
  padding: 60px 20px;
  background-color: #ffffff;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  margin-bottom: 40px;
}

.hero h2 {
  font-size: 2.5em;
  color: #4A90E2;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2em;
  margin-bottom: 20px;
  color: #555;
}

.hero button {
  background-color: #50E3C2;
  color: white;
  border: none;
  padding: 15px 30px;
  font-size: 1em;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.hero button:hover {
  background-color: #45c4a8;
}

.features {
  display: flex;
  justify-content: space-around;
  gap: 20px;
}

.feature-item {
  background-color: #ffffff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  text-align: center;
  flex-basis: 30%;
}

.feature-item h3 {
  font-size: 1.5em;
  color: #4A90E2;
  margin-bottom: 10px;
}

.feature-item p {
  font-size: 1em;
  color: #666;
}

.footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
  font-size: 0.9em;
}
</style>