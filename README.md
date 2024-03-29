- Daniel He
- Zena Chang

## Abstract

The idea of collaborating with or emulating the masters has been a dream. Of course, not everyone has the opportunity to do so. Even more so when ones favorite artist has passed. It is possible to learn an artist’s style to perform a manual style transfer, but this requires a great deal of practice and dedication. Fortunately, Cycle GAN makes such a dream reachable. Inspired by the collaborations like those done between Dali and Disney, called Destino, we have decided to do a collaboration with Dali by using Cycle GAN on our own body of work. Using this method, we hope to perform a true style transfer, where one artist provides the subject or content and another adds their stylized artistic execution.

## Model/Data

- The network model shown in the paper Unpaired Image-to-Image Translation using Cycle Consistent Adversarial Networks is used for the true style transfer. To learn the meaningful mapping between images in our sketchbook and Dali’s body of work, a generator network and a discriminator network are trained jointly on the basis of the fact that the generator learns the way to generate more likely accepted images by the discriminator while the discriminator’s learning to distinguish the original and generated images.

- The data used a collection of Dali's artwork and images from our sketchbook. The images selected from the sketchbook were chosen based on similar features. Dali's artwork was unfiltered to ensure a complete style transfer.

## Code

- Jupyter notebook: DanToDali.ipynb : this is the modified Cycle GAN code. Here the file path was changed to use our dataset, which are included in the folders in this github. In addition the main training loop was modified to save every epoch so that videos can be generated using the saved output images.

## Results

- The results are discussed in detail within the report. Overall, the results did not fully realize our artistic vision, but still were interesting. 

## Technical Notes

- The jupyter notbook can be run on datahub. Make sure the file paths are correct in order for it to work.

## Reference

- Dali, Salvador. Disney. Destino. 2003. https://www.youtube.com/watch?v=rMLVqQDeY58
- Efros, Alexei A. Isola, Phillip. Park, Taesung. Zhu, Jun-Yan.Unpaired Image-to-Image Translation using Cycle Consistent Adversarial Networks. 2017. https://junyanz.github.io/CycleGAN/
- Bansal, Hardik. Rathore, Archit. Understanding and Implementing CycleGAN in TensorFlow. 2017. https://hardikbansal.github.io/CycleGANBlog/
- Icaro. Best Artworks of All Time: Collections of Painting of the 50 Most Influential Artists of All Time. 2019. https://www.kaggle.com/ikarus777/best-artworks-of-all-time
