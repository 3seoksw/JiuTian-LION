# Preparing the datasets

LION requires various datasets for training and inference.
The following is the required datasets as suggested from the [original repository](https://github.com/JiuTian-VL/JiuTian-LION).

## To-Do List

- [ ] [LION Train data](https://huggingface.co/datasets/daybreaksly/LION-data-train)
- [ ] [OCR-VQA](https://drive.google.com/drive/folders/1_GYPY5UkUy7HIcR0zq3ZCFgeZN7BAfm_)
  - [Hugging Face](https://huggingface.co/datasets/howard-hou/OCR-VQA)
- [ ] [coco-2014](https://www.kaggle.com/datasets/jeffaudi/coco-2014-dataset-for-yolov3)
  - [Hugging Face](https://huggingface.co/datasets/visual-layer/coco-2014-vl-enriched)
- [ ] [coco-2017](https://www.kaggle.com/datasets/awsaf49/coco-2017-dataset)
  - [Hugging Face](https://huggingface.co/datasets/rafaelpadilla/coco2017)
- [ ] [okvqa-2014](https://okvqa.allenai.org/download.html)
  - [Hugging Face](https://huggingface.co/datasets/HuggingFaceM4/A-OKVQA)
- [ ] [textcaps](https://textvqa.org/textcaps/dataset/)
  - [Hugging Face](https://huggingface.co/datasets/HuggingFaceM4/TextCaps)
- [ ] [vqav2-2014](https://visualqa.org/download.html)
  - [Hugging Face](https://huggingface.co/datasets/HuggingFaceM4/VQAv2)
- [ ] [visual_genome](https://homes.cs.washington.edu/~ranjay/visualgenome/api.html)
  - [Hugging Face](https://huggingface.co/datasets/ranjaykrishna/visual_genome)

## Dataset Directory Tree

```tree
/path/to/data/images/
├── OCR-VQA/images
├── coco/images/train2014
├── coco_2017/train2017
├── okvqa/images/train/train2014
├── textcaps/images/train_images
├── vqav2/images/train2014
├── visual_genome/VG_100K
└── visual_genome/VG_100K_2
```

## Downloading Script

- [ ] bash script
- [ ] python script
