Daniel He
Zena Chang

## Abstract

The idea of collaborating with or emulating the masters has been a dream. Of course, not everyone has the opportunity to do so. Even more so when ones favorite artist has passed. It is possible to learn an artist’s style to perform a manual style transfer, but this requires a great deal of practice and dedication. Fortunately, Cycle GAN makes such a dream reachable. Inspired by the collaborations like those done between Dali and Disney[1] , we have decided to do a collaboration with Dali by using Cycle GAN on our own body of work. Using this method, we hope to perform a true style transfer, where one artist provides the subject or content and another adds their stylized artistic execution.

## Model/Data

- The network model in [2] is used for the true style transfer. To learn the meaningful mapping between images in our sketchbook and Dali’s body of work, a generator network and a discriminator network are trained jointly on the basis of the fact that the generator learns the way to generate more likely accepted images by the discriminator while the discriminator’s learning to distinguish the original and generated images.

- The data used a collection of Dali's artwork and images from our sketchbook.

## Code

- Jupyter notebook: DanToDali.ipynb

## Results

- The results are discussed in detail within the report.

## Technical Notes

These were all run on datahub.

## Reference

- Dali, Salvador. Disney. Destino. 2003. https://www.youtube.com/watch?v=rMLVqQDeY58
- Efros, Alexei A. Isola, Phillip. Park, Taesung. Zhu, Jun-Yan.Unpaired Image-to-Image Translation using Cycle Consistent Adversarial Networks. 2017. https://junyanz.github.io/CycleGAN/
- Bansal, Hardik. Rathore, Archit. Understanding and Implementing CycleGAN in TensorFlow. 2017. https://hardikbansal.github.io/CycleGANBlog/
- Icaro. Best Artworks of All Time: Collections of Painting of the 50 Most Influential Artists of All Time. 2019. https://www.kaggle.com/ikarus777/best-artworks-of-all-time
