---
layout: single
title: Tables in Jekyll
date: '2020-05-02 19:53:27 -0500'
excerpt: This post should
header:
  overlay_image: /assets/images/site/gray_bldg.jpg
  overlay_filter: 0.25
  caption: Photo by Anders Jildén on [**Unsplash**](https://unsplash.com)'
  actions:
    - label: More Info
      url: 'https://unsplash.com'
categories: jekyll html markdown
---

# A First Table

One of the surprises in coding has always been how difficult building a good looking table can be. Since my background is in R, I always start with the first 5 rows of the `mtcars` dataset.


<table id="myTable01" class="display">
      <thead>
            <tr>
                  <th> make </th>
                  <th> mpg </th>
                  <th> cyl </th>
                  <th> disp </th>
                  <th> hp </th>
                  <th> drat </th>
                  <th> wt </th>
                  <th> qsec </th>
                  <th> vs </th>
                  <th> am </th>
                  <th> gear </th>
                  <th> carb </th>
            </tr>
      </thead>
      <tbody>
            <tr>
                  <td align="right"> Mazda RX4 </td>
                  <td align="right"> 21.00 </td>
                  <td align="right"> 6.00 </td>
                  <td align="right"> 160.00 </td>
                  <td align="right"> 110.00 </td>
                  <td align="right"> 3.90 </td>
                  <td align="right"> 2.62 </td>
                  <td align="right"> 16.46 </td>
                  <td align="right"> 0.00 </td>
                  <td align="right"> 1.00 </td>
                  <td align="right"> 4.00 </td>
                  <td align="right"> 4.00 </td>
            </tr>
            <tr>
                  <td align="right"> Mazda RX4 Wag </td>
                  <td align="right"> 21.00 </td>
                  <td align="right"> 6.00 </td>
                  <td align="right"> 160.00 </td>
                  <td align="right"> 110.00 </td>
                  <td align="right"> 3.90 </td>
                  <td align="right"> 2.88 </td>
                  <td align="right"> 17.02 </td>
                  <td align="right"> 0.00 </td>
                  <td align="right"> 1.00 </td>
                  <td align="right"> 4.00 </td>
                  <td align="right"> 4.00 </td>
            </tr>
            <tr>
                  <td align="right"> Datsun 710 </td>
                  <td align="right"> 22.80 </td>
                  <td align="right"> 4.00 </td>
                  <td align="right"> 108.00 </td>
                  <td align="right"> 93.00 </td>
                  <td align="right"> 3.85 </td>
                  <td align="right"> 2.32 </td>
                  <td align="right"> 18.61 </td>
                  <td align="right"> 1.00 </td>
                  <td align="right"> 1.00 </td>
                  <td align="right"> 4.00 </td>
                  <td align="right"> 1.00 </td>
            </tr>
            <tr>
                  <td align="right"> Hornet 4 Drive </td>
                  <td align="right"> 21.40 </td>
                  <td align="right"> 6.00 </td>
                  <td align="right"> 258.00 </td>
                  <td align="right"> 110.00 </td>
                  <td align="right"> 3.08 </td>
                  <td align="right"> 3.21 </td>
                  <td align="right"> 19.44 </td>
                  <td align="right"> 1.00 </td>
                  <td align="right"> 0.00 </td>
                  <td align="right"> 3.00 </td>
                  <td align="right"> 1.00 </td>
            </tr>
            <tr>
                  <td align="right"> Hornet Sportabout </td>
                  <td align="right"> 18.70 </td>
                  <td align="right"> 8.00 </td>
                  <td align="right"> 360.00 </td>
                  <td align="right"> 175.00 </td>
                  <td align="right"> 3.15 </td>
                  <td align="right"> 3.44 </td>
                  <td align="right"> 17.02 </td>
                  <td align="right"> 0.00 </td>
                  <td align="right"> 0.00 </td>
                  <td align="right"> 3.00 </td>
                  <td align="right"> 2.00 </td>
            </tr>
      <tbody>
</table>
