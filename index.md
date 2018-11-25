---
layout: default
---

# Structured Feedback for [aksw.org](http://aksw.org/)

This is the the Page is the primary resource for information regarding *Structured Feedback*.
It also comprises a setup of all components required to demonstrate the protocol.
The infrastructure is as well used for the [MMoOn - Open Hebrew morphological lexicon(https://mmoon-project.github.io/JekyllPage/).

{{ site.description }}

## How to Give Feedback

To provide feedback for this site you can start by clicking the button *Give Feedback* in th bottom right corner.
For the present page, no RDF is provided, this means the *AnnotationClient* is in the default fallback mode for simple text comments.
<!-- On [http://aksw.org/](http://aksw.org/) you should also be able to create patches. -->

Pressing the *Submit* button will create an RDF resource representing your comment at `http://resource.feedback.aksw.org/`.
After the creation of the resource a [Semantic Pingback](https://aksw.github.io/SemanticPingback/) ping is sent to [http://pingback.feedback.aksw.org/](http://pingback.feedback.aksw.org/), which is advertised by this page in the head.

    <head xmlns:pingback="http://purl.org/net/pingback/">
        <link rel="pingback:to" href="http://pingback.feedback.aksw.org" />
    </head>

## Read more about Structured Feedback
If you want to read more about Structured Feedback check out our paper at LDOW2016:

[*Structured Feedback: A Distributed Protocol for Feedback and Patches on the Web of Data*](http://ceur-ws.org/Vol-1593/article-02.pdf) by Natanael Arndt, Kurt Junghanns, Roy Meissner, Philipp Frischmuth, Norman Radtke, Marvin Frommhold, and Michael Martin in Proceedings of the Workshop on Linked Data on the Web (LDOW 2016) co-located with the 25th International World Wide Web Conference (WWW 2016)
