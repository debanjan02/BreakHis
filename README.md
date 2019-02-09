# BreakHis
The Breast Cancer Histopathological Image Classification (BreakHis) is  composed of 9,109 microscopic images of breast tumor tissue collected from 82 patients using different magnifying factors (40X, 100X, 200X, and 400X).  To date, it contains 2,480  benign and 5,429 malignant samples (700X460 pixels, 3-channel RGB, 8-bit depth in each channel, PNG format). This database has been built in collaboration with the P&D Laboratory  – Pathological Anatomy and Cytopathology, Parana, Brazil.
The benign breast tissues can be classified into 4 classes adenosis, fibroadenoma, plyllodes tumor, tubular adenoma and the malignant tissues can be classified into ductal carcinoma, lobular carcinoma, mucinous carcinoma, papillary carcinoma.
The aim is to classify all the images into right class and improve prediction accuracy.
The raw folder contains the notebooks where all images are used with out any pre processing
The k_means folder contains notebooks where k_means clustering is used on the images before feeding into cnn models
The laplacian_pyramid folder contains nootbooks where laplacian pyramid is applied on the images and fed to the cnn models
