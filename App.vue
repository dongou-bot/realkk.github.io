<template>
  <div>
    <header>
      <div class="profile-img-container">
        <img src="https://media.discordapp.net/attachments/1030456379850371082/1224645693847896094/3472486386692322141.png?ex=661e3f2e&is=660bca2e&hm=38eb9aa324b72e997eec2c7feb6f255be4e84af864d9218d05ae6aef9b817042&=&format=webp&quality=lossless&width=184&height=252" alt="나" class="profile-img">
      </div>
      <h1>My Blog</h1>
      <nav>
        <ul>
          <li><a href="#main">Main</a></li>
          <li><a href="#development">Development</a></li>
          <li><a href="#hobby">Hobby</a></li>
          <li><a href="#about">About</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <!-- Main content -->
      <h1>My Blog</h1>
      
    </main>
  </div>
</template>

<style>
body {
  margin: 0; /* 브라우저 창 여백 제거 */
  padding: 0;
}

main {
  background: #222;
  color: #ddd;
  padding: 0 auto;
  margin: 0 auto;
  margin-left: 25%;
  height: 100vh;
  border: 20px solid #222;
}

main h1 {
  text-align: center;
}

header {
  float: left;
  text-align: center;
  line-height: 10px;
  background: #444;
  height: 100vh;
  width: 25%;
  position: fixed;
  top: 0;
  left: 0;
}

.profile-img-container {
  width: 70%;
  margin: 0 auto;
  overflow: hidden;
  border-radius: 50%;
  transition: transform 0.3s;
}

.profile-img {
  width: 100%;
  clip-path: circle(50% at 50% 50%); /* 원형으로 잘라내기 */
  transition: transform 0.3s;
}

.profile-img-container:hover .profile-img {
  transform: scale(1.1);
}

header h1 {
  text-align: center;
  color: #aaa;
  margin-top: 30px;
}

nav {
  text-align: left;
  line-height: 20px;
  color: #999;
}

nav a {
  color: #999;
}

nav a:hover {
  color: #aaa;
}
</style>


<script>

export default {
  name: 'App',
  components: {
  }
}
</script>