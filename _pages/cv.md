---
layout: single
title: "CV"
permalink: /cv/
---

<style>
  html, body {
    background-color: #000;
    margin: 0;
    padding: 0;
    height: 100%;
  }

  /* Hides the headers/sidebars */
  .masthead, .page__footer, .sidebar, .page__title, .page__meta {
    display: none;
  }

  /* Centers the content */
  #main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    padding: 0;
  }

  /* Ensures the PDF container fills the center */
  .container {
    width: 100%;
    height: 100%;
    max-width: 100%;
  }
</style>

<object data="{{ site.baseurl }}/files/cv.pdf" type="application/pdf" width="100%" height="100%">
  <p>Your browser doesn't support PDFs. <a href="{{ site.baseurl }}/files/cv.pdf" style="color: white;">Download the PDF here.</a></p>
</object>
