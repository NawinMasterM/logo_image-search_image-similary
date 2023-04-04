# logo_image-search_image-similary
The easiest pipe line for image search

## Augmentation
- Rotate image

## Preprocessing
- Resize with ImageOps to keep aspect ration
- padding image

## Model
- Sentence Similarity to extract feature, [![facebook](https://cloud.githubusercontent.com/assets/17016297/18839836/0a06deb4-83d2-11e6-8078-1d0974af0f63.png)][3]
- Annoy Index for cosine similarity
