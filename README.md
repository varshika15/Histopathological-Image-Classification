# Histopathological-Image-Classification

Using data augmentation, original dataset and auto-encoded created images are fed to the InceptionV3 and Inception Resnet V2 models respectively. The feature layer derived from both the models are concatenated and further Dense layers are added. The output label is then predicted with the help of sigmoid activation function that is applied on the last layer.
