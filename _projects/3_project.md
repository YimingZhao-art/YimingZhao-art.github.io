---
layout: page
title: SemRecon
description: A research in CV reconstruction and perception
img: assets/img/semrecon.png
importance: 1
category: work
---
In this project, we proposed a framework combining perception into a recronstrucion process.


We used DinoV2 to get the 2D features.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/dino.png" title="dino" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


Then we use TSDF as our reconstruction baseline.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tsdf.png" title="tsdf" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


We project 2D DinoV2 features to 3D. And use the features to do segmentation.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/seg.png" title="segmentaion" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


We got a preliminary result, and we are currently trying to do other thing.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/result.png" title="result" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
