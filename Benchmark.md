Benchmarking the different models on Caltech256. (Rounded to nearest integer)

| Algorithm | Number of features indexed | Time to search 1 image (ms) | Time to search 1000 images (ms)  | Time to index (ms)    |
|-------------|----------------------------|------------------------|--------------|-------------|
| Brute force   | 2048 |  213   | 2970       | 123   | 
| k-d tree      | 2048 |  120   | 113000     |    14|
| Ball tree     | 2048 |  100   | 99000      |   12  |
| PCA + brute force | 100 | 6.61  | 574  |  151   |
| PCA + k-d tree | 100 |  6.84  | 5870    |  523  |
| PCA + ball tree | 100 | 5.73  |  4810  |   416  |
