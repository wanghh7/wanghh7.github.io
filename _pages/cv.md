---
layout: single
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .cv-preview-page .page {
    float: none;
    width: 100%;
  }

  .cv-preview-page .page__inner-wrap {
    max-width: 1100px;
    margin: 0 auto;
  }

  .cv-preview {
    margin-top: 1.5rem;
  }

  .cv-preview__frame {
    width: 100%;
    min-height: 80vh;
    border: 1px solid #d5d5d5;
    border-radius: 12px;
    background: #f8f8f8;
  }

  .cv-preview__fallback {
    margin-top: 1rem;
    text-align: center;
  }
</style>

<script>
  document.documentElement.classList.add('cv-preview-page');
</script>

<div class="cv-preview">
  <object
    class="cv-preview__frame"
    data="{{ base_path }}/files/Curriculum_Vitae.pdf#view=FitH"
    type="application/pdf"
  >
    <iframe
      class="cv-preview__frame"
      src="{{ base_path }}/files/Curriculum_Vitae.pdf#view=FitH"
      title="Curriculum Vitae PDF Preview"
    ></iframe>
  </object>

  <p class="cv-preview__fallback">
    If the preview does not load, <a href="{{ base_path }}/files/Curriculum_Vitae.pdf">open the PDF directly</a>.
  </p>
</div>
