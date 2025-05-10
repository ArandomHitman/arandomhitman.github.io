---
layout: page
icon: fas fa-thumbs-up
title: Recommended Brands
order: 4
---

<style>
  .brand-button {
    display: flex;
    align-items: center;
    background-color: #ffffff;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 10px 15px;
    margin: 10px 0;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s, box-shadow 0.2s, background-color 0.3s;
    animation: fadeIn 0.5s ease-in-out;
    cursor: pointer;
  }

  .brand-button:hover {
    transform: translateY(-3px) scale(1.02);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.25);
    background-color: #f0f0f0;
  }

  .brand-button img {
    width: 50px;
    height: 50px;
    margin-right: 15px;
    border-radius: 50%;
    border: 1px solid #ddd;
    transition: transform 0.3s ease;
  }

  .brand-button:hover img {
    transform: rotate(5deg) scale(1.1);
  }

  .brand-button span {
    font-size: 18px;
    font-weight: bold;
    color: #555;
    transition: color 0.3s ease;
  }

  .brand-button:hover span {
    color: #333;
  }

  .brand-link {
    display: none;
  }

  @keyframes fadeIn {
    from {
      opacity: 0;
      transform: translateY(10px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  [data-theme="dark"] .brand-button {
    background-color: #333;
    border: 1px solid #555;
    box-shadow: 0 2px 4px rgba(255, 255, 255, 0.1);
  }

  [data-theme="dark"] .brand-button:hover {
    background-color: #444;
    box-shadow: 0 6px 12px rgba(255, 255, 255, 0.25);
  }

  [data-theme="dark"] .brand-button img {
    border: 1px solid #555;
  }

  [data-theme="dark"] .brand-button span {
    color: #f9f9f9;
  }

  #theme-toggle {
    margin: 10px 0;
    padding: 10px 15px;
    background-color: #ddd;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    font-weight: bold;
    transition: background-color 0.3s ease, color 0.3s ease;
  }

  [data-theme="dark"] #theme-toggle {
    background-color: #555;
    color: #f9f9f9;
  }
</style>

<script>
  // Ensure the theme is applied based on the user's preference or system setting
  const userPrefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches;
  const savedTheme = localStorage.getItem('theme');
  const theme = savedTheme || (userPrefersDark ? 'dark' : 'light');
  document.documentElement.setAttribute('data-theme', theme);

  // Update the toggle button text based on the current theme
  function updateToggleButtonText() {
    const currentTheme = document.documentElement.getAttribute('data-theme');
    const toggleButton = document.getElementById('theme-toggle');
    toggleButton.textContent = currentTheme === 'dark' ? 'Switch to Light Mode' : 'Switch to Dark Mode';
  }

  // Function to toggle theme
  function toggleTheme() {
    const currentTheme = document.documentElement.getAttribute('data-theme');
    const newTheme = currentTheme === 'dark' ? 'light' : 'dark';
    document.documentElement.setAttribute('data-theme', newTheme);
    localStorage.setItem('theme', newTheme);
    updateToggleButtonText();
  }

  // Initialize the toggle button text on page load
  document.addEventListener('DOMContentLoaded', updateToggleButtonText);
</script>

<button id="theme-toggle" onclick="toggleTheme()">Switch Theme</button>

<div class="brand-button" onclick="window.location.href='#';">
  <img src="/assets/img/brand-icons/ubiquiti-logo.png" alt="Ubiquiti Logo">
  <span>Ubiquiti Inc.</span>
  <a href="https://www.ui.com/" class="brand-link">Visit Website</a>
</div>

<div class="brand-button" onclick="window.location.href='#';">
  <img src="/assets/img/brand-icons/sysracks-logo.png" alt="Sysracks Logo">
  <span>Sysracks Inc.</span>
  <a href="https://sysracks.com/" class="brand-link">Visit Website</a>
</div>

<div class="brand-button" onclick="window.location.href='#';">
  <img src="/assets/img/brand-icons/cisco-logo.png" alt="Cisco Logo">
  <span>Cisco Systems</span>
  <a href="https://www.cisco.com/" class="brand-link">Visit Website</a>
</div>

<div class="brand-button" onclick="window.location.href='#';">
  <img src="/assets/img/brand-icons/netgear-logo.png" alt="Netgear Logo">
  <span>Netgear Inc.</span>
  <a href="https://www.netgear.com/" class="brand-link">Visit Website</a>
</div>

<div class="brand-button" onclick="window.location.href='#';">
  <img src="/assets/img/brand-icons/mikrotik-logo.png" alt="MikroTik Logo">
  <span>MikroTik</span>
  <a href="https://mikrotik.com/" class="brand-link">Visit Website</a>
</div>

<div class="brand-button" onclick="window.location.href='https://www.ifixit.com/';">
  <img src="/assets/img/brand-icons/ifixit-logo.png" alt="Ifixit Logo">
  <span>Ifixit</span>
  <a href="https://www.ifixit.com/" class="brand-link">Visit Website</a>
</div>

<div class="brand-button" onclick="window.location.href='https://frame.work/';">
  <img src="/assets/img/brand-icons/framework-logo.png" alt="Framework Logo">
  <span>Framework</span>
  <a href="https://frame.work/" class="brand-link">Visit Website</a>
</div>
