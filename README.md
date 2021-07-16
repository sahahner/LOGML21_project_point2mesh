# LOGML21 Project 
## Surface reconstruction from point clouds using Point2Mesh

The [London Geometry and Machine Learning Summer School 2021](https://www.logml.ai/) was held 12-16 July 2021 online. During the week, we workrf in a group under the guidance of Rana Hanocka on a research project in the intersection of geometry and machine learning.

#### Mentor: Rana Hanocka

#### Collaborators: [Josh Mitton](https://github.com/JoshuaMitton), [Sara Hahner](https://github.com/sahahner), [Milton Wong](https://github.com/amiltonwong), [Leila Elabbady](https://github.com/lelabbady)

In this project, we will take a closer look into surface reconstruction from point clouds. This project is a hands-on project in PyTorch. You will gain familiarity with 3D surface reconstruction and applying deep neural networks to meshes. The project is mainly focused on the [Point2Mesh](https://github.com/ranahanocka/point2mesh) [1] technique, which optimizes the weights of a CNN to deform some initial mesh to shrink-wrap the input point cloud. You will apply this technique to scans and a wider variety of data in order to explore the current strengths and limitations of such a technique, and how it can be further improved. One interesting direction is to learn which edge to split, thereby defining where to add additional mesh connectivity. By the end of the project, you should better understand these topics from a theoretical and practical perspective, and gain insights with respect to how to incorporate similar concepts into your own research.

[1] Point2Mesh: A Self-Prior for Deformable Meshes. Rana Hanocka, Gal Metzer, Raja Giryes, and Daniel Cohen-Or. SIGGRAPH 2020.
