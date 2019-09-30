# Sign Language Translation

Hearing impaired people have to tackle a lot of challenges. The mode of communication followed by them is sign language. While it is an effective means of communication for the deaf, people with hearing ability do not know the sign language. So this model aims translate sign language to text. The model uses CNN with transfer learning. 

## Dataset

Dataset consists of images of 29 classes (26 alphabets,one for space, one for delete and one for nothing). Each class consists of 3000 images out of which 2200 were chosen for training, 400 each for validation and testing.
Dataset link: https://github.com/paddy-03/SignDataset

## Workflow

- Loading the images via Image Datagenerator
- Extracting features from  the images using pre-trained VGG-16 model
- Adding custom dense layers to predict the class of the image
- Testing the performance using various metrics

