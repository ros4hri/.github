# ROS4HRI  
*Bridging Human-Robot Interaction with ROS*

---

## 🚀 What is ROS4HRI?  
ROS4HRI is a collection of open-source resources built around the [Human-Robot Interaction (HRI)](http://wiki.ros.org/hri) paradigm — enabling robots to meaningfully perceive, interpret and respond to humans in shared spaces and applications.  
Within this organization you’ll find modules for human skeleton tracking, face detection, full-body modeling, engagement estimation, and other key components for HRI applications. (See the list of repositories below.)

---

## 🎯 Why ROS4HRI?  
- **Modularity** – Every component follows the ROS ecosystem and can be integrated into your pipelines.  
- **Standardization** – A consistent message/specification set so different modules speak the same “HRI language”.  
- **Flexibility** – You can pick the pieces you need (face detection, body modelling, human description…) and build from there.  
- **Open Collaboration** – Built to be extended, adapted and contributed to by the wider robotics and HRI research community.

---

## 📂 Key Repositories  
Here are some of the flagship modules you’ll find here:  
- **[hri_msgs](https://github.com/ros4hri/hri_msgs)** – ROS message definitions specific to human-robot interaction.  
- **[libhri](https://github.com/ros4hri/libhri)** – A C++ API library wrapping ROS4HRI topics to simplify perception access.  
- **[hri_fullbody](https://github.com/ros4hri/hri_fullbody)** – A Python node for extracting 2D/3D skeletons of humans from RGB/RGB-D cameras.  
- **[hri_face_detect](https://github.com/ros4hri/hri_face_detect)** – A ROS-conformant node for detecting faces, extracting facial landmarks and estimating head pose.  
- …and many more specialized modules (emotion recognizer, body detector, engagement estimator, interaction simulators).

---

## 🧭 Getting Started  
1. Choose the repository that fits your need (face, body, engagement, etc).  
2. Clone the repo, install any dependencies listed in that module’s README.  
3. Launch the ROS node(s) as described in the repo.  
4. Subscribe to the published topics (e.g., human skeleton, engagement score) and integrate with your robot/system logic.  
5. Extend or adapt — build your own HRI workflows on top of these modules.

---

## 📦 Supported Platforms & Dependencies  
- Developed mainly for ROS (Robot Operating System) — check each module’s README for version compatibility.  
- Native support in C++ and Python (depending on module).  
- Leverages standard ROS messaging, TF frames, and typical robotics libraries (e.g., OpenCV, PCL, etc).  
- Fully open source and licensed under Apache 2.0 unless otherwise noted.  

---

## 🤝 Contributing  
We welcome contributions of all kinds: bug-reports, feature requests, pull-requests, documentation improvements, and new HRI modules.  
To contribute:  
- Fork the target repository.  
- Create a feature or fix branch.  
- Make sure your code follows the existing style conventions and passes any included tests.  
- Submit a Pull Request and reference the issue(s) it addresses.  
- Engage in review — we aim for clarity, correctness and maintainability.

---

## 📢 Stay Connected  
- Check the **Issues** tab of each repository for upcoming work and current priorities.  
- If you build an HRI use-case with ROS4HRI, we’d love to hear about it — drop a link or case study.  
- Consider citing this organization/modules in your research or project publications when relevant.

---

## 📝 License  
Unless otherwise stated in a specific module, all material in this organisation is available under the [Apache License, Version 2.0](LICENSE) — see each repository for details.

---

> _Ready to make robots more socially aware?_  
> Let’s build HRI systems that understand humans — together.


