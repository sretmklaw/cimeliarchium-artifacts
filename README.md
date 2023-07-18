# Old World Saints Artifacts
> cimeliarchium est thesaurum qui continet gemmae pretiosarum fiderum

## Project Dependencies

- Gradle 7 - build configuration
- Eclipse 4 - integrated development environment

## Getting Started

1. Inside C:\git run the following command to clone the repository:
  ```
  git clone https://github.com/sretmklaw/cimeliarchium-artifacts.gif
  ```
2. Create an empty folder named 'cimeliarchium' and open as an Eclipse workspace:
  - Select the cloned repository under File -> Open Projects from File System.
3. Import required Gradle dependencies into the JRE System Library:
  - Right-click on the project and select Gradle -> Refresh Gradle Project.
3. Make changes inside the project
  - Add/update/remove files under src/main/resources
  - Increment version number in build.gradle
4. Build the project and publish the artifact to local system directory.
  - Run the 'publish' target under Gradle Tasks.