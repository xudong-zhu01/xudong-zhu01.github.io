---
# the default layout is 'page'
icon: fas fa-user-graduate
order: 1
---

## Download CV

<div style="text-align: center; margin: 30px 0;">
  <a href="https://xudong-zhu01.github.io/documents/cv-xudong-zhu.pdf" class="btn btn-primary" download style="display: inline-block; padding: 12px 30px; background-color: #0d6efd; color: white; text-decoration: none; border-radius: 5px; font-weight: 500; box-shadow: 0 2px 4px rgba(0,0,0,0.1); transition: all 0.3s ease;">
    📄 Download Full CV (PDF)
  </a>
  <p style="margin-top: 10px; color: #6c757d; font-size: 0.9em;">Last updated: {{ site.time | date: "%B %Y" }}</p>
</div>

---

## View Resume

<style>
  .resume-container {
    position: relative;
    width: 100%;
    margin-top: 20px;
  }
  
  .resume-container iframe {
    border: 1px solid #dee2e6;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    width: 100%;
    height: 80vh;
    min-height: 600px;
  }
  
  @media (max-width: 768px) {
    .resume-container iframe {
      height: 70vh;
      min-height: 500px;
    }
    
    .mobile-notice {
      display: block;
      padding: 15px;
      background-color: #fff3cd;
      border: 1px solid #ffc107;
      border-radius: 5px;
      margin-bottom: 15px;
      text-align: center;
    }
  }
  
  @media (min-width: 769px) {
    .mobile-notice {
      display: none;
    }
  }
</style>

<div class="mobile-notice">
  📱 For the best experience on mobile, please download the PDF above.
</div>

<div class="resume-container">
  <iframe src="https://mozilla.github.io/pdf.js/web/viewer.html?file=https://xudong-zhu01.github.io/documents/cv-xudong-zhu.pdf" title="Xudong Zhu - Curriculum Vitae"></iframe>
</div>
