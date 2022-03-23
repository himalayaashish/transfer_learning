# transfer_learning

#### We are using the InceptionV3 model.

    Since we're making use of transfer learning, we'll load the pre-trained weights of the model.
    we'll also freeze the existing layers so that they aren't trained on your downstream task with the cats and dogs data.
    we'll also get a reference to the last layer, 'mixed7' because we'll add some layers after this last layer.
