# Conditional-Face-Generation

Generation of faces with specific attributes using Generative Adeversarial Networks (GANs) on CelebA dataset

# Model

Conditional DCGAN. 
Labels vector concatenated in the discriminator by means of vectorization. 
More details can be found in the file cGAN.ipynb

# Results 

The model achieves a State of the Art FID score of 11.7

  - Unconditional generation
  
    ![Alt text](https://github.com/marcellosicbaldi/Conditional-Face-Generation/blob/main/images/FID_11.png)
    
  - Woman, Young, Brown_Hair, Bangs, Straight_Hair, Attractive, Heavy_Makeup
   
    ![Alt text](https://github.com/marcellosicbaldi/Conditional-Face-Generation/blob/main/images/bangs.png)

  - Man, Old, Bald, Arched_Eyebrows, Bushy_Eyebrows, Pale_Skin, No_Beard
  
    ![Alt text](https://github.com/marcellosicbaldi/Conditional-Face-Generation/blob/main/images/bald.png)
