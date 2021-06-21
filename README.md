# CNN-flower-classification
A deep learning model (with CNN algorithms) for flower classification. 

Dataset has 5 types of flowers and about 1000 photos for each type.

Firstly, basic CNN model was defined with 1 convolutional layer and %56 accuracy score was achieved.

And then, another convolutional layer was added (2 conv total) and %59 accuracy score was achieved.

When one more convolutional layer was added (3 conv total),  %62 accuracy score was achieved. 

The same model was used with data augmentation and %70 accuracy score was achieved.

# To improve model performance and prevent overfitting, transfer learning, data augmentation and dropout methods  were used. 

%82 accuracy score was achieved with VGG 16 model,

%84 accuracy score was achieved with VGG 16 model and data augmentation,

%85 accuracy score was achieved with VGG 16 model + data augmentation + 512 units dense layer (previous dense layers had 128),

And %86 accuracy score was achieved with VGG 16 model + data augmentation + 512 units dense layer + dropout layer.

%84 accuracy score was achieved with VGG 19 model + data augmentation + 512 units dense layer.

%89 accuracy score and %0.4 loss (previos models had %1) was achieved with ResNet model + data augmentation + 512 units dense layer. 

%89.4 accuracy score and %0.5 loss was achieved with ResNet model + data augmentation + 512 units dense layer + dropout layer.

# Finally, ResNet model has achieved best performance. Also, Data augmentation, more units in dense layer and dropout layer have improved the performance.
