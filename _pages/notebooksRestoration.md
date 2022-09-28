---
layout: splashnew
permalink: /notebooksRestoration/
header:
  overlay_image: /images/headerImages/Restoration.jpg
  overlay_filter: 0.2
title: "Image Restoration"
feature_row1:
    - image_path: /images/NotebookImages/Restoration/NLA.jpg
      title: "Non local approaches for image denoising"
      excerpt: "The subject of this practical session is patch-based image denoising. It covers PCA image denoising, inspired by the paper [*C.-A. Deledalle and J. Salmon and A. Dalalyan, Image denoising with patch based PCA: local versus global, proceedings of BMVC 2011.*](https://hal.inria.fr/hal-00654289/) and DCT image denoising based on the algorithm described on [*Guoshen Yu, and Guillermo Sapiro, DCT image denoising: a simple and effective image denoising algorithm, Image Processing On Line, 1 (2011)*](https://www.ipol.im/pub/art/2011/ys-dct/).
      

      *Image: PCA denoising (Notre Dame of Órleans)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/Restoration/Non_local_approaches_for_image_denoising.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/Restoration/Non_local_approaches_for_image_denoising.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
    - image_path: /images/NotebookImages/Restoration/NLM.jpg
      title: "Non local means for denoising"
      excerpt: "This practical session explains how to implement the [Non local means algorithm](https://epubs.siam.org/doi/pdf/10.1137/040616024?casa_token=T_quJzhNoP8AAAAA:JYmsToAmRuk_jyIaLUEpwQqlmu5rCCB_j49qFTrhCchWUE2RgFC8SWsh5i-yEVnrNd1GTt5f29HClw) for denoising images, introduced in 2005 by Buadès, Coll and Morel in [Buades, A., Coll, B., & Morel, J. M. (2005). *A review of image denoising algorithms, with a new one*. Multiscale modeling & simulation, 4(2), 490-530.](https://hal.archives-ouvertes.fr/hal-00271141/document). The session describes various implementations of the algorithm: from the naive version, through an implementation using integral images, and finally the pytorch version.
      
      
      *Image: Pytorch NL means denoising (Saint Emilion)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/Restoration/Non_Local_Means_for_denoising.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/Restoration/Non_Local_Means_for_denoising.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
    - image_path: /images/NotebookImages/Restoration/NetD.jpg
      title: "Networks for image denoising"
      excerpt: "This session works with convolutional neural networks (CNN) to denoise images. Special emphasis is placed on [FFDnet](https://arxiv.org/abs/1710.04026) as well as on generalization problems and solutions such as Bias free networks, studied in [Mohan et al., Robust and interpretable blind image denoising via bias-free convolutional neural networks, 2020](https://arxiv.org/abs/1906.05478v3).
      
      
      *Image: FFDNet denoising (Paris)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/Restoration/Networks_for_image_denoising.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/Restoration/Networks_for_image_denoising.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
feature_row2:
    - image_path: /images/NotebookImages/Restoration/VA.jpg
      title: "Variational approaches for image restoration"
      excerpt: "In this practical session we address different restoration problems such as inpainting, denoising and deblurring. Several variational approaches are used depending on the conditions of the problem: Tychonov, Total variation L1 and L2 and Wiener.
      
      
      *Image: inpainting (Bordeaux)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/Restoration/Variational_approaches_for_image_restoration.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/Restoration/Variational_approaches_for_image_restoration.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
    - image_path: /images/NotebookImages/Restoration/PnP.jpg
      title: "Plug and Play optimization"
      excerpt: "Plug-and-play (PnP) is a non-convex framework that integrates modern denoising priors into proximal algorithms. This practical session explains and shows inpainting end deblurring experiments using the following PnP algorithms: PnP ADMM, PnP FBS, PnP BBS, PnP BBS2 and PnP BBS3.
      
      
      *Image: deblurring using BBS3 (Camila & Paula)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/Restoration/Plug_and_Play_optimization.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/Restoration/Plug_and_Play_optimization.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
    - image_path: /images/NotebookImages/Restoration/Sampling.jpg
      title: "TV Sampling"
      excerpt: "This practical session explains how to draw samples from different distributions. It uses the Metropolis algorithm, inspired by what is used in [Louchet, C., & Moisan, L. (2008, August). Total variation denoising using posterior expectation, EUSIPCO 2008](https://hal.archives-ouvertes.fr/hal-00258849/file/lm08ok.pdf).
      
      
      *Image: total variation sampling with mask operator (Martina)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/Restoration/Sampling_TV.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/Restoration/Sampling_TV.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
feature_row3:
    - image_path: /images/NotebookImages/Restoration/Sampling_ICE.jpg
      title: "TV-ICE Sampling"
      excerpt: "This session focuses on image denoising using the classical TVL2 model using the algorithm Iterated Conditional Expectation (ICE). It is inspired by the article [Louchet, C.,  Moisan, L., *Total variation denoising using iterated conditional expectation*. In 2014 22nd European Signal Processing Conference (EUSIPCO) (pp. 1592-1596). 2014](https://hal.archives-ouvertes.fr/hal-01214735). 
      
      
      *Image: total variation ICE sampling (Martina)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/Restoration/TVICE.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/Restoration/TVICE.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
    - image_path: /images/NotebookImages/Restoration/Sampling_ULA.jpg
      title: "ULA Sampling"
      excerpt: "This practical session uses ULA (Unadjusted Langevin Algorithm) to sample from distributions. In particular, this practical session shows how to use the algorithm to deblurring an image.


      *Image: total variation ULA sampling for deblurring (Simpson)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/Restoration/ULA_Sampling.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/Restoration/ULA_Sampling.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
---

{% include feature_row id="feature_row1" %}
{% include feature_row id="feature_row2" %}
{% include feature_row id="feature_row3" %}