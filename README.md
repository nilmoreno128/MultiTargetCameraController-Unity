# Multi Target Camera Controller  

![MultiTargetCamera Example](Media/GIF1%20-%20README.gif)  
*An example of the camera dynamically following multiple targets.*

A Unity script that allows the camera to smoothly follow multiple targets simultaneously. It dynamically adjusts the camera's position and height based on the number of targets, providing a smooth and immersive experience for games that need to track multiple objects at once.

## Features  
- **Follow Multiple Targets**: Track multiple objects at once with smooth camera transitions.  
- **Dynamic Camera Height**: The camera adjusts its height based on the distance between the targets.  
- **Smooth Camera Movement**: Camera transitions smoothly between positions using a customizable smoothing factor.  
- **Customizable Settings**: Easily adjust offset, smooth time, and camera height settings to fit the needs of your game.

## Installation  
1. Download the `MultiTargetCameraController.unitypackage` file from this repository.  
2. Open your Unity project and go to **Assets > Import Package > Custom Package**.  
3. Select the `MultiTargetCameraController.unitypackage` file and click **Import**.  
4. After importing, attach the `MultiTargetCameraController` script to your main camera in the scene.

## How to Use  
1. Import the asset by following the installation steps above.  
2. Attach the `MultiTargetCameraController` script to your camera by selecting the camera in the scene and clicking **Add Component**.  
3. In the **Inspector**, configure the following parameters:
   - **Targets**: Add the objects you want the camera to follow by dragging them into the **Targets** array.
   - **Offset**: Adjust the offset from the center of the targets to set the camera's initial position.
   - **Smooth Time**: Set the smooth transition time for camera movement.
   - **Height Settings**: Set the minimum and maximum height of the camera and enable/disable height limit.
4. The camera will automatically adjust to follow all assigned targets and maintain an appropriate height based on their distance.

## License  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
