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
    transform: translateY(-3px);
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    background-color: #f0f0f0;
  }

  .brand-button img {
    width: 50px;
    height: 50px;
    margin-right: 15px;
    border-radius: 50%;
    border: 1px solid #ddd;
  }

  .brand-button span {
    font-size: 18px;
    font-weight: bold;
    color: #555;
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
</style>

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
