Himavanth Kandula
Hrushith Ram Koduri

###The project requires XCODE and a IOS 17 Simulator to run.
###Open the folder in XCODE.


- **planetarium (top-level)**: This is the root folder of the project, which contains all the other files and folders related to the app.

- **planetarium (second-level)**: This folder contain the source files specific to the app, including code files, resources, and asset catalogs.

  - **textures**: A folder that contains image files or texture assets used to render the planets in the app.
  
  - **Assets**: This typically includes an `.xcassets` folder containing images and other assets for the app's UI, such as app icons, launch images, and more.

  - **AppDelegate**: A Swift class file that contains methods that are essential for the lifecycle of the app.

  - **SceneDelegate**: A class that's used to manage a UIWindowScene for apps that support multiple windows.

- **Model**: This folder contains the data model of the app.

  - **PlanetNodes**: Contains classes representing the nodes (elements) of planets in the app.
  
  - **PlanetModel**: Represents the data model for planets, containing properties such as name, texture, size, etc.
  
  - **UniverseNode**: Class representing the overall universe within the app.
  
  - **UniverseModel**: Similar to PlanetModel, but for modeling the universe's data.

- **View**: Contains the user interface files.

  - **LaunchScreen**: A storyboard or view representing the initial screen shown when the app is launched.
  
  - **Main**: Refers to the main storyboard file that contains the initial view controller and app interface flow.

- **Controller**: This folder contains the view controllers, which manage the presentation of the app's views.

  - **AboutController**: A view controller that manages an "About" view with app or planetarium information.
  
  - **PlaneDetectionController**: Related to AR (Augmented Reality) functionality, detecting planes in the environment to place 3D objects.
  
  - **ARMenuController**: Manages the AR-related menu or options within the app.
  
  - **PlanetController**: Manages the views and interactions related to individual planets.
  
  - **UniverseController**: Manages the views and interactions related to the universe or a collection of planets.

- **Info**: `Info.plist` file, which contains configuration and settings for the app such as version number, display name, permissions, and other metadata.





