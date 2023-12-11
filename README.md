# XAS_featurization
Robust machine learning inference from X-ray absorption near edge spectra through featurization

X-ray absorption spectroscopy (XAS) is a commonly-employed technique for characterizing functional materials. In particular, x-ray absorption near edge spectra (XANES) encodes local coordination and electronic information and machine learning approaches to extract this information is of significant interest. To date, most ML approaches for XANES have primarily focused on using the raw spectral intensities as input, overlooking the potential benefits of incorporating spectral transformations and dimensionality reduction techniques into ML predictions. In this work, we focused on systematically comparing the impact of different featurization methods on the performance of ML models for XAS analysis. We evaluated the classification and regression capabilities of these models on computed datasets and validated their performance on previously unseen experimental datasets. Our analysis revealed an intriguing discovery: the cumulative distribution function (CDF) feature achieves both high prediction accuracy and exceptional transferability. This remarkably robust performance can be attributed to its tolerance to horizontal shifts in spectra, which is crucial when validating models using experimental data. While this work exclusively focuses on XANES analysis, we anticipate that the methodology presented here will hold promise as a versatile asset to the broader spectroscopy community. 

This works is available on [arxiv](https:////arxiv.org/abs/2310.07049).
