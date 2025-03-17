# HandDrive

##  WWDC23 Swift Student Challenge

<div align="center">
  <img src="https://github.com/user-attachments/assets/a8bbf0b2-56b6-4cad-8fc1-8ef513cdce51" width="250"/>
</div>


## About the Project
> This app, 'HandDrive', encourages driving for individuals with lower-body paralysis by using AR-based parking simulations to help them gain confidence and lead a more positive life.

Did you know that individuals with lower-body paralysis can also drive?  

Many people with disabilities operate vehicles using assistive hand controls to manage acceleration and braking. However, despite the technical feasibility, psychological fears and anxieties often make them hesitant to take on the challenge.

HandDrive is an app designed to help these individuals experience parking simulations in an AR (Augmented Reality) environment. The app utilizes machine learning technology to recognize hand movements. The left hand, when clenched into a fist, controls steering motions, while the right hand’s gestures are used to manage acceleration and braking. This setup allows users to practice driving motions naturally, just as they would with actual assistive hand controls.

Through a three-stage parking simulation, users can practice driving, overcome perceived limitations, and build both understanding and confidence in their driving abilities.


## Key Technologies
- **ARKit**: Created an immersive driving environment that mimics real-world scenarios.
- **Hand Gesture Recognition**:
  - Used `hand.chirality == .left/.right` to distinguish left and right hand interactions.
  - **Left Hand**: Implemented `HandPoseClassification` for simulating hand controller actions.
  - **Right Hand**: Used `HandActionClassification` with `MyHandActionClassifier` for steering control.
- **CreateML**: Trained separate machine learning models for each hand with **95%+ accuracy** using data augmentation.
- **Responsive Design**: Developed a grid-based layout for optimal performance across iPad devices, from iPad Air to iPad Pro.
- **User Flow**: Designed a clear progression—`Start > Story > Walkthrough > Main > Ending`—using modals and animations for intuitive guidance.
- **AI-Assisted Development**: Utilized **ChatGPT** to review code and ensure reliability.

<!--
## Video

<div align="center">
  <img src="https://github.com/user-attachments/assets/af24ab94-35d7-4b48-9f63-06c6d1ddd791" width="300"/>
</div>

<br/>
-->

## Key Screenshots

| **Main View** | **Story View** | **Simulation View** |
| --- | --- | --- |
| <img src="https://github.com/user-attachments/assets/7c0a9ae0-f6d3-4e2b-a0ae-9b73970f65f3" width="300"/> | <img src="https://github.com/user-attachments/assets/cbaaf9e5-978d-4f93-a316-2628cab62284" width="300"/> | <img src="https://github.com/user-attachments/assets/8e6dae77-abbf-4690-87c5-350e4fbf2165" width="300"/> |

<!--
## Additional Screenshots

<div align="center">
  <img src="https://github.com/user-attachments/assets/da75ef1d-6456-4474-8ccb-31682ae6d337" width="250"/>
  <img src="https://github.com/user-attachments/assets/cfac9ab1-44fc-4971-bdb9-1b63bfbc09a5" width="250"/>
  <img src="https://github.com/user-attachments/assets/1a568436-d30a-491a-8176-dd90467ba710" width="250"/>
  <img src="https://github.com/user-attachments/assets/69c03c7a-1daa-4f1d-9028-f344f25be82f" width="250"/>
  <img src="https://github.com/user-attachments/assets/88bd3552-3c15-4ce5-9615-a33fdab9a202" width="250"/>
  <img src="https://github.com/user-attachments/assets/ace4f2e5-323b-40c5-a6d7-da162364f388" width="250"/>
</div>
-->
