# Open-MMLab cocoapi
In this repo, we merged COCO and LVIS API into one repo.

For better compatability with Open-MMLab projects, we fork from original
repo and remove some legacy code.
Also we unify the api of COCO and LVIS, since they share similar functions.

Notes:
* We add snack case aliases for functions of [COCO](pycocotools/coco.py).
* The the package version requirement of `lvis-api` is lifted.
* The major version of `cocoapi` and `lvis-api` in this repo is offseted by 10.
  Namely, `cocoapi@2.0.0->cocoapi@12.0.0`, `lvis-api@0.5.2->lvis-api@10.5.2`.

# Installation
Currently, you could install by run
```
# Install cocoapi
pip install "git+https://github.com/open-mmlab/cocoapi.git#subdirectory=pycocotools"
# Install lvis-api
pip install "git+https://github.com/open-mmlab/cocoapi.git#subdirectory=lvis"
```

# Reference
* [cocoapi](https://github.com/cocodataset/cocoapi) of [COCO dataset](http://cocodataset.org/).
* [lvis-api](https://github.com/lvis-dataset/lvis-api) of [LVIS dataset](http://lvisdataset.org).
