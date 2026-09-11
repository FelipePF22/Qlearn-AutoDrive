
# 🤖 Navegação Autônoma com Q-Learning e Fast LiDAR

> 🌐 **Selecione o idioma / Choose your language**

<details>
<summary><b>🇧🇷 Português (Brasil)</b></summary>

<br>

Este repositório foi desenvolvido como parte da entrega do **Projeto 1 da disciplina de Robôs Móveis Autônomos**, pelos alunos **Felipe Pereira Furlaneto** e **Marcos Vinicios dos Santos**.

---

## 🎯 Objetivo

Este projeto tem como objetivo desenvolver um sistema de navegação autônoma para um robô móvel DC, desenvolvido pelo **Laboratório de Robótica e Sistemas Inteligentes da Universidade Federal de São Carlos** (Autora: **Kelen Teixeira Vivaldini** — disponível em: https://github.com/vivaldini/dcrobot), por meio da integração de técnicas de aprendizado por reforço (Q-learning) e percepção baseada em Fast LiDAR.

A proposta consiste em treinar um agente em um ambiente simulado, controlado e simplificado, utilizando dados discretizados sensoriais do modelo simulado LiDAR Velodyne HDL-32E, desenvolvido por **Lovro Marković**, disponível em: https://github.com/lmark1/velodyne_simulator — bem como neste repositório, na pasta `velodyne_simulator`. Esse sensor será responsável pela identificação dos obstáculos e, por consequência, pela tomada de decisão em tempo real.

Ao final, como trabalho futuro, busca-se avaliar a capacidade do agente de generalizar o comportamento aprendido para cenários distintos, mesmo diante de incertezas e mudanças no ambiente.

---

## 📥 Como Baixar e Executar o Projeto

### 1. Clonar o Repositório

```bash
cd seu_workspace/src
git clone https://github.com/FelipePF22/Qlearn-AutoDrive.git
```

### 2. Compilar os arquivos

```bash
cd
catkin clean
catkin build
source devel/setup.bash
```

### 3. Rodar a simulação

```bash
roslaunch q_learning_control q_learning_sim.launch
```

---

## 📷 Imagens da Simulação

Após rodar o código acima, as seguintes telas serão abertas:

**Ambiente no Gazebo:**

![Gazebo Ambiente](images/gazebo_ambiente.png)

**Visualização no RViz:**

![RViz Velodyne](images/rviz_velodyne.png)

---

> ⚠️ Este repositório contém os **resultados preliminares da primeira parte da avaliação**.
> Dessa forma, o diretório contém apenas o segmento de treinamento inicial. As técnicas de otimização de aprendizado de máquina, bem como a implementação da política em um ambiente mais complexo, foram destinadas à segunda fase do projeto.

</details>

<details>
<summary><b>🇺🇸 English</b></summary>

<br>

This repository was developed as part of the **Project 1 deliverable for the Autonomous Mobile Robots course**, by students **Felipe Pereira Furlaneto** and **Marcos Vinicios dos Santos**.

---

## 🎯 Objective

This project aims to develop an autonomous navigation system for a DC mobile robot, developed by the **Laboratory of Robotics and Intelligent Systems at the Federal University of São Carlos** (Author: **Kelen Teixeira Vivaldini** — available at: https://github.com/vivaldini/dcrobot), through the integration of reinforcement learning techniques (Q-learning) and Fast LiDAR-based perception.

The proposal consists of training an agent in a simulated, controlled, and simplified environment, using discretized sensory data from the simulated Velodyne HDL-32E LiDAR model, developed by **Lovro Marković**, available at: https://github.com/lmark1/velodyne_simulator — as well as in this repository, in the `velodyne_simulator` folder. This sensor will be responsible for identifying obstacles and, consequently, for real-time decision-making.

Finally, as future work, the goal is to evaluate the agent's ability to generalize the learned behavior to different scenarios, even in the face of uncertainties and changes in the environment.

---

## 📥 How to Download and Run the Project

### 1. Clone the Repository

```bash
cd your_workspace/src
git clone https://github.com/FelipePF22/Qlearn-AutoDrive.git
```

### 2. Build the files

```bash
cd
catkin clean
catkin build
source devel/setup.bash
```

### 3. Run the simulation

```bash
roslaunch q_learning_control q_learning_sim.launch
```

---

## 📷 Simulation Images

After running the code above, the following screens will open:

**Gazebo Environment:**

![Gazebo Environment](images/gazebo_ambiente.png)

**RViz Visualization:**

![RViz Velodyne](images/rviz_velodyne.png)

---

> ⚠️ This repository contains the **preliminary results of the first part of the evaluation**.
> Therefore, the directory contains only the initial training segment. Machine learning optimization techniques, as well as the policy implementation in a more complex environment, were reserved for the second phase of the project.

</details>
