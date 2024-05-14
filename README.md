# ObjectLocalization
In this project, I tried to do localization task in Image 2D. 

The folder "src" contains the code for the whole process. It goes from just detecting white box in black background, to detecting pokemon on black background and "real" background, then the final is for detecting different objects (flipped and at different sizes) and localizing them, in real background.

To get data for this project, I used 3 pokemons along with 10 background images, they will be chosen randomly to generate new data during training process.

## Evaluation
At the end, I got the loss around 0.61 and stops to train due to limited hardware resources. Despite the quite high loss score, I saw that the model still works well to localize and detect class of objects. It also did well in detecting there is no object in the images. 
