--- 
layout: splashnew
permalink: /notebooksContrastAndColor/
header:
  overlay_image: /images/headerImages/ContrastAndColor.png
title: "Contrast, color and image statistics"
feature_row1:
    - title: "Radiometry"
      image_path: /images/NotebookImages/ContrastAndColor/Radiometry.jpg  
      excerpt: "Radiometry is a set of techniques for measuring electromagnetic radiation, including visible light. In this practical session we will work with histograms to describe the frequency with which the intensity values (pixels) of an image occur. It also shows how to modify image contrasts using histograms. Finally, Image Quantization techniques are shown, especially useful for displaying images on screen with different color depth.


      *Image: Dithering (Lighthouse)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/ContrastAndColor/TP_Radiometrie.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/ContrastAndColor/TP_Radiometrie.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
    - title: "Color in images"
      image_path: /images/NotebookImages/ContrastAndColor/Color1.jpg  
      excerpt: "In this practical session perceived color spaces as well as different classical color spaces are explored. Techniques are studied to visualize the distribution of colors. In addition, different algorithms are tested for white balance correction in images. Finally, a demosicing algorithm for the reconstruction of color images is studied.


      *Image: White balance algorithm: Shades of gray. (Moscow)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/ContrastAndColor/TP_color.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary" 
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/ContrastAndColor/TP_color.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
    - title: "Amplitude jumps"
      image_path: /images/NotebookImages/ContrastAndColor/AmplitudeJumps.jpg
      excerpt: "The purpose of this practical session is to model the distribution of amplitude jumps in images.


      *Image: Histogram of horizontal amplitude jumps for a variable.*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/ContrastAndColor/Amplitude_jumps.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/ContrastAndColor/Amplitude_jumps.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
feature_row2:
    - title: " Color transfer"
      image_path: /images/NotebookImages/ContrastAndColor/ColorTransfer.jpg 
      excerpt: "The goal of this practical session is to work with different techniques and algorithms that allow to transport the color distribution from one image to another. For this purpose, the optimal transport algorithm Sliced is applied. Regularization methods are studied in order to reduce artifacts that may be generated while the color transfer.


      *Image: Sliced 3D Transport applied to Color Transfer (Renoir painted with Rembrandt colors)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/ContrastAndColor/TP_color_transfer.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary" 
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/ContrastAndColor/TP_color_transfer.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
    - title: "Color transfer with Sinkhorn"
      image_path: /images/NotebookImages/ContrastAndColor/ColorTransferSinkhorn.jpg 
      excerpt: "The goal of this practical session is to work with the Sinkhorn algorithm that allow to transport the color distribution from one image to another. Regularization methods are applied in order to reduce artifacts that may be generated while the color transfer.


      *Image: Sinkhorn algorithm for Color Transfer (Renoir painted with Gauguin colors)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/ContrastAndColor/TP_color_transfer_with_Sinkhorn.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/ContrastAndColor/TP_color_transfer_with_Sinkhorn.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
    - title: "Optimal Transport between Gaussian Mixture Models - Simple experiments"
      image_path: /images/NotebookImages/ContrastAndColor/GMM2D.jpg
      excerpt: "This notebook presents simple experiments using a transportation distance between GMM defined by restricting the set of possible coupling measures to Gaussian mixtures. 


      *Image: Optimal Transport between Gaussian Mixture Models in 2D*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/ContrastAndColor/GMM_OT_introduction.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/ContrastAndColor/GMM_OT_introduction.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
feature_row3:
    - title: "Color transfer with Optimal transport between Gaussian Mixture Models"
      image_path: /images/NotebookImages/ContrastAndColor/ColorTransferOT.jpg
      excerpt: "This notebook illustrates the use of the distance $GW_2$ for color transfer, as described in [Delon, Desolneux, *A Wasserstein-type distance in the space of Gaussian Mixture Models*, 2019.](https://hal.archives-ouvertes.fr/hal-02178204)


      *Image: Color transfer with GMM-OT (Renoir painted with Gauguin colors)*"
      url: "https://colab.research.google.com/github/storimaging/Notebooks/blob/main/ContrastAndColor/GMM_OT_color_transfer.ipynb"
      btn_label: "Open In Colab"
      btn_class: "btn--primary"
      url2: "http://nbviewer.org/github/storimaging/Notebooks/blob/main/ContrastAndColor/GMM_OT_color_transfer.ipynb"
      btn_label2: "Open In nbviewer"
      btn_class2: "btn--primary"
    
---

{% include feature_row id="feature_row1" %}
{% include feature_row id="feature_row2" %}
{% include feature_row id="feature_row3" %}

