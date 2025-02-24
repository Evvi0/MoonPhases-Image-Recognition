  
# MoonPhases-Image-Recognition
This image recognition project predicts the phase of the moon based off of an image. All images have been gathered from my very own backyard through my own telescope. Being an enjoyer of astronomy and the moon, I am glad I can join two of my hobbies together in this passion project. 

<img src="https://cdn.discordapp.com/attachments/764894037093253121/1334240058730876981/IMG_4632.jpg?ex=67aaf8a2&is=67a9a722&hm=7522ee29b26cad003a610b6c4a6557bedee1bdc86d01f3e6ee13b4a1bb0d42dd&" alt="Alt Text" width="210" height="300">  <img src="https://cdn.discordapp.com/attachments/764894037093253121/1334239194452856852/IMG_7978.jpg?ex=67aaf7d4&is=67a9a654&hm=b2bf1474e12543f94f5b9c4a79a40f697fca63815ad3a1bde46cb8b6dd59c638&" alt="Alt Text" width="200" height="200"> <img src="https://cdn.discordapp.com/attachments/764894037093253121/1338565589404356781/IMG_6474.jpg?ex=67ab8bd9&is=67aa3a59&hm=537ddad375ddc0693cd615815d8b18db3cbc4f6813b909ccaab99b80b4c122c7&" alt="Alt Text" width="200" height="350"> <img src="https://cdn.discordapp.com/attachments/764894037093253121/1334239195463684158/IMG_7548.jpg?ex=67aaf7d5&is=67a9a655&hm=5590c94984d017400f4e3e9ee370cea3395bd1d6b40c9874db7f0a52fe4bbec4&" alt="Alt Text" width="200" height="350"> 


- Gathering my own images posed the challenge of having to correclty classify each image itself. Attached as an mp4 file is a video of me correclty classifying each image to use for correct model training to show the work and time taken.




### Experimental Use of Data Augmentation
- Before training, the use of data aumentation to edit images from the dataset helps to create a more robust and well-rounded model that can predict on images outside of the normal dataset.
- The code below takes every image from the dataset and augments it to a out of focused or non-centered version of itself, and appends it back to the original dataset. 

![image](https://github.com/user-attachments/assets/4c0513bb-2dfd-49f9-ba16-53a52a28618c)

### Final count of images and augmented images

![image](https://github.com/user-attachments/assets/f75c9578-2933-4dc8-ade4-1a7b84d7459f)

### Creation of my own Convolutional Neural Network
- 5 output neurons for the moon's phases.
  
![image](https://github.com/user-attachments/assets/5a4f55cc-5ca6-46b9-aadb-a01b8533016a)

### Scoring

![image](https://github.com/user-attachments/assets/e3ba7d47-24f3-4de2-b42d-871520c4d408)


### Predictions
![image](https://github.com/user-attachments/assets/d736ff8c-bc24-4e4e-91bb-6355226fbca8)

![image](https://github.com/user-attachments/assets/2c4ed186-356c-4609-adcd-41326dd899fc) ![image](https://github.com/user-attachments/assets/d1c38e83-3650-41a6-b7e3-94a14444d8a1) ![image](https://github.com/user-attachments/assets/a3d96ebb-2ea9-4fe7-952c-ea4b0487cf31)




### Final Thoughts

- This project was a very fun experience for me, as it boasts the use data gathered on my own. Being able to take these images and not only predict on them, but augment them to create a better model produced excellent experience in both ends of the data analytics spectrum.










