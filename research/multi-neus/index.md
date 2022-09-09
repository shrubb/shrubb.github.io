---
title: ""
---

<style type="text/css">
    * {text-align: justify;}
    table, td, tr {border: none;}

    .title {text-align: center; margin: 0px;}

    .authors {font-size: 90%; text-align: center; margin-bottom: 0px;}
    .authors td {border: none; text-align: center;}

    .affiliations {font-size: 90%; text-align: center; margin: 0px; }
    .affiliations td {border: none; text-align: center;}

    .image-grid {font-size: 90%; text-align: center; margin: 0px; }
    .image-grid td {border: none; text-align: center;}

    table.resource-links td {
      border: none;
      text-align: center;
    }
    table.resource-links img {
      position: relative;
      max-width: 70px;
      max-height: 70px

      display: block;
      margin: 0 auto;
    }
</style>

## **Multi-NeuS**: 3D Head Portraits from Single Image with Neural Implicit Functions
{: .title}

|Egor Burkov<sup>1</sup> |Ruslan Rakhimov<sup>1</sup> |Aleksandr Safin<sup>1</sup> |Evgeny Burnaev<sup>12</sup> |Victor Lempitsky<sup>3</sup> |
{: .authors}

|<sup>1</sup>[Skoltech](https://www.skoltech.ru/) |<sup>2</sup>[AIRI](https://airi.net/) |<sup>3</sup>[Cinemersive Labs](https://www.cinemersivelabs.com/) |
{: .affiliations}

|image_original|gif_rgb|git_normals|image_original|gif_rgb|git_normals|
{: .image-grid}

### Abstract

We present an approach for the reconstruction of textured 3D meshes of human heads from one or few views. Since such few-shot reconstruction is underconstrained, it requires prior knowledge which is hard to impose on traditional 3D reconstruction algorithms. In this work, we rely on the recently introduced 3D representation &#8211; neural implicit functions &#8211; which, being based on neural networks, allows to naturally learn priors about human heads from data, and is directly convertible to textured mesh. Namely, we extend NeuS, a state-of-the-art neural implicit function formulation, to represent multiple objects of a class (human heads in our case) simultaneously. The underlying neural net architecture is designed to learn the commonalities among these objects and to generalize to unseen ones. Our model is trained on just a hundred smartphone videos and does not require any scanned 3D data. Afterwards, the model can fit novel heads in the few-shot or one-shot modes with good results.

|<a href="https://arxiv.org/pdf/xxxx.xxxxx"><img src="/research/resource-images/pdf.svg"><br>Full Paper</a>|<img src="/research/resource-images/work-in-progress.svg"><br>Source Code|<a href="https://dblp.uni-trier.de/rec/journals/corr/abs-xxxx-xxxxx.html?view=bibtex"><img src="/research/resource-images/bibtex.svg"><br>BibTeX Citation</a>|
{: .resource-links}