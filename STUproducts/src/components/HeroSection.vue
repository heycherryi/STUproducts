<template>
    <div class="hero">
      <div class="content">
        <h1 class="title">Speech and Text Understanding Research Team (STU)</h1>
        <p class="description">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Facilisis penatibus sapien fusce vel curae elementum. Gravida quisque feugiat per bibendum integer vitae ut. Iaculis platea efficitur posuere ultricies potenti interdum.
        </p>
      </div>
      <div class="big-text-container">
        <h1 class="big-text">STU</h1>
      </div>
    </div>
    
</template>
  
<style scoped>
.hero {
    width: 100vw;  /* ✅ กว้างเต็มจอ */
    height: 60vh; /* ✅ สูงเต็มจอ */
    background: linear-gradient(45deg, #12002b, #3b1665);
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: absolute; /* ✅ ชิดด้านบน */
    top: 0;
    left: 0;
    box-sizing: border-box;
    padding: 0 5vw;
}

.content {
    flex: 1; /* ✅ ให้กินพื้นที่ครึ่งหนึ่งของหน้าจอ */
    max-width: 100%;
    text-align: left; /* ✅ จัดข้อความชิดซ้าย */
}

.title {
    font-size: 28px;
    font-weight: bold;
    color: #34d399;
}

.description {
    font-size: 16px;
    line-height: 1.5;
    max-width: 500px;
    opacity: 0.8;
}

.big-text-container {
    flex: 1; /* ✅ ให้กินพื้นที่ครึ่งหนึ่งของหน้าจอ */
    display: flex;
    justify-content: center; /* ✅ จัดให้อยู่กลางแนวนอน */
    align-items: center; /* ✅ จัดให้อยู่กลางแนวตั้ง */
}

.big-text {
    font-size: 140px; 
    font-weight: bold;
    opacity: 0.2;
}
</style>
