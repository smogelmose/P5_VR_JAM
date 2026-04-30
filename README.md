# BlindSight VR

> How can a virtual reality application raise awareness of visual impairment and offer practical training for individuals experiencing vision loss?

[Demo video](https://www.youtube.com/watch?v=dSshegJECDU)

---

## About

BlindSight VR is a virtual reality application designed to:

- **Raise awareness** about visual impairments among the general public
- **Empower individuals** experiencing vision loss through practical, risk-free training

Users are immersed in a busy urban environment where a tunnel vision effect replicates the limited field of view experienced by individuals with visual impairments. Navigating the scene with a VR controller functioning as a digital cane — guided by haptic feedback and spatial audio cues — users build confidence and skills transferable to real-world scenarios.

The experience serves two audiences: individuals with vision loss seeking a safe space to practice navigation, and sighted individuals gaining firsthand empathy for the challenges of visual impairment.

---

## Key Features

- Immersive urban environment simulating busy streets with traffic, obstacles, and pedestrians
- Tunnel vision effect replicating the restricted field of view of visual impairment
- VR controller functions as a digital cane with haptic feedback on collision
- Spatial audio cues for environmental interaction and directional guidance
- Safe, controlled setting for building real-world confidence and skills

---

## Benefits

- Empowers individuals with visual impairments through practical navigation training
- Fosters empathy and understanding among normally-sighted individuals
- Enhances public awareness of the challenges faced by those with vision loss
- Promotes inclusivity and accessibility awareness

---

## Build Requirements

| Requirement      | Version / Details                                                     |
|------------------|-----------------------------------------------------------------------|
| Unity            | 2022.3.47f1 (LTS)                                                     |
| Render Pipeline  | Universal Render Pipeline (URP) 14.0.11                               |
| XR Plugin        | OpenXR 1.12.1                                                         |
| XR Interaction   | XR Interaction Toolkit 2.6.3                                          |
| XR Hands         | com.unity.xr.hands 1.4.3                                              |
| Target Platforms | PC (Standalone), Android (Meta Quest)                                 |
| Headset          | Any OpenXR-compliant headset (Meta Quest, SteamVR, etc.)              |

---

## Setup & Installation

1. Clone the repository:
   ```
   git clone <repo-url>
   ```
2. Open the project in **Unity 2022.3.47f1** (LTS). Using a different version may cause package compatibility issues.
3. Go to **Edit → Project Settings → XR Plug-in Management** and enable **OpenXR** for your target platform.
4. Open the main scene: `Assets/Scenes/P5_VR_Crossing.unity`
5. Press **Play** with a connected VR headset, or build to Android for standalone Quest deployment.

### Android / Meta Quest Build

- Switch platform to Android in **File → Build Settings**
- Enable developer mode on the headset and connect via USB
- Build and Run

---

## Controls

| Input                          | Action                                              |
|--------------------------------|-----------------------------------------------------|
| VR controller (dominant hand)  | Digital white cane — sweep to detect obstacles      |
| Haptic feedback                | Vibration on cane collision with objects            |
| Spatial audio                  | Environmental cues for navigation and interaction   |
| Physical movement              | Walk through the urban crossing environment         |

Traffic lights cycle automatically. Animated NPCs and vehicles populate the scene. The tunnel vision effect is active throughout to simulate restricted peripheral vision.

---

## Third-Party Assets

- [Traffic Lights System](https://healthbargames.pl) by Mariusz Skowroński (Healthbar Games)
- POLYGON City Pack — urban environment assets
- asset_free_Ukraine_cars — vehicle models
- XR Hands & XR Interaction Toolkit Samples (Unity Technologies)
