# VR-Based Solid Waste Management Awareness Platform

An immersive Virtual Reality platform that combines cutting-edge AI object detection with engaging gamified learning to teach waste segregation and promote sustainable environmental practices.

**Published in IEEE:** [IC3ECSBHI 2026](https://ieeexplore.ieee.org/document/11469071)

## 🎯 Overview

Waste management is a collective environmental responsibility. This project leverages Virtual Reality as a novel learning modality to educate users about proper waste segregation and disposal methods through immersive, interactive simulations. The platform integrates real-time object detection with hand tracking to create a genuinely immersive learning experience that increases knowledge retention and promotes sustainable behavior.

## ✨ Key Features

- **Immersive VR Environment**: Full 3D waste management simulation with spatial awareness and haptic feedback
- **Real-Time Object Detection**: YOLOv12 and MSCNN for intelligent waste item recognition
- **Hand Tracking**: HCI-based hand tracking for natural interaction with virtual waste items
- **Gamified Learning**: Points, feedback, and progressive difficulty levels to enhance engagement
- **Dual Scenarios**: Interior (home) and exterior (public spaces) waste management simulations
- **Cross-Platform VR Support**: OpenXR plugin compatibility with Meta Quest, HTC Vive, and other HMD devices
- **Interactive Feedback System**: Real-time guidance and educational feedback during waste segregation tasks
- **3D Modeling**: High-quality 3D assets created with Blender for realistic waste items

## 🛠️ Technologies Used

### Core Engine & VR
- **Unity 3D** (2021.3 LTS or higher)
- **OpenXR** for cross-platform VR support
- **XR Interaction Toolkit** for VR-specific interactions
- **XR Plugin Management** for device compatibility

### 3D Assets
- **Blender** - 3D model creation for waste items and environments
- **TextMeshPro** - Advanced text rendering for UI

### Development
- **C#** for all scripting
- **Git** for version control

## 📋 Prerequisites

Before you begin, ensure you have:

- **Unity Hub** and **Unity Editor** (2021.3 LTS or newer)
- **Git** installed on your system
- **VR Headset** (Meta Quest 2/3, HTC Vive, or compatible device with OpenXR support)
- **Visual Studio Code or Visual Studio** for C# development
- **Python 3.8+** (for running MSCNN model inference if needed)


## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/VR-Solid-Waste-Management.git
cd VR-Solid-Waste-Management
```

### 2. Open in Unity

1. Open **Unity Hub**
2. Click **"Add"** and select the cloned project folder
3. Open the project with Unity 2021.3 LTS or higher
4. Wait for Unity to import all assets and compile scripts

### 3. Install Required Packages

The project uses Unity Package Manager. Verify these packages are installed:

- XR Interaction Toolkit
- XR Plugin Management
- TextMeshPro
- OpenXR Plugin

**To manually install:**
1. Open `Window > Package Manager`
2. Search for each package and install the latest stable version
3. Configure XR Plugin Management for your target platform




## 🎮 How to Use

### For Development

1. Open the `MainMenu` scene in `Assets/Scenes/`
2. Ensure your VR headset is connected
3. Press **Play** in Unity Editor
4. Use VR controllers to:
   - Select waste items
   - Place them in appropriate bins
   - Receive real-time feedback on correctness

### Available Scenes

- **MainMenu** - Start screen and mode selection
- **InteriorWasteManagement** - Home waste segregation scenario
- **ExteriorWasteManagement** - Public space waste management scenario
- **Tutorial** - Interactive guide to waste types and sorting rules

### Building for VR Headset

1. Go to `File > Build Settings`
2. Select your target platform:
   - **Android** (Meta Quest 2/3)
   - **Windows** (PC VR: HTC Vive, Valve Index)
3. Configure Player Settings:
   - Color Space: Linear (for better graphics)
   - Minimum API Level: Android 6.0 (Quest)
4. Click **Build and Run**
5. The app will install and launch on your headset

## 📊 Research Paper

This project is based on peer-reviewed research published at IEEE's 2026 International Conference on Cognitive Computing in Engineering, Communications, Sciences & Biomedical Health Informatics (IC3ECSBHI).

**Paper Title:** Development of a VR-Based Solid Waste Management Awareness Platform Utilizing YOLOv12 and MSCNN

**Authors:** Sambhav Jain, Suresh K, Neha Singhal, Surabhi Saxena

**Publication Year:** 2026  
**Pages:** 287-291

**Key Research Findings:**
- VR-based waste management training increases knowledge retention compared to traditional methods
- Real-time AI feedback improves segregation accuracy
- Gamified elements significantly boost user engagement and motivation
- Platform effectiveness in promoting sustainable practices

[Read Full Paper on IEEE Xplore](https://ieeexplore.ieee.org/document/11469071)


### Difficulty Levels

Modify `GameDifficulty.cs` to adjust:
- Time limits per waste item
- Number of items per session
- Feedback detail level
- Scoring multipliers

## 🎓 Educational Impact

This platform addresses critical gaps in environmental education:

✅ **Knowledge Acquisition** - Users learn proper waste segregation methods
✅ **Behavioral Change** - Immersive experience promotes sustainable habits
✅ **Engagement** - Gamification increases learning motivation
✅ **Accessibility** - Works across different VR platforms via OpenXR
✅ **Scalability** - Can be deployed in schools and public awareness campaigns

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork** the repository
2. **Create a feature branch**
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add YourFeature with description'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/YourFeature
   ```
5. **Open a Pull Request** with a clear description

### Areas for Contribution
- Additional waste categories and items
- Language localization
- Performance optimization
- New VR interaction methods
- Mobile VR support
- Multiplayer classroom features
- Analytics and progress tracking


## 👥 Authors

- **Sambhav Jain** - Lead Developer  
  - [GitHub](https://github.com/sambhav302005-coder)
  - [LinkedIn](https://www.linkedin.com/in/sambhavjain~/)
  - Email: sambhav302005@gmail.com

- **Suresh K** - Co-Author
- **Neha Singhal** - Co-Author
- **Surabhi Saxena** - Co-Author

## 🙏 Acknowledgments

- **IEEE IC3ECSBHI 2026** for publication opportunity
- **Unity Technologies** for the game engine and XR toolkits
- **Ultralytics** for YOLOv12 framework
- **Blender Foundation** for 3D modeling tools
- **OpenXR Khronos Group** for cross-platform VR standard
- **Environmental educators** for domain expertise

## 📊 Project Statistics

- 🎮 **Development Time:** 6+ months
- 📱 **Supported Platforms:** Meta Quest 2/3, HTC Vive, Valve Index, Windows Mixed Reality
- 🎯 **Waste Categories:** 12+ types with 50+ individual items
- 🧠 **AI Models:** YOLOv12 + MSCNN integration
- 📈 **Research Impact:** Published in peer-reviewed conference

## 🗺️ Roadmap

- [ ] Multi-language support (Spanish, French, Mandarin, Hindi)
- [ ] Advanced analytics dashboard for educators
- [ ] Multiplayer classroom sessions
- [ ] Mobile VR optimization
- [ ] AI-powered personalized feedback based on user behavior
- [ ] Integration with school management systems
- [ ] Expanded waste categories (E-waste, Biomedical, Industrial)
- [ ] Leaderboards and achievement system
- [ ] Extended reality (AR) complementary features
- [ ] Real-world waste facility tours (video integration)

## 🐛 Known Issues & Limitations

- Performance depends on VR headset specifications
- YOLOv12 model size requires 4GB+ storage
- Requires steady internet for initial API calls (optional features)
- Hand tracking may be limited on some VR devices

## 📞 Support & Contact

For questions, bug reports, or feature requests:

- **Open an Issue** on GitHub
- **Email:** sambhav302005@gmail.com
- **LinkedIn:** [Connect with Sambhav](https://www.linkedin.com/in/sambhavjain~/)
- **GitHub Discussions:** Community Q&A

## 📚 Additional Resources

- [Unity XR Documentation](https://docs.unity3d.com/Manual/XR.html)
- [OpenXR Specification](https://www.khronos.org/openxr/)
- [YOLOv12 Documentation](https://github.com/ultralytics/ultralytics)
- [Waste Management Best Practices](https://www.un.org/sustainabledevelopment/sustainable-consumption-production/)

## 🌍 Sustainability Statement

This project contributes to **UN Sustainable Development Goal #12: Responsible Consumption and Production** by promoting environmental awareness and sustainable waste management practices through innovative educational technology.

---

**Made with ❤️ for a sustainable future**

Last Updated: May 2026  
Version: 1.0.0
