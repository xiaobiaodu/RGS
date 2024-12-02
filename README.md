<h2 align="center"> <a href="https://xiaobiaodu.github.io/rgs-project/">RGS: Reflection-aware Gaussian Splatting via Learning Geometry Continuity
for Reflective Objects</a></h2>
<h5 align="center"> If you like our project, please give us a star ⭐ on GitHub for latest update.  </h2>

<h5 align="center">

<p align="center">
  <a href="https://xiaobiaodu.github.io/">Xiaobiao Du</a><sup>123</sup> ·
  <a href="https://wangyida.github.io/">Yida Wang</a><sup>3</sup> ·
  <a href="">Cheng Bi</a><sup>3</sup> ·
  <a href="https://sites.google.com/view/xinyus-homepage/Home">Xin Yu</a><sup>2</sup>
</p>
<p align="center"><sup>1</sup>The University of Technology Sydney · <sup>2</sup>The University of Queensland · <sup>3</sup>Li Auto Inc.</p>
<img src="assets/teaser.png"/>

### <p align="center">[🌐Project Page](https://xiaobiaodu.github.io/rgs-project/) | [🖨️ArXiv](https://arxiv.org/pdf/2410.02103) | [📰Paper](https://arxiv.org/pdf/2410.02103)</p>


## 😮 Highlights
RGS is a state-of-the-art Gaussian-based method for high-quality novel view synthesis of reflective objects.
### 🔥 Three key Contributions 
- We propose a reflection-guided normal regularization based on Total Variation loss and physical constraint, encouraging normal map smoother in neighboring regions and fixing small hollows in surface geometry.
- We propose a stereo depth regularization to prevent collapsed surface geometry in the reflective region. This network enables the reconstruction of accurate geometry and facilitates smooth novel view synthesis.
- We also propose a reflection-guided densification strategy to produce more 3D Gaussian primitives that contribute significantly to the rendering of specular, encouraging the learning of specular patterns.





## 🚩 **Updates**


Welcome to **watch** 👀 this repository for the latest updates.


✅ **[2024.12.2]** : Release [project page](https://xiaobiaodu.github.io/rgs-project/).

**Our code will be released upon the acceptance of this paper.**







[//]: # (## Installation)

[//]: # ()
[//]: # (1. Clone this repo:)

[//]: # ()
[//]: # (```)

[//]: # (git clone ...)

[//]: # (cd RGS)

[//]: # (```)

[//]: # ()
[//]: # (2. Install dependencies)

[//]: # (First, please follow the setup tutorial of vanilla [3DGS]&#40;https://github.com/graphdeco-inria/gaussian-splatting&#41;, and ensure you can run their code. Then, install the following submodules to run our code.)

[//]: # ()
[//]: # (```)

[//]: # (pip install submodules/cubemapencoder)

[//]: # (pip install submodules/diff-gaussian-rasterization_c3)

[//]: # (pip install submodules/diff-gaussian-rasterization_c7)

[//]: # (pip install submodules/simple-knn)

[//]: # (```)

[//]: # (`diff-gaussian-rasterization_c3` and `simple-knn` are identical to the vanilla 3DGS. You can skip them if you have installed them. You just need to replace `diff-gaussian-rasterization_c3` with `diff-gaussian-rasterization` if you have installed it.)

[//]: # ()
[//]: # ()
[//]: # (## Quickstart)

[//]: # ()
[//]: # (#### Public Data)

[//]: # (We evaluate our method on [Shiny Blender Synthetic]&#40;https://storage.googleapis.com/gresearch/refraw360/ref.zip&#41;, [Shiny Blender Real]&#40;https://storage.googleapis.com/gresearch/refraw360/ref_real.zip&#41;, [Glossy Synthetic]&#40;https://liuyuan-pal.github.io/NeRO/&#41; and [NeRF Synthetic dataset]&#40;https://drive.google.com/drive/folders/128yBriW1IG_3NJ5Rp7APSTZsJqdJdfc1&#41;. )

[//]: # ()
[//]: # ()
[//]: # ()
[//]: # (You can create links as follows:)

[//]: # (```)

[//]: # (mkdir data)

[//]: # (ln -s PATH_TO_DATASET data)

[//]: # (```)

[//]: # ()
[//]: # (#### Run)

[//]: # ()
[//]: # ()
[//]: # (```)

[//]: # (sh run_ref_synthetic.sh)

[//]: # (```)

[//]: # ()
[//]: # (### Evaluation)

[//]: # (```)

[//]: # (python eval.py --model_path output/NAME_OF_THE_SCENE)

[//]: # (```)

[//]: # (You will get PSNR/SSIM/LPIPS/FPS results.)

[//]: # (If you need to save image and lighting results, add argument `--save_images`)

[//]: # ()



## ✏️ Citation

If you find our paper and code useful in your research, please consider giving a star :star: and citation :pencil:.


```BibTeX
...
```




