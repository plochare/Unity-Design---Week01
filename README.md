# Unity Design - Week 01

## Agenda

1. [Intro To Unity](#Intro-to-Unity)  
2. [Installing Unity Hub](#installing-unity-hub)  
3. [Unity Essentials](#installing-unity-editor-62)  
4. [Unity Asset Store](#managing-unity-modules)  
5. [Unity Build and Publish ](#creating-a-new-unity-project)  
6. [Installing GitHub Desktop](#adding-existing-projects-to-unity-hub)  
7. [Git LFS](#additional-resources)
8. [Git Readme Formatting](#additional-resources)
9. [Class Assignment - Week #01](#additional-resources)

---

## 🚀 Intro to Unity

Unity is a cross-platform real-time development platform primarily known for its game engine, enabling the creation of 2D and 3D interactive experiences, including video games, simulations, and augmented/virtual reality applications.

---

- **Unity Sizzle Reels**:  
[![Made with Unity Games sizzle 2025](images/UnityGames.jpg)](https://www.youtube.com/watch?v=LlgHCeLV92Y)
[![Unity in Industry](images/UnityIndustry.jpg)](https://www.youtube.com/watch?v=MtTea5GZHmo)

---

## 🚀 Install Unity Hub + Unity 6.2

## Requirements

- **Operating System**:  
  - **Windows**: 10 (64-bit) or 11  
  - **macOS**: macOS X 11+  
  - **Linux**: Ubuntu 24.04 supported (RPM/Deb installations possible for other distributions) :contentReference[oaicite:0]{index=0}

- **System compatibility**: Ensure your machine can run Unity. If your PC or Mac is relatively recent (within the last few years), you're likely good to go :contentReference[oaicite:1]{index=1}.

---

## Installing Unity Hub

1. **Download Unity Hub**  
   Visit the [Unity Download page](https://unity.com/download) and select the installer for your OS :contentReference[oaicite:2]{index=2}.

2. **Run the installer** and follow the on-screen instructions.

3. **Launch Unity Hub** and sign in with your Unity ID (or create one if you don't have an account) :contentReference[oaicite:3]{index=3}.

4. **Keep Unity Hub updated**—Unity Learn tutorials recommend using the latest official (non-beta) release to avoid discrepancies :contentReference[oaicite:4]{index=4}.

---

## Installing Unity Editor 6.2

1. In Unity Hub, go to the **Installs** tab.

2. Click **Add** to view available Unity Editor versions.

3. Select **Unity 6.2 (Supported)** and install it :contentReference[oaicite:5]{index=5}.

   > **Note:** Unity 6.2 is a Supported Update release, offering the latest features and platform improvements with support approximately matching LTS until the next update :contentReference[oaicite:6]{index=6}.

4. Optionally, include additional modules during installation (e.g., for WebGL, Visual Studio, language packs, or documentation) by selecting them in the module list :contentReference[oaicite:7]{index=7}.

---

## Managing Unity Modules

After installing Unity 6.2:

1. In the **Installs** tab, locate the Unity 6.2 entry and click the **gear icon**.

2. Choose **Add Modules**.

3. Select desired components such as **Dev tools**, **Build support** (Windows, WebGL, macOS, etc.), **Documentation**, or language packs, then click **Install** :contentReference[oaicite:8]{index=8}.

---

## Creating a New Unity Project

1. Go to the **Projects** tab in Unity Hub.

2. Click **New Project**.

3. Choose **Unity 6.2** from the **Editor Version** dropdown.

4. Pick a project **template** (e.g., 3D URP, Basic, etc.) :contentReference[oaicite:9]{index=9}.

5. Set a project **name**, **location**, select an **organization**, and decide if you want **Unity Cloud** or **Unity Version Control** enabled :contentReference[oaicite:10]{index=10}.

6. Click **Create project**. Unity Hub will download and open the project in the Editor :contentReference[oaicite:11]{index=11}.

---

## Adding Existing Projects to Unity Hub

To manage an existing project:

1. In Unity Hub’s **Projects** tab, click **Add → Add project from disk**.

2. Navigate to your project folder and select it.

3. If in **Editor Version** you see a warning that Unity 6.2 isn’t installed, either install it or choose another compatible version :contentReference[oaicite:12]{index=12}.

   > **Caution:** Avoid opening a project with an older Unity version—that would be a downgrade :contentReference[oaicite:13]{index=13}.

---

## Additional Resources

- For offline or command-line installations, refer to the official Unity Manual "Install Unity using installer files or Download Assistant" :contentReference[oaicite:14]{index=14}.

- Unity’s [documentation site](https://docs.unity3d.com) and Learn platform have further references for advanced setup and troubleshooting.

- Unity 6.2 includes improvements like Unity AI (beta), enhanced rendering pipelines, platform support, and performance upgrades :contentReference[oaicite:15]{index=15}.

---

## 🚀 Unity Essentials

### Download Unity Essentials pathway learning modules zip file
[- Unity Essentials Zip File](files/Essentials-Download-U6.zip)

---

## 🚀 Exploring the Unity Editor:

- **Explore the Unity Editor**:  
[![Explore the Unity Editor](images/UnityGames.jpg)](https://learn.unity.com/pathway/unity-essentials/unit/editor-essentials/tutorial/explore-the-editor-interface-1-1?version=6.0)

- **Master 3D Navivation**:  
[![Master 3D Navivation](images/UnityGames.jpg)](https://learn.unity.com/pathway/unity-essentials/unit/editor-essentials/tutorial/explore-the-editor-interface-1-1?version=6.0)


- **Design a Mural**:  
[![Design a Mural](images/UnityGames.jpg)](https://learn.unity.com/pathway/unity-essentials/unit/editor-essentials/tutorial/design-a-mural-in-scene-view?version=6.0)

---

## 🚀 Importing Assets from Unity Asset Store

Follow these steps to add assets from the Unity Asset Store into your Unity project.

### Prerequisites
* A Unity project already created/opened
* A Unity account (required for accessing the Asset Store)

### Steps to Import Assets

1. **Open the Unity Editor**

   * Launch your project through **Unity Hub**.

2. **Access the Unity Asset Store**

   * In Unity 2020.1 and newer, the Asset Store is accessed via your **web browser**:

     * Go to [Unity Asset Store](https://assetstore.unity.com/)
     * Log in with your Unity account

3. **Download an Asset**

   * Browse or search for the asset you want.
   * Click **Add to My Assets** (if free or purchased already).
   * Then click **Open in Unity** (this will launch the Unity Editor’s Package Manager).

4. **Import the Asset into Your Project**

   * Inside the Unity Editor, go to **Window > Package Manager**.
   * In the **Package Manager**, switch the dropdown to **My Assets**.
   * Find the asset you added, then click **Download** (if not already downloaded).
   * Once downloaded, click **Import**.
   * Unity will display an **Import Unity Package** dialog where you can review files.
   * Select the files you want, then click **Import**.

5. **Verify the Imported Asset**

   * The asset will appear in your **Project > Assets** folder.
   * You can now drag prefabs, textures, scripts, or models into your scene.

### Tips

* Keep your **project organized** by creating folders like `/Assets/Imported/` or `/Assets/ThirdParty/`.
* Check for **sample scenes** inside the imported asset to see how it works.
* Some assets may require additional setup (see the asset’s documentation).

---

## 🚀 Unity Build and Publish To Web and Desktop
Unity allows publishing projects to both web (via WebGL) and desktop platforms (Windows, macOS, Linux). The process involves configuring build settings and then generating the necessary files.
### Publishing for Desktop (Windows, macOS, Linux):
1. **Switch Platform:**
- In Unity, navigate to File > Build Settings. Select the desired desktop platform (Windows, Mac, or Linux) and click "Switch Platform".
2. **Player Settings:** 
- Configure platform-specific settings in Player Settings. This includes options for resolution, icons, splash images, and other platform-specific preferences.
3. **Build:** 
- In Build Settings, click "Build". Choose a location to save the build. For desktop builds, this typically generates an executable file and a corresponding data folder (e.g., _Data on Windows) which must be kept together for the application to run.
4. **Distribution:** 
- Distribute the executable and its accompanying data folder to users. They can then run the application directly on their respective operating systems.

### Publishing for Web (WebGL):
1. **Switch Platform:**
- In Unity, navigate to File > Build Settings. Select "WebGL" as the target platform and click "Switch Platform".
2. **Player Settings:** 
- Configure WebGL-specific settings in Player Settings (accessible from Build Settings). This includes options for compression, template, and publishing settings.
3. **Build:** 
- In Build Settings, click "Build". Choose a location to save the build output, which will be a folder containing HTML, JavaScript, WebAssembly, and data files.
4. **Distribution:** 
- Upload the contents of the generated build folder to a web server. Ensure the server is configured to serve WebAssembly files with the application/wasm MIME type for optimal performance with streaming compilation.

---

## 🚀 Installing GitHub Desktop

1. **Download GitHub Desktop**  
   - Go to the official site: [desktop.github.com](https://desktop.github.com/).  
   - Download the installer for your operating system (Windows or macOS).

2. **Install GitHub Desktop**  
   - Run the installer and follow the setup prompts.  
   - On macOS, drag the app into your **Applications** folder.  
   - On Windows, the installer will handle everything automatically.

3. **Sign in with GitHub**  
   - Launch GitHub Desktop.  
   - Sign in with your GitHub account (or create one if you don’t have it).  

4. **Configure your preferences**  
   - Go to `File > Options` (Windows) or `GitHub Desktop > Preferences` (macOS).  
   - Set your default editor, shell, and Git identity.  

5. **Clone or create a repository**  
   - Use the `File > Clone Repository` option to bring in an existing repo.  
   - Or `File > New Repository` to start a fresh one.  

---

## 🚀 Installing Git Large File Storage (Git LFS)

[Git LFS](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage)

---

## 📝 GitHub README Formatting (Markdown Basics)

GitHub uses **Markdown** syntax for README files. Here are the essentials:

````
1. **Headings**  
# H1 Title
## H2 Subtitle
### H3 Section

2. **Text Formatting**
**Bold text**  
*Italic text*  
~~Strikethrough~~  
`Inline code`

3. **Lists**
- Bullet list item
- Another item
  - Sub-item

1. Numbered item
2. Second item

4. **Links**
[GitHub Desktop](https://desktop.github.com/)
![Alt text](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
![Screenshot](images/screenshot.png)
[![Watch the video](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://youtu.be/VIDEO_ID)
````

[- Git Hub Formatting Readme Docs ](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)

---

## 🚀 Unity Design - Class Assignment - Week #01

Design a kid's bedroom with a bouncing ball and a tower of collapsing building blocks. Follow the lesson and modify the Unity 3D essentials scene. Add 2 elements from the Unity Store. Upload project files to personal github repository.
[- Learn Unity 3D Essentials](https://learn.unity.com/pathway/unity-essentials/unit/3d-essentials)






