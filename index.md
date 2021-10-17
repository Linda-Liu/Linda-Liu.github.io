---
layout: default
---

# News
---
Oct. 2021: This website is online!

---
# Research Projects
---

## Physics-based Learned Design for Fourier DiffuserScope
Eric Markley*, __Fanglin Linda Liu*__, Michael Kellman, Nick Antipa, and Laura Waller

A diffuser in the Fourier space of an imaging system can encode 3D fluorescence intensity information in a single-shot 2D measurement, which is then recovered by a compressed sensing algorithm. Typically, the diffusers used in such systems are either off-the-shelf, heuristically designed, or merit function driven. In this work we use a differentiable forward model of single-shot 3D microscopy in conjunction with an invertible and differentiable reconstruction algorithm, ISTA-Net<sup>+</sup>, to jointly optimize both the diffuser surface shape and the reconstruction parameters.  By choosing a differentiable and invertible reconstruction method, we enable the use of memory-efficient backpropagation to trade off storage with a reasonable increase in compute time, in order to fit an unrolled network containing a large-scale 3D volume into a single GPU's memory. We validate our method on 2D and 3D single-shot imaging, where our learned diffuser demonstrates improved reconstruction quality compared to previous heuristic designs.

[![ICCP2021](/assets/img/ICCP2021.png)](https://youtu.be/MNYIUbEIhEk?t=3932)

---

## Fourier DiffuserScope: Single-shot 3D Microscopy with a diffuser

__Fanglin Linda Liu__, Grace Kuo, Nick Antipa, Laura Waller

[Optics Express 28, 28969 (2020)](https://www.osapublishing.org/oe/fulltext.cfm?uri=oe-28-20-28969&id=439689)

Light field microscopy (LFM) uses a microlens array (MLA) near the sensor plane of a microscope to achieve single-shot 3D imaging of a sample without any moving parts. Unfortunately, the 3D capability of LFM comes with a significant loss of lateral resolution at the focal plane. Placing the MLA near the pupil plane of the microscope, instead of the image plane, can mitigate the artifacts and provide an efficient forward model, at the expense of field-of-view (FOV). Here, we demonstrate improved resolution across a large volume with Fourier DiffuserScope, which uses a diffuser in the pupil plane to encode 3D information, then computationally reconstructs the volume by solving a sparsity-constrained inverse problem. Our diffuser consists of randomly placed microlenses with varying focal lengths; the random positions provide a larger FOV compared to a conventional MLA, and the diverse focal lengths improve the axial depth range. To predict system performance based on diffuser parameters, we for the first time establish a theoretical framework and design guidelines, which are verified by numerical simulations, then build an experimental system that achieves 3 µm lateral and 4 µm axial resolution over a 1000 × 1000 × 280 µm<sup>2</sup> volume. Our diffuser design outperforms the MLA used in LFM, providing more uniform resolution over a larger volume, both laterally and axially. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/Y8SLZr-cwiY?start=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## On chip fluorescence microscopy with a random microlens diffuser

Grace Kuo, __Fanglin Linda Liu__, Kristina Monakhova, Kyrollos Yanny, Ren Ng, Laura Waller

[Optics Express 28, 8384 (2020)](https://www.osapublishing.org/oe/fulltext.cfm?uri=oe-28-6-8384&id=428841)

We present an on-chip, widefield fluorescence microscope, which consists of a diffuser placed a few millimeters away from a traditional image sensor. The diffuser replaces the optics of a microscope, resulting in a compact and easy-to-assemble system with a practical working distance of over 1.5 mm. Furthermore, the diffuser encodes volumetric information, enabling refocusability in post-processing and three-dimensional (3D) imaging of sparse samples from a single acquisition. Reconstruction of images from the raw data requires a precise model of the system, so we introduce a practical calibration scheme and a physics-based forward model to efficiently account for the spatially-varying point spread function (PSF). To improve performance in low-light, we propose a random microlens diffuser, which consists of many small lenslets randomly placed on the mask surface and yields PSFs that are robust to noise. We build an experimental prototype and demonstrate our system on both planar and 3D samples.

<iframe width="560" height="315" src="https://www.youtube.com/embed/AXQ7DiBAu2I?start=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
# Work Experience
---

## Project Silica, Microsoft Research

Cambridge, UK, 12/2020 -- 03/2021

* Modeled in Zemax OpticStudio a polarization microscope and built the microscope in the lab.
* Delivered a new polarization microscope with 30% higher data-reading accuracy, highly praised by the whole team.
* Helped 4 team members take data using the new system to support their research progress.

<iframe width="560" height="315" src="https://www.youtube.com/embed/6CzHsibqpIs?start=2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## LightIC Technologies

Santa Clara, CA, 06/2020 -- 08/2020

* Modeled in Zemax OpticStudio the coupling efficiency from free-space to waveguide.
* Designed a doublet lens and worked with the manufacturer to fabricate and assemble the doublet lens.
* Built a prototype with the manufactured lens within 6 weeks, and achieved 20% higher coupling efficiency.

---
# Community Services
---

## Chinese Graduate and Postdoctoral Scholars Association at UC Berkeley ([CGPSA](https://cgpsa.berkeley.edu))

President, 2018 -- 2019

<img src="/assets/img/cgpsa.jpeg" width="150">

---

## Women in Computer Science and Electrical Engineering ([WICSE](https://inst.eecs.berkeley.edu/~wicse/))

Officer, 2017 -- 2018

<img src="/assets/img/wicse.png" width="150">

---
# Teaching
---

## Berkeley [EE16A](https://eecs16a.org): Designing Informative Devices and Systems

Head Content TA, Spring 2019
TA, Fall 2021

* Led the content team to create weekly course materials and exams for over 800 students.

<img src="/assets/img/eecs16a.png" width="150">

---

## Undergraduate Research Mentor

* Mentored 5 undergrads through Research Experiences for Undergraduates programs.

---
# Skills
---

* **Programming Languages**: MATLAB (5 years), Python (4 years), PyTorch (2 years), TensorFlow (2 years).
* **Software**: Zemax OpticStudio (3 years), SOLIDWORKS (1 year), CAD (1 year).
* **Laboratory skills**: optical system alignment (5 years), lens design (1 year), prototyping.