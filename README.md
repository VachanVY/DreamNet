# DreamNet
* The purpose of the repository is to visualize what the layers in the Convolutional Network see when we amplify the activation in the neurons

---
## DreamNet working
* ![DreamNet.png](DreamNet.png)
* For understanding DreamNet in detail see the jupyter notebook
---
## Results
* ### Monalisa: `mixed0` to `mixed10`
   ![monalisa0](monalisa/MonaLisa.jpg) ![monalisa1](monalisa/monalisa_mixed0.png) ![monalisa2](monalisa/monalisa_mixed1.png) ![monalisa3](monalisa/monalisa_mixed2.png) ![monalisa4](monalisa/monalisa_mixed3.png) ![monalisa5](monalisa/monalisa_mixed4.png) ![monalisa6](monalisa/monalisa_mixed5.png) ![monalisa7](monalisa/monalisa_mixed6.png) ![monalisa8](monalisa/monalisa_mixed7.png) ![monalisa9](monalisa/monalisa_mixed8.png) ![monalisa10](monalisa/monalisa_mixed9.png) ![monalisa11](monalisa/monalisa_mixed10.png)
* ### Sky: `act30` and `mixed3`
  ![sky](Sky/act30.png) ![sky1](Sky/mixed3.png)
* ### Scenery:
  ![GIF](scenery/GIF_200_001.gif)
  ![GIF1](scenery/GIF_200_003.gif) 
  
  
## Ablations
* Without clipping the gradients, the images are disrupted
  
  ![not_clipping_grads](monalisa/not_clipping_grads.png)
* Not normalizing the gradients doesn't affect the resultant image, therefore you should normalize the gradients to see the results
---
### Further Inspection which can be done
* The following repo was created using the Inception Model pre-trained on Imagenet which contains many classes
* Will update this repo to include results by different pre-trained Models, and then finetuned on different tasks like dog classification,...

### References
* [Inceptionism: Going Deeper into Neural Networks](https://blog.research.google/2015/06/inceptionism-going-deeper-into-neural.html)
