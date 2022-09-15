---
permalink: /first-result/
title: "First result from SIDISO project on JWST data !"
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

After hard work, the SIDISO project is proud to produce the first data processing of the projet from the JWST data. The images have been produced by `luigiz`  the Super-Resolution and deconvolution algorithm[^1], written by [François Orieux](https://pro.orieux.fr). The algorithm is the results of the research published [here](https://doi.org/10.1109/TCI.2020.2998170), followed by a lot of subsequent developments.

The main objective of such work is to improve the spatial resolution of the images. We will describe later in more details what has been done. The two images belows are obtained with the F770W, F1000W, F1130W and F2100W filters.

More works are necessary to improve the results, like models evolution, algorithms adaptation, or tests. Raw data will be made available soon. Stay tuned...

{% include figure image_path="/assets/ngc628-raw-gray.png" alt="Mean of the four filters homogenized at the resolution of F2100W filter of JWST MIRI data observing NGC628." caption="Mean of the four filters homogenized at the resolution of F2100W of JWST MIRI data  observing NGC628." %}

{% include figure image_path="/assets/ngc628-deblurred-gray-text.png" alt="Mean of the four filters of JWST MIRI data observing NGC628 processed by SIDISO's Super-Resolution and deconvolution algorithm `luigiz`." caption="Mean of the four filters of JWST MIRI data observing NGC628 processed by SIDISO's Super-Resolution algorithm `luigiz`." %}

F. Orieux, on behalf of the SIDISO team.

[^1]: available when ready
