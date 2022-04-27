# Contrefactual_Multimodal_Data

Explanation of each folder :

Causality : 
    VGG16_greedy : jupyter notebook code of the greedy algo
    BIG_WINDOW_VGG16_greedy : jupyter notebook code of the greedy algo with Big window

Training model :
    train_VGG16_test_data_augm : code for the training of the classifier of bird species

Preprocessing : 
    DL_img_segmentation : Use of the Basnet model to remove the background
    DL_img_segmentation : code that reduce the size of the dataset

Multimodal_Representation :
    compare_multiple_text_feature_extractors : applied multiple text extraction methods in order to select the best one
    multimodal_representation : apply CCA and other methods to merge multimodal data