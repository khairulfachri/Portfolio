<template>
  <div class="card">
    <img class="avatar" src="@/assets/profile.jpg" alt="Profile" />
    <h1>Khairul Fachri</h1>
    <p class="title">UI/UX Designer</p>
    <p>Email: khairulfachri@student.uir.ac.id</p>
    <p>Location: Pekanbaru</p>
    <p>Phone: +62 857-6309-9733</p>

    <div class="section">
      <h3>Skills & Tools</h3>
      <div class="tags">
        <span>Photoshop</span>
        <span>Illustrator</span>
        <span>Figma</span>
        <span>XD</span>
      </div>
    </div>

    <div class="section">
      <h3>Languages</h3>
      <div class="tags">
        <span>HTML</span>
        <span>CSS</span>
        <span>JavaScript</span>
        <span>Python</span>
        <span>C#</span>
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
  width: 400px;
  margin: auto;
  padding: 2rem;
  background: #1e293b;
  border-radius: 10px;
  text-align: center;
  position: relative;
  top: 50%;
  transform: translateY(-50%);
}

.avatar {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1rem;
}

.title {
  color: #38bdf8;
  margin: 0.5rem 0;
}

.section {
  margin-top: 1.5rem;
}

.tags span {
  display: inline-block;
  margin: 0.3rem;
  padding: 0.4rem 0.8rem;
  background-color: #334155;
  border-radius: 20px;
  font-size: 0.85rem;
}
</style>