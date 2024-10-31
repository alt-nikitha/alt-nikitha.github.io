---
layout: page
title: Interpretable QA for Privacy Policies
description: It is hard to read privacy policy documents. Not sure whether your searches are tracked? Why not use our QA system to find out?
importance: 2
category: fun
img: assets/img/privacyqa.jpg
---


Humans are good at reading comprehension. However, humans cannot be expected to spend time understanding extremely long and complext policy documents. Without expertise in the domain, users may unknowingly agree to uses of their data and behaviour online. While the burden shouldn't be on the end-user to make this process more transparent, an AI tool can make parsing such documents easier.

I worked on a Question Answering system for privacy policy documents using deep learning. This question answering system is then made interpretable with the use of saliency maps and perturbation analysis. This enables users to ensure that the answers obtained are grounded in the right sections of the policy document. It also adds accessibility, transparency, and trust.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/privacyqa.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An example of how this tool answers questions about user privacy with evidence from the documents. 
</div>

