<template>
    <nav class="navbar">
      <div class="logo">STU</div>
      <div class="nav-links">
        <button class="nav-button">Product</button>
        <button class="nav-button">Contact</button>
      </div>
    </nav>
  </template>
  
  <style>
  /* Navbar Styles */
  .navbar {
    width: 100%;
    background-color: #0a0a2a;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 100;
  }
  
  .logo {
    font-size: 24px;
    font-weight: bold;
  }
  
  .nav-links {
    display: flex;
    gap: 10px;
  }
  
  .nav-button {
    background: none;
    border: 2px solid white;
    color: white;
    padding: 8px 16px;
    border-radius: 5px;
    cursor: pointer;
    transition: 0.3s;
  }
  
  .nav-button:hover {
    background-color: white;
    color: #0a0a2a;
  }
  </style>
  