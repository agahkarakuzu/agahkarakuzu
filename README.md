### Agah Karakuzu | Biomedical Engineer, Ph.D. 

![](https://img.shields.io/badge/MRI%20Physics-8A2BE2) ![](https://img.shields.io/badge/Medical%20Imaging-33efff) ![](https://img.shields.io/badge/qMRI%20Metrology-e20c4e) ![](https://img.shields.io/badge/Open–source%20Software-ff5d33) ![](https://img.shields.io/badge/Data%20Standards-3389ff) ![](https://img.shields.io/badge/Reproducible%20Science-10c34e) ![](https://img.shields.io/badge/Workflows-c31084) ![](https://img.shields.io/badge/Biomechanics-cfe20c)

I am a Postdoctoral Research Associate at [NeuroPoly Lab](https://neuro.polymtl.ca) at [Polytechnique Montreal](https://www.polymtl.ca/) and a Junior Fellow of the [ISMRM](https://ismrm.org). I have a background in MRI physics, software development, biomedical applications of signal theory, and musculoskeletal biomechanics. 

My current research focuses on developing end-to-end measurement workflows for advanced quantitative MRI (qMRI) applications in neuroimaging, including multiparametric mapping and biophysics-driven microstructural imaging. _My primary motivation is to elevate qMRI to a metrological standard, enabling the quantification of measurement uncertainty within a reproducible multi-vendor framework._ This rigorous aim necessitates addressing the issue of reproducibility through a multistep process, with each following research objective contributing to a comprehensive solution:

1. **Standardized MRI acqusitions – Hardware Integration** 

Multicenter MRI data becomes vulnerable to overfitting when the variability caused by differences between scanners is captured by (deep learning, biophysical, or signal representation) models.

<details>
  <summary>See further context</summary>
  <i>Clinical MRI scanners commonly used in research are not designed as precise measurement devices. However, it is possible to relate raw MRI signals to specific physical properties by estimating numerical parameters from a set of MR images. Since such "quantitative" approach is not the intended use of commercially available scanners, relying on vendor-provided acquisition software (i.e., pulse sequences) can significantly compromise the reliability of these measurements, undermining the clinical value of imaging biomarkers.</i>
</details>

Vendor-neutral pulse sequence development is an emerging open-source approach that offers an alternative to relying on proprietary vendor-native sequences and acquisition controllers. I am interested in applying this approach to standardize acquisitions for various MRI applications (primarily qMRI) with the goal of minimizing non-biological variability at the signal source across scanners from different vendors (e.g., Siemens, GE, Philips, and Canon).

I have experience developing vendor-neutral sequences using both [RTHawk](https://vista.ai/products/research-rthawk/) (JavaScript) and [Pulseq](https://pulseq.github.io) (MATLAB, Python) platforms.

 

* [Relevant article in MRM](https://doi.org/10.1002/mrm.29292) 
    * **Significance:** First empirical evidence supporting the use of vendor-neutral acquisitions to reduce measurement variability across scanners from different vendors.
* GitHub Repositories
    * ![](https://img.shields.io/badge/-e20c4e?&logo=javascript&logoColor=white) [Magnetization transfer and T1 mapping sequence](https://github.com/qmrlab/mt_sat)
    * ![](https://img.shields.io/badge/-e20c4e?&logo=javascript&logoColor=white) [AFI B1 mapping sequence](https://github.com/qmrlab/b1_afi) 
    * ![](https://img.shields.io/badge/-e20c4e?&logo=javascript&logoColor=white) [PHYSICAL calibration sequence](https://github.com/qmrlab/physical)
    * ![](https://img.shields.io/badge/-e20c4e?&logo=octave&logoColor=white) [MP2RAGE pulseq](https://github.com/agahkarakuzu/pulseq-mp2rage)
* Other Resources
    * [Interactive publication with live compute](https://qmrlab.org/VENUS/)
    * [Dataset](https://osf.io/5n3cu/) 
  








3. 

[quantitative MRI (qMRI) applications under one umbrella](https://qmrlab.org) through [data standardization](https://bids-specification.readthedocs.io/), [vendor-neutral acquisitions](https://github.com/qmrlab/pulse_sequences), [fully transparent & reproducible workflows](https://github.com/qmrlab/qmrflow) and community building. To achieve this, I gained experience in: 

* Container-mediated and data driven Nextflow pipelines
* Open-source image reconstruction
* Python/MATLAB/C++
  
I am the lead developer of https://neurolibre.org, an open-source platform for publishing reproducible preprints written in [MyST Markdown](https://mystmd.org/) and [Jupyter Book](https://jupyterbook.org/en/stable/intro.html). It is quite an involved project which helped me gain development experience with the following tools: 
* Kubernetes on baremetal (to host BinderHub)
* Ruby on Rails (OpenJournals editorial manager) 
* OpenStack & OpenNebula
* Terraform
* Flask/Celery/NGINX based full-stack server
* GitHub actions development
* Academic publishing workflows  


For more information re publications, talks, awards: https://agahkarakuzu.github.io 


[Google Scholar](https://scholar.google.ca/citations?user=tVvzWVMAAAAJ&hl=en&oi=ao) 
[ResearchGate](https://www.researchgate.net/profile/Agah-Karakuzu)
