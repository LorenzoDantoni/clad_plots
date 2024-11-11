**pca_components_all_variances_visualization_resnet**: 
- for each object and for each layer a heatmap visualizes the number of PCA components needed to achieve the specific variance threshold for each patch in the feature map
- STFPM (resnet backbone)

**importance_all_features_resnet**:
- for each object and for each layer a heatmap shows the feature importace computed by PCA for each patch
- for each patch, a single value is extracted by summing all the feature importances of the patch
- STFPM (resnet backbone)

**importance_top1%_features_resnet**:
- for each object and for each layer a heatmap shows the feature importace computed by PCA for each patch
- for each patch, a single value is extracted by summing only the top 1% feature importances of the patch
- STFPM (resnet backbone)


  
