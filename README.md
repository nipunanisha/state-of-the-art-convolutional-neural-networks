# state-of-the-art-convolutional-neural-networks
I have implemented and evaluated two types of convolutional neural networks (CNNs): a custom-built CNN model and a fine-tuned pre-trained DenseNet121 model, to classify images in the Jute_Pest_Dataset .
Steps that have Followed:

    Dataset Preparation:
        The dataset was split into training, validation, and testing sets for robust evaluation.

    Custom Model Development:
        Designed a custom CNN with multiple convolutional, activation and pooling layers followed by fully connected layers.
        Trained the model on the training set  validated it on the validation set and evaluated its accuracy and loss.

    Fine-tuning Pre-trained DenseNet121:
        Loaded DenseNet121 a state-of-the-art pre-trained model with its weights initialized from ImageNet.
        Modified the output layer to match the number of classes in the dataset.
        Fine-tuned the DenseNet121 model on the dataset.

    Training and Evaluation:
        Both models were trained using the same dataset splits, with metrics like training and validation loss recorded for each epoch.
        The models were evaluated on the test set with the fine-tuned DenseNet121 achieving higher accuracy than the custom CNN.

    Comparison:
        Compared the test accuracies of both models showing the pre-trained DenseNet121 outperformed the custom CNN.
        Highlighted the trade-offs, advantages and limitations of using a pre-trained model versus a custom model.

Key Insights:

    The fine-tuned DenseNet121 model leveraged transfer learning to achieve better performance in less time compared to the custom CNN.
    While the custom CNN provided flexibility  the DenseNet121 model demonstrated the benefits of pre-training on large datasets for generalization.

This process highlights the importance of transfer learning and pre-trained models in achieving high accuracy, particularly when dealing with small or medium-sized datasets
