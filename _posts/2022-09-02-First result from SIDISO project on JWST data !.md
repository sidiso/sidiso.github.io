---
defaults:
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: false
      share: true
      related: true
    header:
      image: /assets/ngc628-deblurred-gray-text.png
      caption: "NGC628 JWST MIRI data processed by Luigiz"
---

After hard work, the SIDISO project is proud to produce the first data processing of the projet from the JWST data. The image has been produced by the `luigiz` algorithm[^1], written by [François Orieux](https://pro.orieux.fr). The algorithm is the results of the research published [here](https://doi.org/10.1109/TCI.2020.2998170), followed by a lot of subsequent developments.

The main objective of such work is to improve the spatial resolution of the image. We will describe later in more details what has been done.

More works are necessary to improve the results, like models evolution, algorithms adaptation, or tests. Stay tuned...

{% include figure image_path="/assets/ngc628-raw-gray.png" alt="Grayscale version of JWST MIRI data of NGC628" caption="Grayscale version of JWST MIRI data of NGC628." %}

{% include figure image_path="/assets/ngc628-deblurred-gray-text.png" alt="Grayscale version of JWST MIRI data of NGC628 processed by SIDISO's algorithm `luigiz`" caption="Grayscale version of JWST MIRI data of NGC628 processed by SIDISO's algorithm `luigiz`." %}

F. Orieux, on behalf of the SIDISO project.

[^1]: available when ready
