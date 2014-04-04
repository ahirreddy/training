---
layout: global
title: Introduction
navigation:
  weight: 10
  show: true
---

# Welcome
Welcome to the Stanford Workshop hands-on exercises! These exercises are extended and enhanced from those given at previous <a href="http://ampcamp.berkeley.edu">AMP Camp Big Data Bootcamps</a>. They were written by volunteer graduate students and postdocs in the <a href="https://amplab.cs.berkeley.edu/">UC Berkelay AMPLab</a>, and members of the open-source team at Databricks. Many of these individuals are present today as teaching assistants. The exercises we cover today will have you working directly with the Spark specific components of the AMPLab's open-source software stack,
called the <a href="https://amplab.cs.berkeley.edu/software/">Berkeley Data Analytics Stack
(BDAS)</a>.


You can navigate around the exercises by looking in the page header or footer and clicking on the arrows or the dropdown button that shows the current page title (as shown in the figure below).

<p style="margin-bottom:15px"><img src="img/header-nav-dropdown-button-summit.png" class="shadow" style="height:auto; width:498px"/></p>

The components we will cover at the first Spark Training are listed below.

## Exercises

1. [Scala](introduction-to-the-scala-shell.html) - a quick crashcourse on the Scala language and command line interface.
2. [Spark](data-exploration-using-spark.html) [(project homepage)](http://spark.incubator.apache.org) - a fast cluster compute engine.
3. <a href="movie-recommendation-with-mllib.html">Machine Learning with MLLib</a> <a href="http://spark.incubator.apache.org/docs/latest/mllib-guide.html">(project homepage)</a> - Build a movie recommender with Spark.
4. [Optional] <a href="graph-analytics-with-graphx.html">Graph Analytics with GraphX</a> <a href="http://spark.incubator.apache.org/docs/latest/graphx-programming-guide.html">(project homepage)</a> - Explore graph-structured data (e.g., Web-Graph) and graph algorithms (e.g., PageRank) with GraphX.


# Getting Started

If you are attending Spark Training in person, the TAs will be handing out cluster hostnames and you can obtain the private key from the TinyURL address on the projector.  Once you have your cluster hostname and private key you can [follow the directions to log into your cluster](logging-into-the-cluster.html).

<!-- <p class="alert alert-warn">
<i class="icon-info-sign">    </i>
We sent the email to the address you used to registered with. If you don't see the email, first check your spam filter, then ask a TA.
</p> -->

If you are participating in the exercises from a remote location, you will want to [launch a BDAS cluster on Amazon EC2](launching-a-bdas-cluster-on-ec2.html) for yourself.
