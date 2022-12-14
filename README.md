
# 👐OpenDatasets

This is the place to find 💻 Machine Learning Datasets for training,
testing and validation and all thing ML with direct ⬇️ Download Links.

This repo is updated regularly with previous and recently available open source and
free datasets made available by various origanizations.

➡️Please follow the standard format while uploading your datasets.
➡️Please read official guide/paper and licensing before using any dataset regarding copyright and IP.
# 👦Computer Vision
## 1.DigiFace1M
![DigiFace1M](https://microsoft.github.io/DigiFace1M/img/accessories_id2.jpg "DigiFace1M")

The DigiFace-1M dataset is a collection of over one million diverse synthetic face images for face recognition.
The dataset contains:

720K images with 10K identities (72 images per identity). For each identity, 4 different sets of accessories are sampled and 18 images are rendered for each set.
500K images with 100K identities (5 images per identity). For each identity, only one set of accessories is sampled.
The DigiFace-1M dataset can be used for non-commercial research, and is licensed under the license found in LICENSE.

🔗Source https://microsoft.github.io/DigiFace1M/

⬇️Available here
https://github.com/microsoft/DigiFace1M

## 2.Wider Face
![WiderFace](https://res.cloudinary.com/dmzhcquzz/image/upload/v1670508878/intro1_bmwbuc.jpg "WiderFace")

WIDER FACE dataset is a face detection benchmark dataset, of which images are selected from the publicly available WIDER dataset. We choose 32,203 images and label 393,703 faces with a high degree of variability in scale, pose and occlusion as depicted in the sample images. WIDER FACE dataset is organized based on 61 event classes. For each event class, we randomly select 40%/10%/50% data as training, validation and testing sets. We adopt the same evaluation metric employed in the PASCAL VOC dataset. Similar to MALF and Caltech datasets, we do not release bounding box ground truth for the test images. Users are required to submit final prediction files, which we shall proceed to evaluate.

🔗Source https://shuoyang1213.me/WIDERFACE/

⬇️Available https://huggingface.co/datasets/wider_face/blob/main/data/WIDER_train.zip

## 3.Cityscapes Dataset
![Cityscapes](https://www.cityscapes-dataset.com/wordpress/wp-content/uploads/2015/07/stuttgart02-2040x500.png "Cityscape")

The Cityscapes Dataset focuses on semantic understanding of urban street scenes. In the following, we give an overview on the design choices that were made to target the dataset’s focus.
Labeled foreground objects must never have holes, i.e. if there is some background visible ‘through’ some foreground object, it is considered to be part of the foreground. This also applies to regions that are highly mixed with two or more classes: they are labeled with the foreground class. Examples: tree leaves in front of house or sky (everything tree), transparent car windows (everything car).

🔗Source https://www.cityscapes-dataset.com/

⬇️Available https://www.cityscapes-dataset.com/login/

## 4.Open Images Dataset V6

![Open Images](https://storage.googleapis.com/openimages/web/images/oid_thumbnail.png "Cityscape")

Open Images is a dataset of ~9M images annotated with image-level labels, object bounding boxes, object segmentation masks, visual relationships, and localized narratives:

It contains a total of 16M bounding boxes for 600 object classes on 1.9M images, making it the largest existing dataset with object location annotations. The boxes have been largely manually drawn by professional annotators to ensure accuracy and consistency. The images are very diverse and often contain complex scenes with several objects (8.3 per image on average).
Open Images also offers visual relationship annotations, indicating pairs of objects in particular relations (e.g. "woman playing guitar", "beer on table"), object properties (e.g. "table is wooden"), and human actions (e.g. "woman is jumping"). In total it has 3.3M annotations from 1,466 distinct relationship triplets.
In V5 we added segmentation masks for 2.8M object instances in 350 classes. Segmentation masks mark the outline of objects, which characterizes their spatial extent to a much higher level of detail.
In V6 we added 675k localized narratives: multimodal descriptions of images consisting of synchronized voice, text, and mouse traces over the objects being described. (Note we originally launched localized narratives only on train in V6, but since July 2020 we also have validation and test covered.)
Finally, the dataset is annotated with 59.9M image-level labels spanning 19,957 classes.

🔗Source https://storage.googleapis.com/openimages/web/factsfigures.html

⬇️Available https://storage.googleapis.com/openimages/web/download_v4.html
# 🈚Natural Language Processing
## 1.IMDB Movie Review Sentiment Classification

![Sentiment](https://res.cloudinary.com/dmzhcquzz/image/upload/v1670510524/imgonline-com-ua-twotoone-IqmeHa1xHPIxL_plbaby.jpg "sentiment analysis")

This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. There is additional unlabeled data for use as well. Raw text and already processed bag of words formats are provided.

🔗Source https://ai.stanford.edu/~amaas/data/sentiment/

⬇️Available https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz

# ⌚Time Series 


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

