# PaTS-Wheel: Passively-Transformable Single-part Wheel

## Overview
The **PaTS-Wheel** is a novel wheel design for mobile robots that combines the smoothness and energy efficiency of traditional wheels with the obstacle traversal capabilities of legged robots. The wheel passively transforms to form hooks that assist in traversing unstructured terrains, such as stepped obstacles, purely based on the geometry of the obstacles. This design eliminates the need for additional sensors, actuators, or control systems, making it a simple and efficient solution for rugged environments.

## Key Features
- **Passive Transformation:** The wheel automatically adapts its shape to form hooks when encountering obstacles, allowing for better grip and traversal without the need for active control.
- **High Obstacle Clearance:** The PaTS-Wheel successfully traverses stepped obstacles up to approximately 70% of its diameter, outperforming conventional wheels (25% of diameter) and whegs (61% of diameter).
- **Energy Efficiency:** On flat ground, the PaTS-Wheel exhibits comparable energy consumption and vibration profiles to a standard wheel of the same size.
- **Unstructured Terrain Handling:** Suitable for use in unstructured environments where traditional wheeled robots struggle, such as outdoor terrains, rescue missions, and construction sites.

## Project Stages
1. **EV3 Lego Prototype**  
   - The first stage of development will use the LEGO Mindstorms EV3 platform to build a basic functional prototype.
   - This will allow for quick testing and proof-of-concept demonstrations.
   - It also enables easy modification and iteration on the wheel design.

2. **Digital Mock-Up**  
   - Create a digital 3D model of the PaTS-Wheel using CAD software.
   - The model will help in refining the design and performing virtual tests to optimize the wheel's performance.
   - This stage involves simulation of various terrains to predict how the wheel will behave in real-world scenarios.

3. **Aluminum Extrusion Prototype**  
   - The final prototype will be built using durable materials such as aluminum extrusion for the wheel frame.
   - This version will be more robust and suitable for real-world testing.
   - Tests will include performance metrics like energy consumption, vibration analysis, and obstacle traversal efficiency across different terrains.

## Suggested Materials
- **Aluminum Extrusion:** For building the final prototype. It provides a strong yet lightweight structure that is easy to work with for assembly and modifications.
- **3D Printed Parts:** Some components, such as the passive transformation mechanisms, can be initially prototyped using 3D printing to test the design before using metal.
- **Rubber for Treads:** To provide traction on various surfaces and reduce slippage during traversal.

## Getting Started
1. **Build the LEGO EV3 Prototype**
   - Follow the instructions in the `/docs/EV3-prototype` folder to assemble the initial prototype using LEGO parts.

2. **Simulate Using the Digital Mock-Up**
   - Use the CAD files in the `/models` folder to simulate different terrains.
   - Software suggestions include SolidWorks, Autodesk Fusion 360, or Blender.

3. **Build the Final Prototype**
   - Refer to the `/docs/final-prototype` for step-by-step assembly using aluminum extrusion and other suggested materials.

## Testing and Results
- Detailed testing instructions and data collection methods are provided in the `/testing` folder.
- Results from experiments will be logged and updated in the `/results` folder, including comparisons with traditional wheels and whegs.

## Contributing
- Contributions to the project are welcome! Whether you want to improve the design, add new features, or optimize the existing code, feel free to open a pull request or submit an issue.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments
This project is inspired by the need to improve mobile robot mobility in unstructured environments. Special thanks to all contributors and supporters for their input and feedback.

---

For detailed documentation, tutorials, and design files, please visit the project's [GitHub Wiki](https://github.com/your-username/PaTS-Wheel/wiki).
