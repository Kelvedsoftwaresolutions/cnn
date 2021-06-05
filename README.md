# cnn

* n - input, k - kernel
1. Normal - n*n -> k*k -> [(n-k + 1), (n-k + 1)]
2. Padding (Adding padding to pixel) - n*n -> k*k/p -> [(n - k + 2p + 1), (n - k + 2p + 1)]
3. Strides - n*n -> k*k/s -> [(n-k/s + 1), (n-k/s + 1)]
