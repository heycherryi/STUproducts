<template>
  <div class="product-section">
    <h2 class="section-title">Product</h2>
    <div class="product-container">
      <div class="product-card" v-for="product in products" :key="product.id">
        <img :src="product.image" :alt="product.name" class="product-image" />
        <h3 class="product-name">{{ product.name }}</h3>
        <p class="product-description">{{ product.description }}</p>
      </div>
    </div>
    <button class="all-product-btn">All Product</button>
  </div>
</template>

<script setup>
const products = [
  {
    id: 1,
    name: "Patthumma LLM",
    description: "Lorem ipsum dolor amet, consectetur adipiscing elit.",
    image: "/images/patthumma.png",
  },
  {
    id: 2,
    name: "Abdul GI",
    description: "Lorem ipsum dolor amet, consectetur adipiscing elit.",
    image: "/images/abdul.png",
  },
  {
    id: 3,
    name: "Sontana",
    description: "Lorem ipsum dolor amet, consectetur adipiscing elit.",
    image: "/images/sontana.png",
  },
];
</script>

<style scoped>
.product-section {
  background: linear-gradient(to bottom, #f8f8ff, #e6e6fa);
  padding: 80px 5vw;
  text-align: center;
  margin-top: -5px;
}

.section-title {
  font-size: 28px;
  font-weight: bold;
  color: #37517e;
  margin-bottom: 30px;
}

.product-container {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.product-card {
  background: white;
  border-radius: 10px;
  padding: 20px;
  width: 300px;
  text-align: center;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

.product-image {
  width: 100px;
  height: auto;
  margin-bottom: 10px;
}

.product-name {
  font-size: 18px;
  font-weight: bold;
}

.product-description {
  font-size: 14px;
  color: gray;
}

.all-product-btn {
  margin-top: 20px;
  padding: 10px 20px;
  border: 2px solid #6c63ff;
  background: white;
  color: #6c63ff;
  border-radius: 20px;
  font-size: 16px;
  cursor: pointer;
  transition: 0.3s;
}

.all-product-btn:hover {
  background: #6c63ff;
  color: white;
}
</style>
