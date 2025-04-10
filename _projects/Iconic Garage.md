---
layout: project
order: 4

name: Iconic Garage
image: /assets/images/iconic-garage/thumbnail.jpg
carousel_images:
  [
    /assets/images/iconic-garage/1.png,
    /assets/images/iconic-garage/2.png,
    /assets/images/iconic-garage/3.png,
    /assets/images/iconic-garage/4.png,
    /assets/images/iconic-garage/5.png,
    /assets/images/iconic-garage/6.png,
    /assets/images/iconic-garage/7.png,
    /assets/images/iconic-garage/8.png,
  ]
tools: [ Android, iOS ]
project_links: [ https://play.google.com/store/apps/details?id=cz.iconicgarage.design, https://apps.apple.com/us/app/iconic-garage/id1524606092 ]
client: Retrobot

description: >-
  Creative tool designed for car enthusiasts, particularly fans of the classic Mini Cooper. \n
  Users can customize their dream cars by editing graphical elements such as colors and styles to create unique avatars or wallpapers. \n
  This app provides a fun way to design car-inspired visuals that can be shared on social media or used for personal purposes like device backgrounds.
project_scope: Indie
project_role: Unity Developer
project_duration: 3 months
team_size: 3
---

### My Contributions

- **Customizable Car Creation System**: Developed a robust system featuring over 2,500 car parts across five base car models, enabling extensive user customization. Implemented advanced image layering techniques, including overlaying and masking, to ensure seamless integration of parts and realistic visual representation.
- **Efficient Asset Management**: Utilized Unity's Addressables system to manage and load a large volume of sprite assets efficiently, optimizing memory usage and performance.
- **In-App Purchases Integration**: Implemented in-app purchase functionality for both Google Play Store and Apple App Store, allowing users to buy packs of car parts securely and seamlessly.
- **Image Export and Sharing**: Enabled users to export their customized car images to their device gallery and share them directly on social media platforms, enhancing user engagement and app visibility.
- **Metadata Management with Scriptable Objects**: Designed and implemented a system using Scriptable Objects to store and manage metadata for each car part, facilitating efficient data handling and scalability.

### Challenges and solutions

- **Managing Large Image Assets**: Handling a substantial number of high-resolution images posed challenges in memory management and performance optimization.
  - _Solution_: Implemented dynamic loading and unloading of assets using Addressables, ensuring that only necessary assets are in memory at any given time. This approach optimized memory usage and maintained smooth performance.

- **Metadata Parsing and Management**:Efficiently parsing and managing metadata for over 2,500 car parts required a scalable solution.
  - _Solution_: Utilized Scriptable Objects to store metadata, enabling organized and efficient access to part information. The metadata generation process was automated — most data was parsed directly from the image filenames, with built-in error and missing asset detection. This significantly streamlined the asset pipeline and made importing new content fast and reliable.