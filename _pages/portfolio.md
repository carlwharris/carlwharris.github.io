---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}



<hr style="margin:0;padding:0; height:4px;background-color: #696969;">

<table width="100%" style="border:none;margin:0;padding:0; margin-bottom:-2em">
<td style="border:none;padding:0px;margin:0" width="70%" align="left">
	<h2 style="font-size:2em;">Predicting pandemic mental health outcomes</h2>
</td>
<td style="border:none;padding:0px;margin:0;"  align="right">
	<a href="https://psyarxiv.com/7enqw/">
		<img align="center" src="../files/PsyArXiv_logo.png" style="height:5em">
	</a>
</td>
</table>

<img src="../files/covid19_fig.png" width="55%" style="margin: 0em 0em 0em 0em; " align="right">
<p style="font-size:16px;padding:0;margin:0;margin-bottom:1em">The “Mental Health Impact of COVID-19 Pandemic on NIMH Patients and Volunteers” study was a longitudinal study launched in spring 2020 by researchers at NIMH, to investigate the effect of the emerging COVID-19 pandemic on mental health. For each participant, the study collected personal characteristics, such as demographics, psychological traits, and clinical history, together with personal circumstances at regular intervals during their enrollment in the study. In this paper, we examine the degree to which a variety of mental health outcomes over time for an individual can be predicted from personal characteristics and their changing circumstances, using regression models trained on other study participants. We find that it is possible to predict the variation of a participant's mental health outcomes from time point to time point, for most of the outcomes we consider. This capability is dominated by information about outcome at the point of enrollment in the study, but can be improved by considering personal characteristics and circumstances.

</p>



<hr style="margin:0;padding:0; height:4px;background-color: #696969;">

<table width="100%" style="border:none;margin:0;padding:0; margin-bottom:-2em">
<td style="border:none;padding:0px;margin:0" width="70%" align="left">
	<h2 style="font-size:2em;">Holographic photostimulation extension</h2>
</td>
<td style="border:none;padding:0px;margin:0;"  align="right">
	<a href="https://github.com/carlwharris/nwb-photostims">
		<img align="center" src="../files/GitHub_logo.png" style="height:2.5em">
	</a>
</td>
</table>

<img src="../files/nwb_overview.png" width="45%" style="margin: 0em 0em 0em 0em; " align="right">
<p style="font-size:16px;padding:0;margin:0;margin-bottom:1em">State-of-the-art <a href="https://www.nature.com/articles/s41467-017-01031-3">holographic photostimulation methods</a>, used in concert with <a href="https://www.nature.com/articles/nmeth818">two-photon imaging</a>, 
allow unprecedented 
control and measurement of cell activity in the living brain. Methods for managing data for two-photon imaging 
experiments are improving, but there is little to no standardization of data for holographic stimulation methods. 
Stimulation in vivo depends on fine-tuning many experimental variables, which poses a challenge for reproducibility 
and data sharing between researchers. To improve <a href="https://www.sciencedirect.com/science/article/pii/S0896627321009557">standardization</a> of photostimulation data storage and processing, 
we release this extension as a generic data format for simultaneous holographic stimulation experiments, 
using the <a href="https://www.nwb.org/">NeuroData Without Borders (NWB)</a> format for neurophysiology data to store experimental details and data relating to both acquisition 
and photostimulation. It includes <a href="https://pynwb.readthedocs.io/en/stable/">containers</a> for storing photostimulation-specific device parameters, holographic patterns (either 2D or 3D), and time series data related to photostimulation. This project is part of an ongoing intra-NIMH collaboration between <a href="https://markhisted.org/">Mark Histed's lab</a> and the <a href="https://cmn.nimh.nih.gov/dsst">Data Science and Sharing Team</a>.</p>


<hr style="margin:0;padding:0; height:4px;background-color: #696969;">

<table width="100%" style="border:none;margin:0;padding:0">
<td style="border:none;padding:0px;margin:0;" width="70%" align="left">
	<h2 style="font-size:2.5em;">Context-dependent encoding</h2>
</td>
<td style="border:none;padding:0px;margin:0;"  align="right">
	<a href="https://arxiv.org/abs/2211.09295">
		<img align="center" src="../files/arxiv-logo-1.png" style="height:2.5em;margin-top:-1em"></a>
	&nbsp;&nbsp;
	</a>
</td>
</table>

<img src="../files/boxplots_v2.png" width="35%" style="margin: 0em 0em 0em 0em; " align="right">
<p style="font-size:16px;padding:0;margin:0;margin-bottom:1em">We propose a decoding-based approach to detect context effects on neural codes in longitudinal neural recording data. The approach is agnostic to how information is encoded in neural activity, and can control for a variety of possible confounding factors present in the data. We demonstrate our approach by determining whether it is possible to decode location encoding from prefrontal cortex in the mouse and, further, testing whether the encoding changes due to task engagement.</p>


<hr style="margin:0;padding:0; height:4px;background-color: #696969;">

<table width="100%" style="border:none;margin:0;padding:0">
<td style="border:none;padding:0px;margin:0;" width="70%" align="left">
	<h2 style="font-size:2.5em;">DeepAction Toolbox</h2>
</td>
<td style="border:none;padding:0px;margin:0;"  align="right">
	<a href="https://www.biorxiv.org/content/10.1101/2022.06.20.496909v1">
		<img align="center" src="https://www.biorxiv.org/sites/default/files/site_logo/bioRxiv_logo_homepage.png" style="height:2.5em;margin-top:-1em"></a>
	&nbsp;&nbsp;
	<a href="https://github.com/carlwharris/DeepAction"><img align="center" src="../files/GitHub_logo.png" style="height:2.5em;margin-top:-1em">
	</a>
