<template>
  <section class="home-section" id="about">
    <div class="box-bg">
      <div class="box-bg-wrapper">
        <div class="box-2">
          <div class="box-3"></div>
        </div>
      </div>
    </div>
    <div class="container text-center">
      <span class="subhead">เรื่องราวแห่ง ITCAMP ครั้งที่ 15</span>
      <h1>ปฐมบทแห่งมนตรา</h1>
      <div class="about-wrapper">
        <p>
          คุณพร้อมแล้วรึยังกับประตูใบใหม่ที่กำลังจะเปิดขึ้น เตรียมพบโลกเวทมนตร์
ที่ถูกซ่อนเร้นไว้จากเหล่ามักเกิ้ล ถึงเวลาแล้วที่จะเปิดประตูต้อนรับเหล่าพ่อมดและแม่มดรุ่นเยาว์ ที่มีความสนใจใคร่รู้ ศาสตร์เวทมนตร์แห่งไอที
อีกครั้ง โดยครั้งนี้พี่ ๆ จะพาพวกน้อง ๆ ที่ชื่นชอบไอทีมาเรียนรู้จักการประยุกต์ใช้เทคโนโลยีให้เป็นดั่งเวทมนตร์ที่แอบซ่อนอยู่รอบ ๆ ตัวเรา ต้องการ
หาคำตอบของความลับที่ถูกซ่อนเร้นในโลกใบนี้
โรงเรียนเวทมนตร์แห่งนี้ คือที่ที่เหมาะสมกับคุณ
ภาคการศึกษาใหม่ได้ถูกเปิดขึ้นแล้ว พร้อมกับศาสตร์ทั้ง 5 ที่น่าสนใจและไม่เคยเกิดขึ้นที่ไหนมาก่อน แต่กำลังจะเกิดขึ้นแล้วที่นี่
ITCAMP 15 : Magic Academy
เตรียมตัวให้พร้อม ถ้าหากพร้อมแล้วสมัครเลย
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
#about {
  min-height: calc(100vh - 100px);
  background-image: linear-gradient(to bottom, #17013c, #22002b);
  color: #ffffff;
  padding-bottom: 150px;
  padding-top: 50px;
}

#about .subhead {
  color: #ffffff;
}

#about .container {
  position: relative;
  padding-top: 150px;
  padding-bottom: 4vh;
}

#about .about-wrapper {
  width: 55%;
  margin: auto;
  font-family: "Sarabun", sans-serif;
  font-weight: 100;
  line-height: 44px;
}

.box-bg {
  width: 100%;
  height: 100%;
  position: absolute;
  overflow: hidden;
  padding: 30px 0px;
}

.box-bg-wrapper {
  margin: auto;
  margin-top: 100px;
  width: 500px;
  height: 500px;
  border: 0.5px solid #555;
  padding: 2em;
  transform: rotate(45deg);
}

.about-wrapper p{
  white-space: pre-wrap;
}

@media (max-width: 768px) {
  #about .about-wrapper {
    width: auto;
    padding-left: 20px;
    padding-right: 20px;
  }

  .box-bg-wrapper {
    width: 100vh;
    height: 100vh;
  }
}

.box-2 {
  border: 0.5px solid #444;
  width: 100%;
  height: 100%;
}

.box-3 {
  margin: 2em;
  width: calc(100% - 4em);
  height: calc(100% - 4em);
  border: 0.5px solid #222;
}
</style>
