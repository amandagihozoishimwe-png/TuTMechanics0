# TuTMechanics0
An interactive mobile app for structural engineering mechanics. Built with JavaScript and React Native, it features a synchronized form and visual canvas to calculate reaction forces, shear force diagrams, and bending moment diagrams in real time. Perfect for engineering students, educators, and field professionals.

SimpliMech
A product of TuTMechanics

An interactive structural analysis application designed for engineering students, educators, and practicing professionals. Built for mobile devices, it transforms complex structural calculations into an intuitive, hands-on experience.

Table of Contents
Overview

Core Capabilities

Technical Foundation

Development Roadmap

Getting Started

Contributing

License

Overview
Structural analysis is fundamental to engineering education and practice, yet traditional tools often create a disconnect between theoretical understanding and practical application. SimpliMech addresses this by combining precise mathematical computation with visual, interactive input methods—all within a mobile environment that goes wherever you do.

The application allows you to define structural systems through two complementary interfaces: a traditional form for entering exact values and a touch-based canvas where you can place and adjust loads by dragging them directly on the screen. Both inputs stay synchronized, giving you control whether you prefer working with numbers or interacting visually with the structure.

Core Capabilities
Real-Time Analysis
The calculation engine processes your inputs instantly, delivering reaction forces, shear force diagrams, and bending moment diagrams without any perceptible delay. This immediate feedback helps you explore how changes to load placement or magnitude affect the structural response.

Dual-Input Interface
You can define loads by typing precise values into the form fields or by touching and dragging them on the vector canvas. Both methods update the other simultaneously, accommodating different working styles and allowing you to verify your inputs visually.

Cross-Platform Design
Built with a single JavaScript codebase, the application compiles natively for both Android and iOS devices, ensuring consistent performance and a familiar interface regardless of your hardware.

Technical Foundation
Technology	Purpose
React Native (Expo)	Mobile application framework
JavaScript (ES6+)	Core programming language
react-native-svg	Vector graphics rendering
Custom matrix operations	Structural analysis calculations
Equilibrium equations	Physics-based computation
Development Roadmap
Phase 1: Core Functionality
Development of the complete user interface with synchronized form and canvas inputs, supporting simply supported beams with point loads. This establishes the foundation for all subsequent features.

Phase 2: Diagram Generation
Implementation of automatic shear force and bending moment diagrams, displaying these essential analytical outputs clearly and updating them in real time as you modify the structure.

Phase 3: Expanded Load Types
Extension to accommodate uniformly distributed loads and cantilever beam configurations, broadening the range of practical problems the application can address.

Phase 4: Professional Features
Introduction of structural code compliance checks and PDF report generation, transforming the application from an educational tool into a professional utility suitable for field use.

Getting Started
Prerequisites
Node.js (v14 or later)

npm or yarn

Expo CLI

Installation
bash
# Clone the repository
git clone https://github.com/tutmechanics/simplimech.git

# Navigate to the project directory
cd simplimech

# Install dependencies
npm install

# Start the development server
npm start
Running on Mobile Devices
bash
# Run on iOS
npm run ios

# Run on Android
npm run android

# Run on web (for testing)
npm run web
Contributing
We welcome contributions from the engineering and development community. Please follow these steps:

Fork the repository

Create a feature branch (git checkout -b feature/amazing-feature)

Commit your changes (git commit -m 'Add some amazing feature')

Push to the branch (git push origin feature/amazing-feature)

Open a Pull Request

License
This project is proprietary software owned by TuTMechanics. All rights reserved.

Contact
TuTMechanics
