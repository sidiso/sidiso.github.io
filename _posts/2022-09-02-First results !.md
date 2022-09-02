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

# First result from SIDISO project on JWST data !

After hard work, the SIDISO project is proud to produce the first data
processing of the projet from the JWST data. The algorithm is the results of the
research published [here](https://doi.org/10.1109/TCI.2020.2998170), followed by
subsequent development.

The main objective of such work is to improve the spatial resolution of the
image. We will describe in more details later what have been done.

Many work are need to be done yet on the models and algorithms to improve the
results. Stay tuned.


 ![NGC628 raw](/assets/ngc628-raw-gray.png){: .align-center}

{% include figure image_path="/assets/ngc628-raw-gray.png" alt="Grayscale version of JWST MIRI data of NGC628" caption="Grayscale version of JWST MIRI data of NGC628." %}

 ![NGC628 deblurred](/assets/ngc628-deblurred-gray-text.png){: .align-center}

{% include figure image_path="/assets/ngc628-deblurred-gray-text.png" alt="Grayscale version of JWST MIRI data of NGC628 processed by SIDISO's algorithm `Luigiz`" caption="Grayscale version of JWST MIRI data of NGC628 processed by SIDISO's algorithm `Luigiz`." %}

F. Orieux, on behalf of the SIDISO project.
