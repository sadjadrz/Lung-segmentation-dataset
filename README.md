# LungSegDB: Lung Segmentation Dataset

[[Download]](https://drive.google.com/file/d/1EjzpPq0GhpmlMoSUqnJIdukg_QQDJtgq/view?usp=drive_link) [[Results]](https://github.com/sadjadrz/FusionLungNet/tree/main?tab=readme-ov-file#results) [[Codes]](https://github.com/sadjadrz/FusionLungNet)
![image](https://github.com/user-attachments/assets/c1b15a83-6e79-4694-8ce7-fe64a48cccc8)

Automatic lung image segmentation assists doctors in identifying diseases such as lung cancer, COVID-19, and respiratory disorders. However, lung segmentation is challenging due to overlapping features like vascular and bronchial structures, along with pixellevel fusion of brightness, color, and texture.
we introduce LungSegDB, a comprehensive dataset for lung segmentation. We followed a systematic workflow to prepare the datasets, which included downloading the datasets, creating lung masks using any labeling software, conducting an expert review for accurate validation, and finally evaluating the results of the annotation process.

![image](https://github.com/user-attachments/assets/4abab8f2-9a0a-4f40-92e8-b3e8c4991bf0)



Details on the dataset can be found at [ABANet: Attention boundary-aware network for image segmentation](https://doi.org/10.1111/exsy.13625).<br>
If you have questions, or any suggestions to help us improve the dataset, please contact sadjadRezvani@gmail.com.

### Directory Tree

                           
                               
```
                                       ├─/CT_Images/ *.TIF
                                ├─/V1 -│
                                │      ├─/CT_Masks/  *.TIF          
          ├─ /preprocessed data-│
          │                     │      ├─/CT_Images/ *.TIF
          │                     ├─/V2 -│
          │                     │      ├─/CT_Masks/  *.TIF 
          │　
LungSegDB-│　
          │                            ├─/CT_Images/ *.TIF
          │                     ├─/V1 -│
          │                     │      ├─/CT_Masks/  *.TIF          
          ├─ /raw data----------│
          │                     │      ├─/CT_Images/ *.TIF
          │                     ├─/V2 -│
                                │      ├─/CT_Masks/  *.TIF           
```

### Download 
Dataset can be downloaded at [GoogleDrive](https://drive.google.com/file/d/1EjzpPq0GhpmlMoSUqnJIdukg_QQDJtgq/view?usp=drive_link).

MSFD is distributed under the [MIT](https://github.com/sadjadrz/MFSD/blob/main/LICENSE) License


### Citations

Please consider citing our work:

```
@article{rezvaniabanet,
  title={FusionLungNet: Multi-scale Fusion Convolution with Refinement Network for Lung
CT Image Segmentation},
  author={Rezvani, Sadjad and Fateh, Mansoor and Jalali, Yeganeh and Fateh, Amirreza},
  journal={},
  pages={},
  publisher={}
}
```

### Acknowledgements
A special thanks to [Yasin Rezvani](https://github.com/YasinRezvani) for his invaluable assistance in data collection and labeling. Yasin played a crucial role in gathering data from Google and Instagram and preparing it for deep learning model training.

### Changelog 
* 


