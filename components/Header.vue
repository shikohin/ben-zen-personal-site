<template>
    <header class="header">
      <div class="container">
        <NuxtLink to="/" class="logo">Your Logo</NuxtLink>
        <nav class="nav">
          <ul>
            <li>
                <NuxtLink to="/about">About</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/resume">Resume</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/photography">Photography</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/blog">Blog</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/contact">Contact</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/art">Art</NuxtLink>
            </li>
          </ul>
        </nav>
      </div>
    </header>
  </template>
  
  <style scoped>
  .header {
    background-color: #f0f0f0; /* Example background color */
    padding: 1rem 0;
  }
  
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 960px; /* Or your desired width */
    margin: 0 auto;
  }
  
  .logo {
    font-weight: bold;
  }
  
  .nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
  }
  
  .nav li {
    margin-left: 2rem;
  }
  
  .nav a {
    text-decoration: none;
    color: #333;
  }
  </style>
  