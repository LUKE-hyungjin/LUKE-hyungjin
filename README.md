<div align="center">

# 👋 Hi, I'm Luke (Hyungjin Lee)

### Forward Deployed Engineer (Vision) @ MakinaRocks
#### *Robotics roots · Field deployment · Physical AI*

[![Portfolio](https://img.shields.io/badge/Portfolio-hyungjin--lee.pages.dev-FFB800?style=for-the-badge&logo=google-chrome&logoColor=white)](https://hyungjin-lee.pages.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%ED%98%95%EC%A7%84-%EC%9D%B4-ab1a29247/)
[![Email](https://img.shields.io/badge/Email-luke93052080@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:luke93052080@gmail.com)
[![Blog](https://img.shields.io/badge/Blog-Tistory-000000?style=for-the-badge&logo=tistory&logoColor=white)](https://informluke.tistory.com/)

</div>

---

## 🚀 About Me

> **"From CAD to the customer's site — I build it, ship it, and make it work in the field."**

I'm a **Forward Deployed Engineer** with a Mechanical Engineering background. I started by building robots — CAD in Fusion 360, URDF, ROS / Gazebo, Isaac Sim — and co-founded the robotics club **RO:AD**. As a **Software Engineering Officer in the ROK Air Force**, I built tools that non-developers used on closed military networks. Today at **MakinaRocks** I work directly with customers on **image generation** (LoRA fine-tuning, Image RAG, DPO alignment, VLM tagging).

```typescript
const luke = {
  name: "Hyungjin Lee (Luke)",
  role: "Forward Deployed Engineer (Vision) @ MakinaRocks",
  focus: ["Physical AI", "Robotics Data & Visualization", "Generative Vision"],
  background: {
    major: "B.S. Mechanical Engineering",
    experience: ["ROK Air Force SW Engineering Officer", "Robotics club RO:AD co-founder"],
  },
  languages: ["Korean (native)", "English"],
  techStack: ["Python", "ROS 2", "URDF", "Gazebo", "Foxglove", "PyTorch", "Fusion 360 API", "Blender API", "Docker"],
};
```

---

## 💼 Timeline

```mermaid
timeline
    title Engineering Journey
    2018-2022 : BS Mechanical Engineering @ Kyonggi Univ.
              : Undergraduate Researcher @ CAE Lab
              : Co-founder @ Robotics club RO:AD
    2022 : Autodesk Webinar Speaker<br/>(Fusion 360 → URDF plugin)
    2022-2025 : SW Engineering Officer @ ROK Air Force<br/>(Chief of Staff Award, Hackathon Grand Prize)
    2025-NOW : MakinaRocks<br/>Data Manager → Forward Deployed Engineer (Vision)
```

---

## 🛠️ Tech Stack

**🤖 Robotics & Simulation**

![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-F58113?style=flat-square&logoColor=white)
![Foxglove](https://img.shields.io/badge/Foxglove-6F3BE8?style=flat-square&logoColor=white)
![URDF](https://img.shields.io/badge/URDF-555555?style=flat-square&logoColor=white)
![NVIDIA Isaac Sim](https://img.shields.io/badge/Isaac_Sim-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Genesis](https://img.shields.io/badge/Genesis_AI-333333?style=flat-square&logoColor=white)

**🧠 AI / Vision**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![PyG](https://img.shields.io/badge/PyTorch_Geometric-3C2179?style=flat-square&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Diffusion](https://img.shields.io/badge/Diffusion_·_LoRA_·_DPO-8A2BE2?style=flat-square&logoColor=white)

**⚙️ CAD / 3D & Engineering**

![Fusion 360](https://img.shields.io/badge/Fusion_360_API-F48120?style=flat-square&logo=autodesk&logoColor=white)
![Blender](https://img.shields.io/badge/Blender_API-E87D0D?style=flat-square&logo=blender&logoColor=white)
![Gmsh · CalculiX](https://img.shields.io/badge/Gmsh_·_CalculiX-4B5563?style=flat-square&logoColor=white)
![ANSYS](https://img.shields.io/badge/ANSYS-FFB71B?style=flat-square&logo=ansys&logoColor=black)

**🧰 Infra & Web**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Cloudflare Pages](https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat-square&logo=cloudflare&logoColor=white)

---

## 🎯 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🦾 [Foxglove Robot Arm](https://github.com/LUKE-hyungjin/foxglove_robot_arm)
**Pick & place, debugged in Foxglove**

<img src="https://raw.githubusercontent.com/LUKE-hyungjin/foxglove_robot_arm/main/docs/images/foxglove_debug.png" width="100%" alt="Foxglove robot arm debug layout"/>

- 🤖 My own arm model (RO:AD era, inspired by Boston Dynamics Spot's arm)
- 🔁 Fusion 360 → URDF → Blender scene → Gazebo / ROS 2 Jazzy → Foxglove
- 📈 Cameras, motor torque, joint tracking error in one layout
- ✅ `docker compose up` · 19 end-to-end checks

`ROS 2` `Gazebo` `Foxglove` `URDF` `Docker`

</td>
<td width="50%" valign="top">

### 🚗 [Foxglove Robot Car Tutorial](https://github.com/LUKE-hyungjin/foxglove_basic_robot_car)
**8-step tutorial for new Foxglove users**

<img src="https://raw.githubusercontent.com/LUKE-hyungjin/foxglove_basic_robot_car/main/docs/images/foxglove-debug.png" width="100%" alt="Foxglove robot car debug layout"/>

- 🛠️ Two-wheeled robot I modeled in Fusion 360
- 🗺️ Arena built with a Blender script
- 📡 Debug lidar, wheel speed error, odometry vs. ground truth
- 📚 Every step's output in the repo — start anywhere

`ROS 2` `Gazebo` `Foxglove` `Blender`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🔧 [Fusion 360 → URDF](https://github.com/LUKE-hyungjin/fusion360_urdf_script)
**CAD-to-simulation plugin**

- 🎤 Presented at **Autodesk Korea Webinar** (2022) · [Watch](https://www.youtube.com/watch?v=n4WcBF8ReGQ)
- ⚖️ Joints, mass / inertia, colors & materials exported automatically
- 🎮 Works with Unity, NVIDIA Omniverse (Isaac Sim), ROS 2
- 🔗 Original: [RO-AD/fusion2urdf_ros2cpp](https://github.com/RO-AD/fusion2urdf_ros2cpp)

`Fusion 360 API` `Python` `URDF`

</td>
<td width="50%" valign="top">

### ✈️ [Deep-FEM UAV Wing](https://github.com/LUKE-hyungjin/Deep-FEM-UAV-Wing)
**GNN surrogate model for FEM**

- 🔁 Blender → Gmsh → CalculiX → PyG (GraphSAGE)
- 📊 200 parametric wing cases
- ⚡ ~600x faster than FEM
- 🖥️ [Live demo on Hugging Face](https://huggingface.co/spaces/hyungjin12/deep-fem-uav-wing)

`PyTorch Geometric` `FEM` `Gradio`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧪 Genesis AI for Military RL
**Physics-based RL research**

- ⚡ 10–80x faster RL training vs. Unity ML-Agents
- 🧮 4,096 parallel environments on GPU
- 📄 Presented at 2025 KIMST conference
- 🖱️ [Interactive Genesis GUI](https://github.com/LUKE-hyungjin/genesis_ai_gui)

`Genesis` `Reinforcement Learning` `Python`

</td>
<td width="50%" valign="top">

### 🛡️ Defense Robotics Competition
**Tracked robot & robotic arm (RO:AD)**

- 🏁 National Defense Robotics Competition (2021)
- 🔩 Full mechanical design in Fusion 360
- 🤖 URDF → Gazebo simulation → ROS integration
- 👥 Co-founded RO:AD and taught members ROS

`ROS` `Gazebo` `URDF` `Fusion 360`

</td>
</tr>
</table>

---

## 🏆 Achievements

* **Air Force Chief of Staff Award (Grand Prize)** — 6th Air Force Hackathon (2024)
* **Autodesk Korea Webinar Speaker** — Fusion 360 API for robot simulation (2022)
* **Grand Prize, Capstone Design Competition** — ML fault diagnosis for a robotic arm (2021)
* **KIISE conference finalist** — Unity ML-Agents autonomous driving (2nd author, 2021)
* **TensorFlow Developer Certificate** · **NVIDIA DLI** · **Engineer Information Processing**

---

## 📫 Let's Connect!

Always happy to talk about **robotics data, Physical AI, simulation, and deploying AI in the field**.

<div align="center">

### "Engineering the Physical World with Digital Intelligence"

</div>
