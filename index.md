---
title       : Quantifying the relationship between co-expression, co-regulation
              and gene function
subtitle    : Dominic J Allocco, Isaac S Kohane and Atul J Butte
author      : Keith Hughitt
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
mode        : selfcontained 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
---

<!-- Custom Styles -->
<style type='text/css'>
    slides > slide {
        height: 800px;
        margin-top: -400px;
    }
    img {
        max-height: 560px;
        max-width: 964px;
    }
    slide a {border-bottom: none;}
    .references li { font-size: 14px; }
    .references li p { font-size: 14px; }
</style>

<!-- Custom JavaScript -->
<script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.7.min.js"></script>
<script type='text/javascript'>
$(function() {
    $("p:has(img)").addClass('centered');
});
</script>

## Overview

>- An important goal in biology is to understand the gene regulatory networks
   of various organisms.
>- There are now several high-throughput methods for querying the regulatory
>  relationships between genes, e.g.::
>   - ChIP-chip
>   - ChIP-Seq
>- In some cases, however, it is either not possible or not convenient to
>  collect this sort of data (e.g. Trypanosomes.)
>- In principle, genes which are co-regulated should show some similarities in
>  their expression profiles.
>- <span class='red'>Is it possible instead to infer gene-regulatory relationships from
>  transcriptomic data such as Microarray or RNA-Seq?</span>


---.references

## References





- Dominic J Allocco, Isaac S Kohane, Atul J Butte,   (2004) Unknown.  <em>Bmc Bioinformatics</em>  <strong>5</strong>  18-NA  <a href="http://dx.doi.org/10.1186/1471-2105-5-18">10.1186/1471-2105-5-18</a>

