# NUS-WIDE Dataset for Deep Hashing

---

### Description

This repo aims to make the **NUS-WIDE dataset** (preprocessed for deep hashing by [`thuml`](https://github.com/thuml)) pullable via `git clone` instead of downloading via Google Drive or other cloud storage platforms. 

By using Git, the dataset is more usable with notebook platform such as Colab or Kaggle while also making it easier to track changes. The data in this repo is extracted from (hence identical to) `thuml`'s repo: https://github.com/thuml/HashNet/tree/master/pytorch. Thanks `thuml` for their amazing work!

### Usage:
- Clone the repo (~ 5GB):
```
git clone https://github.com/nghia-ndx/deephash-nus-wide
```

- Change into `deephash-nus-wide` directory
```
cd deephash-nus-wide
```

- Extract the archives containing images to the `images/` folder
```
unzip "images/*.zip" -d "images"
```

### Note
- Number of images: 223496
- Classes: 81 (one-hot encoded label)
- DB size: 218491
- Train size: 10000
- Test size: 5000
