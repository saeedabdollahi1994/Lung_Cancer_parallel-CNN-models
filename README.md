# Lung_Cancer_parallel-CNN-models
I work on a lung ct-scan dataset which has 2 classes(Normal and Cancer). I consider using Local Binary Patter(LBP) features in a parallel CNN model.In one side of my parallel network I used LBP features as input of my cnn and in another side of my parallel cnn model I used main pixels if each image as input.After some steps in two cnn models I've added the sum of the both feature maps together and aagain I have some steps in the last cnn model and then I have FC layers at the end of my lass cnn.
