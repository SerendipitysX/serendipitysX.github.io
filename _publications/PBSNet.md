---
title: "Progressive Band-seperated Convolutional Neural Network for Multispectral Pansharpening"
collection: publications
permalink: /publication/PBSNet
excerpt: 'About remote sensing image super-resolution'
date: 2021-03-17
venue: 'IGARSS'
---
<div class="post-content" itemprop="articleBody"> <p><img src="/assets/images/IGARSS_PBSN.png" alt=""></p> <h3 id="abstract">Abstract</h3> <p>Recently, convolutional neural networks (CNNs) have been introduced to pansharpening for enhancing fusion accuracy and overcoming the drawbacks of the conventional methods. However, most of methods based on CNN fail to distinguish the difference of multispectral bands, and only use a uniform set of convolutional kernels to extract features. In this paper, we design a progressive, band-separated convolutional network architecture for discriminatively learning the features and relation among spectral bands, aiming to address the problem mentioned before. More specifically, the proposed architecture mainly consists of three aspects. First, to accurately preserve the spectral peculiarities, we <a href=""><span style="color: #4044c2">divide the multispectral input image in terms of its bands into several groups</span></a>. Second, our original panchromatic and multispectral inputs are filtered by a high-pass operation to further yield more spatial details. Third, we use a <a href=""><span style="color: #3ec9c0">spectral fusion module (SFM)</span></a> for each group and associate them to progressively assemble the whole architecture. It is worth mentioning that <a href=""><span style="color: #c23ec2">the architecture could be integrated into any other competitive CNNs</span></a> to improve the performance. Both visual and quantitative experiments have demonstrated that our proposed method outperforms recent state-of-the-art pansharpening techniques.</p> <h4 id="schematic-diagram-of-the-proposed-method">Schematic Diagram of the Proposed Method</h4> <p><img src="https://chengjin-git.github.io/assets/images/IGARSS_PBSN_schematic.png" alt=""></p> <h4 id="downloads">Downloads</h4> <p>Full paper: <a href="https://github.com/SerendipitysX/serendipitysX.github.io/blob/master/files/IGARSS2021_PBSNet.pdf">click here</a></p> <p>code: <a href="https://github.com/SerendipitysX/PBSNet">click here</a></p> <h4 id="reference">Reference</h4> <div class="language-bib highlighter-rouge"><div class="highlight"><pre class="highlight"><code><span class="nc">@INPROCEEDINGS</span><span class="p">{</span><span class="nl">pbsnet</span><span class="p">,</span>
  <span class="na">author</span><span class="p">=</span><span class="s">{Shi-Shi Xiao, Cheng Jin, Tian-Jing Zhang, Ran Ran and Liang-Jian Deng}</span><span class="p">,</span>
  <span class="na">booktitle</span><span class="p">=</span><span class="s">{IGARSS 2021 - 2021 IEEE International Geoscience and Remote Sensing Symposium}</span><span class="p">,</span> 
  <span class="na">title</span><span class="p">=</span><span class="s">{Progressive Band-separated Convolutional Neural Network For Multispectral Pansharpening}</span><span class="p">,</span> 
  <span class="na">year</span><span class="p">=</span><span class="s">{2021}</span><span class="p">,</span>
  <span class="na">volume</span><span class="p">=</span><span class="s">{}</span><span class="p">,</span>
  <span class="na">number</span><span class="p">=</span><span class="s">{}</span><span class="p">,</span>
  <span class="na">pages</span><span class="p">=</span><span class="s">{4464-4467}</span><span class="p">}</span>



