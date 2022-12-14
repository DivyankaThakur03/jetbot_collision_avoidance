# Jetbot - Collision Avoidance

The JetBot AI Kit is a robot platform powered by the Jetson Nano Developer Kit. It
is ready to assemble parts to get you up and running as quickly as possible. This is great for creating
entirely new AI projects for makers, students, and enthusiasts who are interested in learning AI
and building fun applications. It’s straightforward to set up and use and is compatible with many
popular accessories.

![Imagee (1)](https://user-images.githubusercontent.com/85764700/206226679-ab5fa1d0-833c-4abb-96ca-6a7c86d9de8f.png)

## Assemble the Bot
<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/85764700/206234213-6b3243e9-deb1-4652-8ce6-5eb8eeb03ce6.jpeg" width=290 height=480></td>
    <td><img src="https://user-images.githubusercontent.com/85764700/206229965-d7d0bcbe-3580-4f56-9579-1900b44110d7.png" width=290 height=480></td>
    <td><img src="https://user-images.githubusercontent.com/85764700/206232145-8186a6ef-6dad-4e39-b074-56404efcec0c.jpeg" width=290 height=480></td>
    
  </tr>
 </table>

## Clone the repository

```bash
  git clone https://github.com/DivyankaThakur03/jetbot_collision_avoidance.git
  cd jetbot_collision_avoidance
```

You'll see the following jupyter notebooks -

- 01_data_collection.ipynb
- 02_train_model.ipynb
- 03_live_execute.ipynb

### Data collection
I collected approximately 600 images for each class - free & block. </br>
The dataset is linked here [Dataset](https://drive.google.com/file/d/1PRIKbKASDO5khjF9uwhFNXnajOUJ7-sB/view?usp=sharing)
<table>
  <tr>
  <img src="https://user-images.githubusercontent.com/85764700/206235616-91eefb73-e054-42d6-bab7-bd34d5b48065.png" width=850 height=480>
  </tr>
</table>

### Training the model
Trained the model on Resnet-18 architecture for 60 epochs </br>
Model file attached here [best_model_jetbot.pth](https://drive.google.com/file/d/1C4nTLIEZQceznKGe-6ACGOngRE3ogz5S/view?usp=share_link)

<table>
  <tr>
  <img src="https://user-images.githubusercontent.com/85764700/206235894-fe9cd946-a412-4087-bc4b-2295ca15f94a.png" width=850 height=480>
  </tr>
</table>

### Live Demo
https://user-images.githubusercontent.com/85764700/206239976-29c34451-3cd5-4479-823f-f3d1d9d955cb.mp4



