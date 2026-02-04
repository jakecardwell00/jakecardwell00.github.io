---
title: Contact Information
weight: 40
---

<style>
  .resume-section {
    position: relative;
    width: 100%;
    height: 400px; /* Adjust height as needed */
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .background-gif {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    z-index: 1;
  }

  .white-box {
    position: relative;
    z-index: 2;
    background-image: url('/images/section-white.png');
    background-size: cover;
    background-position: center;
    width: 300px; /* Adjust size */
    height: 200px; /* Adjust size */
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 8px; /* Optional rounded corners */
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2); /* Optional shadow */
  }

  .resume-text {
    color: black;
    font-size: 2.5rem;
    font-weight: bold;
    font-family: sans-serif;
    text-align: center;
  }
</style>

<div class="resume-section">
  <img src="/images/200w.gif" alt="Background GIF" class="background-gif">
  <div class="white-box">
    <h1 class="resume-text">Resume</h1>
  </div>
</div>