</td>
</table>


<table width="100%" style="margin:0;border:none;margin-top:-1.25em;padding:0;">
<tr style="width:100%;border:none;">
	<td style="border:none;padding:0px" width="65%">
		<p style="font-size:16px;padding:0;margin:0">In this project, I created a MATLAB toolbox for automated classification of animal in behavior. It uses features extracted from raw video frames to train a bidirectional LSTM classifier, which in addition to predicting behavior generates a confidence score for the predicted label. These confidence scores allow for the selective review and correction of ambiguous annotations while omitting unnecessary review.</p>
	</td>
	<td style="border:none;padding:0px;vertical-align:top;" rowspan ="2">
		<img src="../files/workflow.png" style="max-width:100%;height:auto;margin-left:1em">
	</td>
</tr>
<tr style="width:100%;border:none;background-color:rgba(0, 0, 0, 0);">
	<td style="border:none; padding:0px;vertical-align:top" width="60%">
		<table width="100%" style="margin:0;border:none;padding:0">
			<tr style="width:100%;border:none;margin:0;padding:0;">
				<td style="border:none;padding:0.2em" width="33%">
					<img src="../files/home_cage_50.gif" style="max-width:100%;height:auto;">
				</td>
				<td style="border:none;padding:0.2em" width="33%">
					<img src="../files/CRIM13S-785.gif" style="max-width:100%;height:auto;">
				</td>						
				<td style="border:none;padding:0.2em" width="33%">
					<img src="../files/CRIM13T-203.gif" style="max-width:100%;height:auto;">
				</td>
			</tr>
			<tr style="width:100%;border:none;margin:0;padding:0;">
				<td style="border:none;padding:0.2em;" width="33%">
					<img src="../files/home_cage_182.gif" style="max-width:100%;height:auto;">
				</td>
				<td style="border:none;padding:0.2em" width="33%">
					<img src="../files/CRIM13S-1785.gif" style="max-width:100%;height:auto;">
				</td>						
				<td style="border:none;padding:0.2em" width="33%">
					<img src="../files/CRIM13T-256.gif" style="max-width:100%;height:auto;">
				</td>
			</tr>
		</table>
	</td>
</tr>
</table>


<hr style="margin:0;padding:0; height:4px;background-color: #696969;margin-top:0.7em">

<table width="100%" style="border:none;margin:0;padding:0">
<td style="border:none;padding:0px;margin:0" width="70%" align="left">
	<h2 style="font-size:2.5em;">HPC keypoint extraction</h2>
</td>
<td style="border:none;padding:0px;margin:0;"  align="right">
	<a href="https://github.com/carlwharris/Discovery-DLC-processing">
		<img align="center" src="../files/GitHub_logo.png" style="height:2.5em">
	</a>
</td>
</table>

<div style="margin-top:-1em;">
<img src="../files/pipeline_diagram.png" style="width:60%;height:auto;float:right;padding-left:0.5em">
<p style="font-size:16px">The purpose of this project is to enable the extraction of animal keypoints from very large video datasets via DeepLabCut, on the Dartmouth College <a href="https://rc.dartmouth.edu/index.php/discovery-overview/">Discovery HPC cluster</a>. Videos are recorded & uploaded to a folder in the user's DropBox account, after which the user selects a subset to extract annotations for. For subset, corresponding video files are first downloaded from DropBox onto the user's HPC accounts using an API key. Then, a trained DeepLabCut network is used to extract keypoints from the video. After keypoints have been extracted, the video is deleted, to clear space for the rest of the video files in the batch to be downloaded. In the final step, keypoints uploaded from the HPC to the user's specified DropBox folder.</p>
</div>



<hr style="margin:0;padding:0; height:4px;background-color: #696969;margin-top:0.5em">

<table width="100%" style="border:none;margin:0;padding:0">
<td style="border:none;padding:0px;margin:0" width="70%" align="left">
	<h2 style="font-size:2.5em;">Elliptic curve cryptography</h2>
</td>
<td style="border:none;padding:0px;margin:0;"  align="right">
	<a href="https://github.com/carlwharris/elliptic-curve-cryptosystems">
		<img align="center" src="../files/GitHub_logo.png" style="height:2.5em">
	</a>
</td>
</table>

<div>
<table width="100%" style="border:none;margin:0;padding:0;margin-top:-1.25em">
<tr style="border:none;margin:0">
	<td style="border:none;padding:0px;margin:0;" width="20%" align="left">
	<img src="../files/ECC.jpeg" style="width:90%;">
			</td>
	<td style="border:none;padding:0px;margin:0;" >
		<p style="font-size:16px; padding:0;">Final project for Abstract Algebra (Dartmouth College, Fall 2020) in which I implemented a simple elliptic curve cryptosystem in MATLAB. The corresponding <a href="https://github.com/carlwharris/elliptic-curve-cryptosystems/blob/main/ECC%20Project%20Paper.pdf">paper</a> includes information about: the invention of public key and elliptic curve cryptography, elliptic curves over finite fields, subgroup generation, and how cryptographic systems are constructed from elliptic curves and used to encrypt and decrypt messages.</p>
	</td>
</tr>
</table>
</div>

<hr style="margin:0;padding:0; height:4px;background-color: #696969;margin-top:0.75em">
