# Differential Gaussian Rasterization

**NOTE**: this is a modified version to support **Depth** & **Alpha** & **ObjectID** rendering (both forward and backward) from the [original repository](https://github.com/graphdeco-inria/diff-gaussian-rasterization). 

```python
rendered_image, radii, rendered_depth, rendered_alpha, rendered_objects = rasterizer(
    means3D=means3D,
    means2D=means2D,
    shs=shs,
    sh_objs = sh_objs,
    colors_precomp=colors_precomp,
    opacities=opacity,
    scales=scales,
    rotations=rotations,
    cov3D_precomp=cov3D_precomp,
)
```



<section class="section" id="BibTeX">
  <div class="container is-max-desktop content">
    <h2 class="title">BibTeX</h2>
    <pre><code>@Article{kerbl3Dgaussians,
      author       = {Kerbl, Bernhard and Kopanas, Georgios and Leimk{\"u}hler, Thomas and Drettakis, George},
      title        = {3D Gaussian Splatting for Real-Time Radiance Field Rendering},
      journal      = {ACM Transactions on Graphics},
      number       = {4},
      volume       = {42},
      month        = {July},
      year         = {2023},
      url          = {https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/}
}</code></pre>
  </div>
</section>
