# Fashion-MNIST
What is Fashion MNIST?
Fashion MNIST is a dataset of 60,000 training images and 10,000 test images, each showing a grayscale image of a clothing item (like T-shirt, shoe, bag, etc.).

It was created by Zalando, an online fashion retailer, and released as a better alternative to the original MNIST handwritten digit dataset.

🎯 Why Fashion MNIST?
The original MNIST (digits 0–9) is too easy for modern ML models.

Fashion MNIST is more challenging, realistic, and good for benchmarking image classification models.

Still has the same format (size, structure) as MNIST — so you can easily swap it in your code.

📦 Dataset Structure
Image details:
Size: 28 x 28 pixels (same as MNIST)

Color: Grayscale (1 channel only)

Pixel values: Range from 0 to 255

0 = black (background)

255 = white (clothing foreground)

Number of samples:
Dataset Part	Number of Samples
Training set	60,000 images
Test set	10,000 images

Number of classes: 10
Label	Class Name
0	T-shirt/top
1	Trouser
2	Pullover
3	Dress
4	Coat
5	Sandal
6	Shirt
7	Sneaker
8	Bag
9	Ankle boot
