# Using Shape Metrics to Describe 2D Data

Provides the experiments for Lamberti 2022 (https://arxiv.org/abs/2201.11857).  Each zip file has corresponds to a given set of experiments using R. 

## Files

Each experiment has associated Python and R files.  The general framework to reproduce these experiments is as follows:

1. Create the associate data folder structure to save the simulated images. 
2. Run the associated Python script.
3. Run the associated R script. 

### norms.zip 

1. Data folder structure:<br />
    -gauss_den_differ<br />
      --none<br />
      --norm_var.zip<br />
        ---dist1_var<br />
        ---dist2_var<br />
    -gauss_means_differ<br />
      --none<br />
      --data<br />
        ---dist1<br />
        ---dist2<br />
        ---none<br />
    -gauss_mix<br />
      --none<br />
      --mix_gauss_imgs<br />
        ---tad1<br />
        ---tad2<br />
        ---tad3<br />
        ---tad4<br />
    -gauss_vars_differ<br />
      --none<br />
      --norm_den.zip<br />
        ---dist1<br />
        ---dist2<br />
2. While in /guass_dens_differ (assuming that you have unzipped norm_var.zip), run Python script: multi_norm_shape_varying_density.py
3. While in /guass_dens_differ, run R script: multivariate_norms_var.r
4. While in /guass_means_differ, run Python script: multi_norm_shape.py
5. While in /guass_means_differ, run R script: multivariate_norms.r
6. While in /guass_mix, run Python script: .py
7. While in /guass_mix, run R script: tads_tree_class.r
8. While in /guass_vars_differ, run Python script: multi_norm_shape.py
9. While in /guass_vars_differ, run R script: multivariate_norms.r


### qqnorm.zip

1. Data folder structure:<br />
   -none<br />
   -data<br />
     --q1<br />
     --q2<br />
     --q3<br />
     --q4<br />
2. Run Python script: qqnorm_shape.py
3. Run R script: qqnorm_tree_class.r

### mods.zip 

1. Data folder structure:<br />
   -none<br />
   -data<br />
     --mod1<br />
     --mod2<br />
     --mod3<br />
     --mod4<br />
2. Run Python script: mods_shape.py
3. Run R script: mods_tree_class.r

### ols_uneq_var.zip

1. Data folder structure:<br />
   -none<br />
   -data<br />
     --mod1<br />
     --mod2<br />
     --mod3<br />
     --mod4<br />
2. Run Python script: uneq_var_shape.py
3. Run R script: mods_tree_class.r

## System Information

Below is the associated information regarding the computer used to run these experiments:

Computer: MacBook Pro (Retina, 13-inch, Early 2015)<br />
Processor: 2.7 GHz Dual-Core Intel Core i5<br />
Memory: 8 GB 1867 MHz DDR3<br />

### Python Information

Below is a list of the installed version of the Python libraries (as of February 2022):

absl-py==1.0.0<br />
aiohttp==3.6.2<br />
aiohttp-json-rpc==0.13.1<br />
aiosqlite==0.15.0<br />
appdirs==1.4.4<br />
apsw-wheels==3.30.1.post3<br />
astunparse==1.6.3<br />
async-timeout==3.0.1<br />
asyncpg==0.20.1<br />
attrs==19.3.0<br />
Babel==2.8.0<br />
beautifulsoup4==4.9.3<br />
bs4==0.0.1<br />
cachetools==4.2.4<br />
certifi==2021.10.8<br />
cffi==1.15.0<br />
chardet==3.0.4<br />
charset-normalizer==2.0.7<br />
chromedriver-binary==93.0.4577.15.0<br />
click==7.1.2<br />
colorama==0.4.3<br />
contextlib2==0.6.0.post1<br />
cycler==0.10.0<br />
decorator==4.4.2<br />
discord.py==1.4.1<br />
flatbuffers==2.0<br />
fuzzywuzzy==0.18.0<br />
gast==0.4.0<br />
google-auth==2.3.3<br />
google-auth-oauthlib==0.4.6<br />
google-pasta==0.2.0<br />
grpcio==1.41.1<br />
h5py==3.5.0<br />
idna==2.10<br />
imagecodecs==2021.6.8<br />
imageio==2.9.0<br />
Jinja2==3.0.3<br />
joblib==1.0.1<br />
keras==2.7.0<br />
Keras-Preprocessing==1.1.2<br />
kiwisolver==1.3.1<br />
kneed==0.7.0<br />
libclang==12.0.0<br />
Markdown==3.2.2<br />
MarkupSafe==2.0.1<br />
matplotlib==3.4.2<br />
multidict==4.7.6<br />
networkx==2.5.1<br />
numpy==1.20.3<br />
oauthlib==3.1.1<br />
opt-einsum==3.3.0<br />
pandas==1.2.4<br />
Pillow==8.2.0<br />
protobuf==3.19.1<br />
pyasn1==0.4.8<br />
pyasn1-modules==0.2.8<br />
pycparser==2.21<br />
pyparsing==2.4.7<br />
PyQt3D==5.15.5<br />
PyQt5==5.15.6<br />
PyQt5-sip==12.9.0<br />
PyQtChart==5.15.5<br />
PyQtDataVisualization==5.15.5<br />
PyQtNetworkAuth==5.15.5<br />
PyQtPurchasing==5.15.5<br />
PyQtWebEngine==5.15.5<br />
python-dateutil==2.8.1<br />
python-Levenshtein-wheels==0.13.1<br />
pytz==2020.1<br />
pytz-deprecation-shim==0.1.0.post0<br />
PyWavelets==1.1.1<br />
PyYAML==5.3.1<br />
QScintilla==2.13.1<br />
Red-DiscordBot==3.4.0<br />
Red-Lavalink==0.6.0<br />
requests==2.26.0<br />
requests-oauthlib==1.3.0<br />
rpy2==3.4.5<br />
rsa==4.7.2<br />
schema==0.7.2<br />
scikit-image==0.18.2<br />
scikit-learn==0.24.2<br />
scipy==1.6.3<br />
selenium==3.141.0<br />
six==1.16.0<br />
sklearn==0.0<br />
soupsieve==2.2.1<br />
TBB==0.2<br />
tensorboard==2.7.0<br />
tensorboard-data-server==0.6.1<br />
tensorboard-plugin-wit==1.8.0<br />
tensorflow==2.7.0<br />
tensorflow-estimator==2.7.0<br />
tensorflow-io-gcs-filesystem==0.22.0<br />
termcolor==1.1.0<br />
threadpoolctl==2.1.0<br />
tifffile==2021.7.2<br />
tqdm==4.48.0<br />
typing-extensions==3.7.4.2<br />
tzdata==2021.5<br />
tzlocal==4.1<br />
urllib3==1.26.6<br />
uvloop==0.14.0<br />
Werkzeug==2.0.2<br />
wrapt==1.13.3<br />
yarl==1.5.1<br />


### R Information

Here is the system info associated with the R sessions:

R version 4.1.0 (2021-05-18)<br />
Platform: x86_64-apple-darwin17.0 (64-bit)<br />
Running under: macOS Big Sur 10.16<br />

Matrix products: default<br />
BLAS:   /Library/Frameworks/R.framework/Versions/4.1/Resources/lib/libRblas.dylib<br />
LAPACK: /Library/Frameworks/R.framework/Versions/4.1/Resources/lib/libRlapack.dylib<br />

locale:<br />
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8<br />

attached base packages:<br />
[1] stats     graphics  grDevices utils     datasets  methods   base     <br />

other attached packages:<br />
[1] randomForest_4.6-14 caret_6.0-88        ggplot2_3.3.5      <br />
[4] lattice_0.20-44     e1071_1.7-7         xtable_1.8-4       <br />

loaded via a namespace (and not attached):<br />
 [1] Rcpp_1.0.6           pillar_1.6.1         compiler_4.1.0      <br />
 [4] gower_0.2.2          plyr_1.8.6           tools_4.1.0         <br />
 [7] class_7.3-19         iterators_1.0.13     rpart_4.1-15        <br />
[10] ipred_0.9-11         lubridate_1.7.10     lifecycle_1.0.0     <br />
[13] tibble_3.1.2         gtable_0.3.0         nlme_3.1-152        <br />
[16] pkgconfig_2.0.3      rlang_0.4.11         Matrix_1.3-3        <br />
[19] foreach_1.5.1        prodlim_2019.11.13   stringr_1.4.0       <br />
[22] withr_2.4.2          dplyr_1.0.6          pROC_1.17.0.1       <br />
[25] generics_0.1.0       vctrs_0.3.8          recipes_0.1.16      <br />
[28] stats4_4.1.0         nnet_7.3-16          grid_4.1.0          <br />
[31] tidyselect_1.1.1     data.table_1.14.0    glue_1.4.2          <br />
[34] R6_2.5.0             fansi_0.5.0          survival_3.2-11     <br />
[37] lava_1.6.9           reshape2_1.4.4       purrr_0.3.4         <br />
[40] magrittr_2.0.1       ModelMetrics_1.2.2.2 splines_4.1.0       <br />
[43] MASS_7.3-54          scales_1.1.1         codetools_0.2-18    <br />
[46] ellipsis_0.3.2       timeDate_3043.102    colorspace_2.0-1    <br />
[49] utf8_1.2.1           stringi_1.6.2        proxy_0.4-25        <br />
[52] munsell_0.5.0        crayon_1.4.1        <br />

