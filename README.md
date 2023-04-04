# logo_image-search_image-similary
The easiest pipe line for image search

## Augmentation
- Rotate image

## Preprocessing
- Resize with ImageOps to keep aspect ration
- padding image

## Model
- Sentence Similarity to extract feature, https://huggingface.co/sentence-transformers/clip-ViT-B-32
- Annoy Index for cosine similarity
