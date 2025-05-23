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
    background-color: var(--color-bg-secondary);
    border: 1px solid var(--color-border-primary);
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
    background-color: var(--color-bg-hover);
  }

  .brand-button img {
    width: 50px;
    height: 50px;
    margin-right: 15px;
    border-radius: 50%;
    border: 1px solid var(--color-border-primary);
    transition: transform 0.3s ease;
  }

  .brand-button:hover img {
    transform: rotate(5deg) scale(1.1);
  }

  .brand-button span {
    font-size: 18px;
    font-weight: bold;
    color: var(--color-text-primary);
    transition: color 0.3s ease;
  }

  .brand-button:hover span {
    color: var(--color-text-hover);
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

<div class="brand-button" onclick="window.location.href='https://www.ui.com';">
  <img src="{{ '/assets/img/brand-icons/ubiquiti-logo.png' | relative_url }}" alt="Ubiquiti Logo">
  <span>Ubiquiti Inc.</span>
</div>

<div class="brand-button" onclick="window.location.href='https://www.sysracks.com';">
  <img src="{{ '/assets/img/brand-icons/sysracks-logo.png' | relative_url }}" alt="Sysracks Logo">
  <span>Sysracks Inc.</span>
</div>

<div class="brand-button" onclick="window.location.href='https://www.cisco.com';">
  <img src="{{ '/assets/img/brand-icons/cisco-logo.png' | relative_url }}" alt="Cisco Logo">
  <span>Cisco Systems</span>
</div>

<div class="brand-button" onclick="window.location.href='https://www.netgear.com';">
  <img src="{{ '/assets/img/brand-icons/netgear-logo.png' | relative_url }}" alt="Netgear Logo">
  <span>Netgear Inc.</span>
</div>

<div class="brand-button" onclick="window.location.href='https://www.tp-link.com';">
  <img src="{{ '/assets/img/brand-icons/tp-link-logo.png' | relative_url }}" alt="TP-Link Logo">
  <span>TP-Link Technologies</span>
</div>

<div class="brand-button" onclick="window.location.href='https://mikrotik.com';">
  <img src="{{ '/assets/img/brand-icons/mikrotik-logo.png' | relative_url }}" alt="MikroTik Logo">
  <span>MikroTik</span>
</div>

<div class="brand-button" onclick="window.location.href='https://www.ifixit.com';">
  <img src="{{ '/assets/img/brand-icons/ifixit-logo.png' | relative_url }}" alt="Ifixit Logo">
  <span>Ifixit</span>
</div>

<div class="brand-button" onclick="window.location.href='https://frame.work';">
  <img src="{{ '/assets/img/brand-icons/framework-logo.png' | relative_url }}" alt="Framework Logo">
  <span>Framework</span>
</div>
