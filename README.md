# Awesome Coverage Control [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)

## 🏠 About

This repository provides a **comprehensive curated list of multi-robot coverage control papers**, tools, libraries, and other related resources in the **Robotics/Control domain**. It is inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) and other awesome lists.

If you find this repository helpful, please consider STARing ⭐ this repo and contributing to improve it further! 🙌

<!-- ---

## 🛠 Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Papers](#papers)
  - [Coverage Control Algorithms](#coverage-control-algorithms)
  - [Persistent Coverage](#persistent-coverage)
  - [3D Coverage](#3d-coverage)
  - [Coverage with Feedback](#coverage-with-feedback)
  - [Safe Coverage](#safe-coverage)
  - [Angle-Aware Coverage](#angle-aware-coverage)
  - [Learning-Based Approaches](#learning-based-approaches)
- [Libraries and Tools](#libraries-and-tools)
- [Applications](#applications)
- [Datasets](#datasets)
- [Workshops and Tutorials](#workshops-and-tutorials)
- [Contributing](#contributing)
- [License](#license) -->

---

## 📖 Introduction

Coverage control is a key area in multi-robot systems, focusing on how robots can coordinate to efficiently monitor, explore, or act upon a given environment. This list aims to gather and organize important papers, tools, datasets, and applications related to coverage control.

---

## 🚀 Getting Started

- **What is Coverage Control?**
  - Coverage control is the study of how to deploy robots to efficiently cover a given area or monitor specific regions.
- **Basic Resources**:
  - [Coverage Control Introduction Paper](https://ieeexplore.ieee.org/document/1284411)
  - [Classic Paper on Coverage Control](https://ieeexplore.ieee.org/document/1284411)
- **Applications**: Surveillance, environmental monitoring, agriculture, and industrial automation.

---

## 📜 Papers

### Coverage Control Algorithms
- **[Foundational Paper](https://ieeexplore.ieee.org/document/1284411)**
  - *Authors*: J. Cortés, S. Martínez, T. Karatas, F. Bullo
  - *Summary*: This seminal paper introduced distributed algorithms for multi-agent coverage control, leveraging Voronoi partitions to efficiently allocate regions for individual agents in a continuous domain. It laid the foundation for subsequent research in multi-robot coverage control.
  - *Citation*: Cortés, J., Martínez, S., Karatas, T., & Bullo, F. (2004). Coverage Control for Mobile Sensing Networks. *IEEE Transactions on Robotics and Automation*, 20(2), 243-255.
  - *Link*: [IEEE Xplore](https://ieeexplore.ieee.org/document/1284411)

### Persistent Coverage Control
- **Control Barrier Function-Based Persistent Coverage with Performance Guarantee and Application to Object Search Scenario**
  - *Authors*: Hayato Dan, Junya Yamauchi, Takeshi Hatanaka, Masayuki Fujita
  - *Summary*: This paper proposes a performance-guaranteed persistent coverage control method for drone networks equipped with onboard cameras, utilizing control barrier functions (CBFs).
  - *Citation*: Dan, H., Yamauchi, J., Hatanaka, T., & Fujita, M. (2020). Control Barrier Function-Based Persistent Coverage with Performance Guarantee and Application to Object Search Scenario. *Proceedings of the 4th IEEE Conference on Control Technology and Applications (CCTA)*, 640-647.
  - [Link](https://ieeexplore.ieee.org/document/9206273)

- **Persistent Object Search and Surveillance Control with Safety Certificates for Drone Networks Based on Control Barrier Functions**
  - *Authors*: Hayato Dan, Takeshi Hatanaka, Junya Yamauchi, Takumi Shimizu, Masayuki Fujita
  - *Summary*: This study addresses persistent object search and surveillance missions for drone networks, presenting a safe control strategy based on CBFs to ensure collision avoidance and energy efficiency.
  - *Citation*: Dan, H., Hatanaka, T., Yamauchi, J., Shimizu, T., & Fujita, M. (2021). Persistent Object Search and Surveillance Control with Safety Certificates for Drone Networks Based on Control Barrier Functions. *Frontiers in Robotics and AI*, 8, 740460.
  - [Link](https://www.frontiersin.org/articles/10.3389/frobt.2021.740460/full)

### Angle-Aware Coverage Control
- **Angle-Aware Coverage Control for 3-D Map Reconstruction with Drone Networks**
  - *Authors*: Takumi Shimizu, Shunya Yamashita, Takeshi Hatanaka, Kuniaki Uto, Martina Mammarella, Fabrizio Dabbene
  - *Summary*: This research focuses on optimizing drone positions and orientations to enhance 3D map reconstruction accuracy, introducing an angle-aware coverage control strategy.
  - *Citation*: Shimizu, T., Yamashita, S., Hatanaka, T., Uto, K., Mammarella, M., & Dabbene, F. (2021). Angle-Aware Coverage Control for 3-D Map Reconstruction with Drone Networks. *IEEE Control Systems Letters*, 6, 1302-1307.
  - [Link](https://ieeexplore.ieee.org/document/9650560)

- **Efficient Angle-Aware Coverage Control for Large-Scale 3D Map Reconstruction Using Drone Networks**
  - *Authors*: Muhammad Hanif, Takumi Shimizu, Zhiyuan Lu, Masaya Suenaga, Takeshi Hatanaka
  - *Summary*: This study presents an efficient coverage control approach for large-scale 3D mapping, utilizing angle-aware techniques to optimize drone deployment.
  - *Citation*: Hanif, M., Shimizu, T., Lu, Z., Suenaga, M., & Hatanaka, T. (2024). Efficient Angle-Aware Coverage Control for Large-Scale 3D Map Reconstruction Using Drone Networks. *SICE JCMSI*.
  - [Link](https://www.tandfonline.com/doi/full/10.1080/18824889.2024.2346375)

- **Angle-Aware Coverage with Camera Rotational Motion Control**
  - *Authors*: Zhiyuan Lu, Muhammad Hanif, Takumi Shimizu, Takeshi Hatanaka
  - *Summary*: The paper proposes a method to improve coverage efficiency by controlling the rotational motion of cameras on drones, considering angle-aware strategies.
  - *Citation*: Lu, Z., Hanif, M., Shimizu, T., & Hatanaka, T. (2024). Angle-Aware Coverage with Camera Rotational Motion Control. *SICE JCMSI*.
  - [Link](https://www.tandfonline.com/doi/full/10.1080/18824889.2024.2351637)


### Learning-Based Approaches
- **Active Learning-Based Model Predictive Coverage Control**
  - *Authors*: Rahel Rickenbach, Andrea Carron, et al.
  - *Summary*: The study tackles the coverage problem by using a hierarchical framework where references are calculated at a central server and passed to agents' local model predictive control tracking schemes, ensuring efficient exploration of unknown environments.
  - *Citation*: Rickenbach, R., Carron, A., et al. (2023). Active Learning-Based Model Predictive Coverage Control. *arXiv preprint arXiv:2303.09910*.
  - [Link](https://arxiv.org/abs/2303.09910)

- **Safe Persistent Coverage Control with Control Barrier Functions Based on Sparse Bayesian Learning**
  - *Authors*: Kazuki Mizuta, Yasuhide Hirohata, Junya Yamauchi, Masayuki Fujita
  - *Summary*: This paper proposes a persistent coverage control method that integrates control barrier functions with sparse Bayesian learning to ensure safety and efficiency in exploration tasks.
  - *Citation*: Mizuta, K., Hirohata, Y., Yamauchi, J., & Fujita, M. (2023). Safe Persistent Coverage Control with Control Barrier Functions Based on Sparse Bayesian Learning. *IEEE Transactions on Robotics*, 39(1), 45-59.
  - [Link](https://ieeexplore.ieee.org/document/9966178)

<!-- ---

## 🛠 Libraries and Tools
- **[Library Name](https://github.com/example)** - Brief description of what this library does.
- **[Another Tool](https://github.com/example)** - Another tool and its purpose. -->

<!-- ---

## 📊 Applications
- **Surveillance**: Coverage control applied to monitoring and security tasks.
- **Environmental Monitoring**: Use cases in agriculture, disaster management, and ecology.
- **Industrial Automation**: Applications in factories and warehouses.
- **Search and Rescue**: Scenarios for disaster recovery and emergency responses. -->

<!-- ---

## 📂 Datasets
- **[Dataset Name](https://example.com)** - Brief description.
- **[Another Dataset](https://example.com)** - Brief description.

---

## 🎓 Workshops and Tutorials
- **[Workshop Name](https://example.com)** - Workshop details and focus.
- **[Tutorial Name](https://example.com)** - Tutorial and learning resources. -->

---

## 🤝 Contributing

Contributions are welcome! Please follow the [contributing guidelines](CONTRIBUTING.md) for details on how to add papers, tools, or any other resources.

<!-- ---

## 📜 Citation
If you find this repository helpful, please cite it using:

```bibtex
@misc{awesomecoverage2025,
      title={Awesome Coverage Control}, 
      author={Your Name and Contributors},
      year={2025},
      url={https://github.com/yourusername/awesome-coverage-control}, 
}
``` -->
