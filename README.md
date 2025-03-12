# Data_Science_RAPIDS_and_more


- Deploy the tutorial Jupyter Notebook [ECG outlier detection](ECG_outlier_detection.ipynb) on a cloud instance through [**NVIDIA Brev**](https://developer.nvidia.com/brev).
    - **Creat a Brev Account** if you haven't already. Click the “Create an account” button in the top right corner of the Brev Console [console.brev.dev](https://console.brev.dev/org/org-2tcmRZuGMBx9Wlh2bxmuIdGb6UN/environments).
    - Brev Launchable links for 
        - running on an A100 instance https://console.brev.dev/launchable/deploy?launchableID=env-2uB4YGj1Vwn5uMHu3FSimBDPw1C
        - running on a T4 intance https://console.brev.dev/launchable/deploy?launchableID=env-2uBDn54lZW5dSi9iS3yB9FsCsSy

- The tutorial Jupyter Noteboook [ECG outlier detection](ECG_outlier_detection.ipynb) was slightly adapted from the [original one](https://gist.github.com/gravitino/0fd27d841c37cc25fe2032eafdc8feb2). The primary modifications are in the arguments passed to the plotting APIs in RAPIDS cuxfilter, such as line and scatter, due to API changes across different versions of cuxfilter. And here's a [variant version](https://github.com/nvahmadi/NVIDIA_IKIM_Workshop/blob/main/exercise4_zerocopy/interoperability_zerocopy.ipynb) used at another workshop (including code for plotting heartbeats sampled from latent space, link to a cheat sheet for data converting between frameworks, etc.). 

- [Slide deck](RAPIDSandMore_2025Mar.pdf) for presentation "Accelerated data science in medicine with CuPy, RAPIDS & numba".