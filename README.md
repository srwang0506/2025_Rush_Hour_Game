# **2025 Rush Hour Game**

The project was co-created by **Sirui Wang**, **Juntang Huang**, **Jing Qiu**, **Chenxi Shen** and **Yuhan Tian** and will be made publicly available in code soon. Thank you for your interest in this project.

**To ensure a smooth deployment of our software on your system, please follow the steps below. All the operation complete in Windows.**

## Software Overview

Rush Hour is a classic single player sliding block puzzle on a 6×6 grid. The objective is to slide cars and trucks of varying lengths horizontally or vertically to clear a path for the red target car to exit on the right. To enrich gameplay, five modes are available:

- **Classic Mode (*Rush Hour*)** is the standard game without additional constraints.
- **Endless Mode (*Rush Infinity*)** comprises 89 levels of increasing difficulty; completing each level unlocks the next one.
- **Time Limit Mode (*Rush Time*)** requires solving the level within a specified time.
- **Step Limit Mode (*Rush Step*)** requires solving the level within a fixed number of moves.
- **Chaos Mode (*Rush Chaos*)** moves a random vehicle one square along its orientation every five moves.

## **Environment Setup**

To ensure maximum stability, we **strongly recommend** creating a dedicated Python environment for the game.

1. Open **Anaconda Terminal/Command Prompt**;

2. Create a **new environment** named `rushhour`:

   ```bash
   conda create --name rushhour python=3.9
   ```

   (**Hint:** As tested by the developers, you need to have Python version 3.7, 3.9, 3.10, 3.11 or 3.12 installed.)

3. Activate the environment:

   ```bash
   conda activate rushhour
   ```

4. Verify that the environment is correctly configured:

   ```bash
   conda info  --envs
   ```

   And you will find the `rushhour` environment and its path.

## Package dependencies

Pyqt5<br>
Pyqt5-tools<br>
openai<br>
requests<br>
psycopg2

The codes for installing the packages above:

```bash
conda install pyqt=5 openai requests psycopg2
pip install pyqt5-tools
```

### Local Database Deployment：

**postgreSQL (17.4) + pgAdmin4 (9.3)**

we use postgreSQL as our database management framework, you can enter follow website to install proper service<br>
[PostgreSQL download](https://www.postgresql.org/download/)

we use pgAdmin using the database visually, you can enter follow website to install proper software<br>
[PgAdmin4 download](https://www.pgadmin.org/download/pgadmin-4-windows/)

When entering into the software, right mouse button to create a new Database name **DataMy**(must be DataMy)
![Image](https://github.com/user-attachments/assets/ce0ebcf8-0c8b-4bb7-a8ac-14a5ced23432)

Then right mouse button on DataMy to click **Queue tool** and enter the following statements
![Image](https://github.com/user-attachments/assets/d0fe1b27-6721-4665-a1df-0fde1522a4f0)

Successfully deploy associate database!😊

## Software Demonstration

A demonstration video of the software is available—click the link below to download and view it.
[BaiduDisk](https://pan.baidu.com/s/1eLesSs-Q1exFacewd2RsXg)

Access code: yux7

## Citation

If you find this resource helpful, please cite it using the following format:

```latex
@software{wang2025rushhour,
  author       = {Sirui Wang, Juntang Huang, Jing Qiu, Chenxi Shen, Yuhan Tian},
  title        = {Rush Hour Game},
  version      = {1.0},
  year         = {2025},
  publisher    = {GitHub},
  url          = {https://github.com/srwang0506/2025_Rush_Hour_Game.git},
  note         = {[Computer software]}
}
```



