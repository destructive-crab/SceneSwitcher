<p align="center"><h1>SceneSwitcher</h1></p>
<p align="center">
  <a>
    <img alt="Made With Unity" src="https://img.shields.io/badge/made%20with-Unity-57b9d3.svg?logo=Unity">
  </a>
  <a>
    <img alt="License" src="https://img.shields.io/github/license/RimuruDev/SceneSwitcher?logo=github">
  </a>
  <a>
    <img alt="Last Commit" src="https://img.shields.io/github/last-commit/RimuruDev/SceneSwitcher?logo=Mapbox&color=orange">
  </a>
  <a>
    <img alt="Repo Size" src="https://img.shields.io/github/repo-size/RimuruDev/SceneSwitcher?logo=VirtualBox">
  </a>
  <a>
    <img alt="Downloads" src="https://img.shields.io/github/downloads/RimuruDev/SceneSwitcher/total?color=brightgreen">
  </a>
  <a>
    <img alt="Last Release" src="https://img.shields.io/github/v/release/RimuruDev/SceneSwitcher?include_prereleases&logo=Dropbox&color=yellow">
  </a>
  <a>
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/RimuruDev/SceneSwitcher?branch=main&label=Stars&logo=GitHub&logoColor=ffffff&labelColor=282828&color=informational&style=flat">
  </a>
  <a>
    <img alt="GitHub user stars" src="https://img.shields.io/github/stars/RimuruDev?affiliations=OWNER&branch=main&label=User%20Stars&logo=GitHub&logoColor=ffffff&labelColor=282828&color=informational&style=flat">
  </a>
  <a>
    <img alt="" src="https://img.shields.io/github/watchers/RimuruDev/SceneSwitcher?style=flat">
  </a>
</p>

## Description

**SceneSwitcher** – is a handy Unity editor tool that helps you move between scenes.

## Features

- **Fast switching between scenes**: You can switch to any scene just from tool's window.
- **Different scene pools**: You can choose to display scenes only from Build Settings or all scenes in project.
  сборки (Build Settings).
- **Highly customizable**: every part of scene switcher window can be customized.
- **Safe**: scenes are saved on switching, scene switcher stuff is disabled on Play Mode.
- **Custom Play Mode Start Scene**: you can change from which scene you want to enter into Play Mode. Or disable this feature.
- **Return To Previous Scene Button**: SceneSwitcher remembers the previous scene and can return to it. Or you can disable this feature.

## Installation
### With Package Manager
1. Open your Unity project.
2. Open **Window** → **Package Manager**.
3. In **Package Manager** press `+` button, then choose **Add package from git URL...**.
4. Paste this URL:`https://github.com/RimuruDev/SceneSwitcher.git`
5. Press **Enter** and wait for the installation to complete.
### With Unity Package 
1. Download latest release from github page.
2. Drag and drop unitypackage file in your project.
3. Check if SceneSwitcher source was imported correctly: in Editor folder.

## Usage

After **SceneSwitcher** installation tool appears in Unity menu:  
**Tools** → **Scene Switcher**.

1. Open **Scene Switcher** window. In Assets/Editor/SceneSwitcher settings asset will be created.
2. Choose which scenes you want to see in SceneSwitcher window.
3. Choose if you want to have Return button.
4. Choose if you want to have Custom Play Mode Scene feature, then choose it. You can look for build index in your build settings;
5. Choose if you want to save scene before switch. It is not recommended to disable this feature.
6. Edit spacings and heights of buttons.
7. Edit the formatting of button labels. SCENE_NAME will be replaced with scene name. 
