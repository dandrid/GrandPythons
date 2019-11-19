# GrandPythons - Milestone 2

The title of our chosen exercise is **Speech-based emotion recognition**.

## Data Set

We decided to use the **RAVDESS** Data Set.  https://zenodo.org/record/1188976#.XaYUupIzaUk

## Data Preparation

The Data Set is preprocessed in 5 steps. This is done in the **1_prepare_data.ipynb** file. The results of the first three steps are serialized.

1. **STEP 1** trimming the silent data from the audio
2. **STEP 2** enriching the data set by adding noise to the audio data
3. **STEP 3** creating a spectogram from the audio data
4. **STEP 4** split the spectograms into equal time length images
5. **STEP 5** assembling the Data Frame

### Data Set Download

We have published the used Data Set versions on Google Drive

* The original RAVDESS Data Set is published [here](https://drive.google.com/open?id=1WyJsDuxJlUObBCFrNZLAXM2w4-sp0CxN) as **RAVDESS_original.zip**. Use this if you want to run the workflow from the beginning.
* The trimmed RAVDESS Data Set is published [here](https://drive.google.com/open?id=1pFum_YGf2C82HJvMwt0gi8apj6PJLi0s) as **RAVDESS_trimmed.zip**. Use this if you want to run the workflow from the STEP 2.
* The enriched RAVDESS Data Set is published [here](https://drive.google.com/open?id=1LG42oQTSs6HWMLsdqhFKbADA2wi8234_) as **RAVDESS_enriched.zip**. Use this if you want to run the workflow from the STEP 3.
* The spectograms of the RAVDESS Data Set is published [here](https://drive.google.com/open?id=1jDb2GDnapxx-5bhRR4rudVLxd4ajrpF-) as **RAVDESS_spectogram.zip**. Use this if you want to run the workflow from the STEP 4.

## Model Train

The loading of the pre-processed data set and the training ofthe model is done in the **2_build_model.ipynb** file. Use the Data Set published [here](https://drive.google.com/open?id=1a2TRcqj5ySMWwetfU3Zgq4FE-highOKK) to re-run.
