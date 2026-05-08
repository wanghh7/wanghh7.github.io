---
layout: archive
title: "Dogtor"
permalink: /dogtor/
author_profile: true
---

{% include base_path %}

<style>
  .dog-gallery {
    margin-top: 1.5rem;
  }

  .dog-gallery h2 {
    margin-top: 2rem;
    margin-bottom: 1rem;
  }

  .dog-gallery__grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
    margin-bottom: 2rem;
  }

  .dog-gallery__image {
    width: 100%;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    display: block;
    border-radius: 12px;
  }

  @media (max-width: 800px) {
    .dog-gallery__grid {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }

  @media (max-width: 520px) {
    .dog-gallery__grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="dog-gallery">
  <h2>Maggie</h2>
  <div class="dog-gallery__grid">
    <img class="dog-gallery__image" src="{{ base_path }}/images/Maggie1.JPG" alt="Maggie photo 1">
    <img class="dog-gallery__image" src="{{ base_path }}/images/Maggie2.JPG" alt="Maggie photo 2">
    <img class="dog-gallery__image" src="{{ base_path }}/images/Maggie3.JPG" alt="Maggie photo 3">
    <img class="dog-gallery__image" src="{{ base_path }}/images/Maggie4.JPG" alt="Maggie photo 4">
    <img class="dog-gallery__image" src="{{ base_path }}/images/Maggie5.JPG" alt="Maggie photo 5">
    <img class="dog-gallery__image" src="{{ base_path }}/images/Maggie6.JPG" alt="Maggie photo 6">
  </div>

  <h2>Mia</h2>
  <div class="dog-gallery__grid">
    <img class="dog-gallery__image" src="{{ base_path }}/images/Mia1.JPG" alt="Mia photo 1">
    <img class="dog-gallery__image" src="{{ base_path }}/images/Mia2.JPG" alt="Mia photo 2">
    <img class="dog-gallery__image" src="{{ base_path }}/images/Mia3.JPG" alt="Mia photo 3">
  </div>
</div>
