# Dataset_Capsule

This GitHub repository contains a image dataset obtained from a video showing the path of a bio-artificial capsule through a Y-shaped micro-pipe.
It is composed of 353 different grayscale images of 768x768 pixels, that are stored in TIFF format. 
The capsule is transparent, consequently a trained model need to learn to detect contour patterns and then filling the inside of the detected contour. The capsule is deformable so the model cannot learn a single shape. 

The raw inputs of the dataset were provided by Benjamin Sévénié and Anne-Virginie Salsac at [Biomechanics and Bioengineering Laboratory (BMBI, UMR CNRS 7338), University of Technology of Compiègne](https://bmbi.utc.fr), and described in Benjamin Sévénié's [PhD thesis](http://www.theses.fr/2016COMP2278).
The targets were provided by a joint work form the [Biocomputing](https://www.cristal.univ-lille.fr/equipes/biocomputing/) and [SIGMA](https://www.cristal.univ-lille.fr/equipes/sigma/) teams of [CRIStAL](https://www.cristal.univ-lille.fr). The delineation was carefully obtained using Bezier curves. Input images were also slightly rotated to that the background is not entirely uniform from a training example to another one. 

Three example input/target pairs are shown below:

<img src="https://user-images.githubusercontent.com/16539991/135630329-6f3d0f27-9962-4dc2-94bb-3e3553bba6d7.png" width="500">
<img src="https://user-images.githubusercontent.com/16539991/135630593-cd4ee5e0-87f3-45b5-81fd-a76f6eca6c83.png" width="500">
<img src="https://user-images.githubusercontent.com/16539991/135630606-3b9ece16-b855-4693-b47a-708a43aa6100.png" width="500">


## How to cite this dataset?
If you use this dataset for your own work, please consider citing it with [this piece of BibTeX](capsule.bib):


```bibtex
@misc{Caps2021,
    title =   {{Capsule: a dataset for the segmentation of a transparent and deformable capsule.}},
    author =  {Benjamin Sévénié and Anne-Virginie Salsac and Arnaud Deleruyelle and Cristian Versari and John Klein},
    year =    {2021},
    url =     {https://github.com/ArnaudDeleruyelle/Dataset_Capsule},
    howpublished = {Online at: \url{https://github.com/ArnaudDeleruyelle/Dataset_Capsule}},
}
```


## License 
[MIT Licensed](https://github.com/ArnaudDeleruyelle/Dataset_Capsule/blob/main/LICENCE) (file [LICENSE](LICENSE)).
