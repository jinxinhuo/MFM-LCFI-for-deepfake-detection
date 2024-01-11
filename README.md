# MFM-LCFI-for-deepfake-detection
The implementation of Multiple Feature Mining Based on Local Correlation and Frequency Information for Face Forgery Detection, the code can be fond at https://github.com/turlydark/MFM-LCFI
 
This is the implementation of the article, Multiple Feature Mining Based on Local Correlation and Frequency Information for Face Forgery Detection. Causing the upload limitation of github(just 25MB), we do not upload the pre-trained model pkl file, but you can train the model by yourself with train.py file at the root path, and evaluate the accuracy and auc score with test.py file. The training datasets are FF++ c23 and c40, the testing datasets are FF++ and Celeb-DF(v2) for cross-dataset scenario. By the way, we provide the baseline model xception and efficient-net b4, and other useful tool at the root path. The abstract is below.


Abstract
As facial image manipulation techniques developed, deepfake detection attracted extensive attentions. Although re- searchers have made remarkable progresses in deepfake detection recently, which is still suffering from two limitations: a) current detectors achieve high accuracy in the high-quality videos and images, but it is hard to capture local and subtle artifacts in the low-quality and high-compression media; b) few of deeepfake detection methods gain satisfying performance under cross- database scenario, because detector overfit to specific color textures producing by same manipulation algorithm. Inspired the above issues, this paper proposes a novel framework fusing local related features and frequency information to mine the forgery patterns. Firstly, we design multi-feature enhancement module, which amplifies implicit local discrepancies and capture spatial correlation from three shallow feature layers and high- level semantic layer guided by attention maps. Secondly, dual frequency decomposition module is proposed for disassembling high-frequency and low-frequency features, the forgery artifacts are exposed after dual cross attention block processing in the frequency spectrum. Features from the two streams are fused to the classification for the final result. Comprehensive experiments demonstrate the superior performance of our proposed approach in the low-quality benchmark database and cross-dataset sce- nario.
