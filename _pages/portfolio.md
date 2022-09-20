---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


<table width="100%" style="border:none;">
<td style="border:none;">
<div style='float: left; text-align: left'><h1>DeepAction</h1></div>
<div style='float: right; text-align: right'><a href="https://github.com/carlwharris/DeepAction"><img align="center" src="../files/GitHub_logo.png" style="height:25px">
</a>&nbsp;<a href="https://www.biorxiv.org/content/10.1101/2022.06.20.496909v1"><img align="center" src="https://www.biorxiv.org/sites/default/files/site_logo/bioRxiv_logo_homepage.png" style="height:25px"></a></h1></div>
</td>
</table>


In this project, I created a MATLAB toolbox for automated classification of animal in behavior. It uses features extracted from raw video frames to train a bidirectional LSTM classifier, which in addition to predicting behavior generates a confidence score for the predicted label. These confidence scores allow for the selective review and correction of ambiguous annotations while omitting unnecessary review. The toolbox is publicly available on <a href="https://github.com/carlwharris/DeepAction">GitHub</a>, and the preprint is published on <a href="https://www.biorxiv.org/content/10.1101/2022.06.20.496909v1">bioRxiv</a>.
  
<p align="center">
<img src="../files/home_cage_182.gif" width="200">
<img src="../files/CRIM13S-1785.gif" width="200">
</p>


<table width="100%" style="border:none;">
<td style="border:none;">
<div style='float: left; text-align: left'><h1>Eliptic curve cryptography</h1></div>
<div style='float: right; text-align: right'><h1><a href="https://github.com/carlwharris/elliptic-curve-cryptosystems"><img align="center" src="../files/GitHub_logo.png" style="height:25px"></a></h1></div>
</td>
</table>

Final project for Abstract Algebra (Dartmouth College, Fall 2020) which provides an overview of elliptic curve cryptography (ECC) and implement a simple elliptic curve cryptosystem in MATLAB. The <a href="https://github.com/carlwharris/elliptic-curve-cryptosystems/blob/main/ECC%20Project%20Paper.pdf">paper</a> describing the project is divided into four sections:

1. **Introduction and Historical Background**: overview of public key cryptography and the advent of elliptic curve cryptography
2. **Background on Elliptic Curves**: itroduction to elliptic curves over finite fields
3. **Elliptic Curve Subgroups**: generation of elliptic curve subgroups and the properties relevant to my ECC implementation example
4. **Elliptic Curve Cryptosystems: theory and MATLAB Implementation**: overview of how cryptographic systems are constructed from elliptic curves and used to encrypt and decrypt messages, along with a MATLAB implementation of this process