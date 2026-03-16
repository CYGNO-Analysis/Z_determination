# Z determination
Repository with analysis of z determination

## Main goal
Provide the calibration method and code to estimate the z coordinate of a cluster/signal from camera-only (maybe in future 3D) info. This also helps the deconvolution of the raw data to recover something which has the diffusion contribution subtracted.

Technique based on track deconvolution and machine learning with attention.

We want to answer to 4 questions:
1. How much the results in z improve with a bit of simulation? Simulate data at various energy with known z (uniformly distributed in z)
2. How much angular resolution improves when deconvolving the tracks? (try with and without deconvolution on simulation)
3. What data is required to have this z recognition workflow adapted to any detector?
4. Can ML workflows (Edward Shields') in data driven mode tell us how the GEM smears the track and thus remove it from data? (Only after apply deconvolution and track recognition on only drift dependent diffusion)

## People supervising
Giorgio Dho, Giovanni Mazzitelli

## People on the task
Federico Scamporlino
