# Augmented Reality with Unity
This  Github teaches you how to setup the Augmented Reality with Unity

### Requirments
* Install Unity Hub " https://unity.com/pages/unity-pro-buy-now?gclid=Cj0KCQiAuvOPBhDXARIsAKzLQ8Fvxpt8Ng32RbNFCrb7G18xq8_s6Y9zy65O_KXsU5fDQ1dSu1iFZm8aAqY-EALw_wcB&gclsrc=aw.ds "
* Install Vuforia " https://developer.vuforia.com/ " Link setup tutorial = " https://www.youtube.com/watch?v=y7VD7yGwmV4&t=1s " 

### Steps 
*  Create a database on the Vuforia Developer Portal 
  ![Screenshot 2022-02-05 101613](https://user-images.githubusercontent.com/80488842/152625066-bd894ae3-ae1d-428f-b028-4f3a6e9dd85d.png)
* Add a Target

  ![image](https://user-images.githubusercontent.com/80488842/152625110-bf8e55af-9847-4401-96dc-62f8be60a3a4.png)
  
  'import an image from your device to act as the base of the Augmented Reality'
  'After that download the database'
  
## Unity Setup 
* To able to use the Vuforia   
  ![Screenshot 2022-02-05 102203](https://user-images.githubusercontent.com/80488842/152625273-babc6cec-d4cc-4ca7-bf3a-8347aa50a176.png)
  'First download an choose the Editor version 2022.1.0b6(BETA)'
  'Select the 3D core, name your file and create your project'
* You can refer to the Link setup tutorial = " https://www.youtube.com/watch?v=y7VD7yGwmV4&t=1s " to install your Vuforia 

* To import the object you must first import the file to the Unity folder by dragging the object folder to the asset folder.

  ![Screenshot 2022-02-05 102959](https://user-images.githubusercontent.com/80488842/152625624-7f07724f-5d19-41c9-b569-66757413b5e7.png)

* After that go to the source folder then dragged the object into the scene.
 
  ![Screenshot 2022-02-05 103308](https://user-images.githubusercontent.com/80488842/152625685-bf181c1f-d035-412d-8b9f-068247aa2e89.png)

* In order to include the texture of the object reimport the model into the texture folder

  ![Screenshot 2022-02-05 103557](https://user-images.githubusercontent.com/80488842/152625768-076b4334-6027-4aee-bc26-340b86ad0946.png)
  
* After that dragged the texture to the Albedo to include the color

 ![Screenshot 2022-02-05 103645](https://user-images.githubusercontent.com/80488842/152625822-0a4b7c8b-2866-4cb7-a470-1d566827f968.png)
 
 * Dragged the ReynaNoTextures under the ImageTarget
 
 ![Screenshot 2022-02-05 103908](https://user-images.githubusercontent.com/80488842/152625861-922634a5-aaa1-4ff6-9056-8bc73645e26a.png)
 
  'this is so that the model will appear under the AR object'
  
### Example 

![reyna ag](https://user-images.githubusercontent.com/80488842/152625906-ff547349-9d8f-4354-9b36-98ba527d535d.png)



