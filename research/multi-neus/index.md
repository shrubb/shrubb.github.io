---
title: ""
---

<style type="text/css">
    * {text-align: justify;}
    table, td, tr {border: none;}

    .title {text-align: center; margin: 0px;}

    .no-border-table {font-size: 90%; text-align: center;}
    .no-border-table td {border: none; text-align: center;}

    .authors {margin-bottom: 0px; background-color: #e5e5e5;}

    .affiliations {margin: 0px;}
    .affiliations td {background-color: #f3f3f3;}

    .video-grid td {background-color: #ffffff; padding: 1%;}
    table.video-grid img, video {
      width: 100%;
      /*padding: 2% 2% 2% 2%;*/
    }

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
{: .no-border-table .authors}

|<sup>1</sup>[Skoltech](https://www.skoltech.ru/) |<sup>2</sup>[AIRI](https://airi.net/) |<sup>3</sup>[Cinemersive Labs](https://www.cinemersivelabs.com/) |
{: .no-border-table .affiliations}

<table class="no-border-table video-grid">
  <tr>
    <td width="10%"></td>
    <td width="26.6666%"><img src="elon.jpg" /></td>
    <td><video autoplay loop src="elon.mp4" /></td>
    <td width="10%"></td>
  </tr>
  <tr>
    <td width="10%"></td>
    <td width="26.6666%"><img src="botticelli.jpg" /></td>
    <td><video autoplay loop src="botticelli.mp4" /></td>
    <td width="10%"></td>
  </tr>
</table>

### Abstract

We present an approach for the reconstruction of textured 3D meshes of human heads from one or few views. Since such few-shot reconstruction is underconstrained, it requires prior knowledge which is hard to impose on traditional 3D reconstruction algorithms. In this work, we rely on the recently introduced 3D representation &#8211; neural implicit functions &#8211; which, being based on neural networks, allows to naturally learn priors about human heads from data, and is directly convertible to textured mesh. Namely, we extend NeuS, a state-of-the-art neural implicit function formulation, to represent multiple objects of a class (human heads in our case) simultaneously. The underlying neural net architecture is designed to learn the commonalities among these objects and to generalize to unseen ones. Our model is trained on just a hundred smartphone videos and does not require any scanned 3D data. Afterwards, the model can fit novel heads in the few-shot or one-shot modes with good results.

|<a href="https://arxiv.org/abs/2209.04436"><img src="/research/resource-images/pdf.svg"><br>Full Paper</a>|<img src="/research/resource-images/work-in-progress.svg"><br>Source Code|<a href="citation.txt"><img src="/research/resource-images/bibtex.svg"><br>BibTeX Citation</a>|
{: .resource-links}

### Additional Results

<video preload="none" controls src="additional-results.mp4" />
