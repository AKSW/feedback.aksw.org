---
layout: default
---

# Structured Feedback for [aksw.org](http://aksw.org/)

This is the the Page is the primary resource for information regarding *Structured Feedback*.
It also comprises a setup of all components required to demonstrate the protocol.
The infrastructure is as well used for your work group homepage at [http://aksw.org/](http://aksw.org/).

{{ site.description }}

## How to Give Feedback

To provide feedback for this site you can start by clicking the button “Give Feedback” in th bottom right corner.
For the present page, no RDF is provided, this means the *AnnotationClient* is in the default fallback mode for simple text comments.
<!-- On [http://aksw.org/](http://aksw.org/) you should also be able to create patches. -->

Pressing the “Submit” button will create an RDF resource representing your comment at `http://resource.feedback.aksw.org/`.
After the creation of the resource a [Semantic Pingback](https://aksw.github.io/SemanticPingback/) ping is sent to [http://pingback.feedback.aksw.org/](http://pingback.feedback.aksw.org/).
