---
layout: page
title: Featured Artists
subtitle:
lang: en
ref: ref2
---

<style>
.card {
  width: 350px;
  height: 525px;
  overflow: hidden;
  position: relative;
}
.card .main-content {
  width: 100%;
  height: 100%;
}
.card .main-content img {
  width: 100%;
  height: 100%;
}
.card .overlay-content {
  width: 100%;
  height: 100%;
  background-color: #ffeac9;
  color: #080808;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  position: absolute;
  z-index: 1;
  transition: 0.6s;
  top: 0%;
  left: 100%;
  opacity: 0.8;
}
.card:hover .overlay-content {
  /* left: 0; */
  transform: translateX(-100%);
}
.card .overlay-content p {
  text-align: center;
  font-size: 1.4rem;
  margin: 2rem;
  letter-spacing: 1px;
  line-height: 1.75rem;
}
.card .overlay-content p span {
  display: block;
  letter-spacing: normal;
  font-size: 1rem;
  font-style: italic;
  margin-top: 1.25rem;
}
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-column-gap: 0px;
  grid-row-gap: 0px;
}
</style>

<div class="grid-container">
  <div class="grid-item">
  <div class="card">
      <div class="main-content">
        <img src="https://images.unsplash.com/photo-1531259683007-016a7b628fc3?w=500&q=80&fit=max" alt="Batman">
      </div>
      <div class="overlay-content">
        <p>
          "Sometimes the truth isn't good enough, sometimes people deserve more. Sometimes people deserve to have their faith rewarded..."
          <span>- The Dark Knight -</span>
        </p>
      </div>
    </div>
  </div>
  <div class="grid-item">
  <div class="card">
      <div class="main-content">
        <img src="https://images.unsplash.com/photo-1531259683007-016a7b628fc3?w=500&q=80&fit=max" alt="Batman">
      </div>
      <div class="overlay-content">
        <p>
          "Sometimes the truth isn't good enough, sometimes people deserve more. Sometimes people deserve to have their faith rewarded..."
          <span>- The Dark Knight -</span>
        </p>
      </div>
    </div>
  </div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
  <div class="grid-item">5</div>
  <div class="grid-item">6</div>
  <div class="grid-item">7</div>
  <div class="grid-item">8</div>
  <div class="grid-item">9</div>
</div>
