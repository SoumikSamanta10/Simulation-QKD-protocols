# Attacking Quantum Key Distribution (QKD) Protocol

&emsp; This repository contains code for simulation of famous QKD Protocols like **BB84** and **E91**. We will use Python modules like Qiskit and Flask to achieve this. In the internet, there are a lot of simulating codes for these protocols. They perfectly demonstrate the mathematics behind these protocols. But, most of them fail to demonstrate the basic idea behind the Key Distribution. The protocol is actually designed to transfer the Key from one device to the other. Only demonstrating the mathematics behind it, is not enough. We need to show the real world application of the protocol.

&emsp; So we used **Flask** module of Python to transfer the Key from one device to the other. We used **Qiskit** module to simulate the quantum circuit on our classical computers.

&emsp; Our submited report can be found here: [Report](https://github.com/SoumikSamanta10/Simulation-QKD-protocols/blob/8354f31d8d89e9fca160388c4311f3799653e82f/Simulation%20of%20Attacks%20on%20Quantum%20Key%20Distribution%20protocols.pdf)

## Environment Setup before running the code:

1. Clone the repository.
```git clone https://github.com/SoumikSamanta10/Simulation-QKD-protocols.git```

2. Open the terminal and navigate to the directory.
```cd Simulation-QKD-protocols```

3. Install virtual environment package.
```pip install virtualenv```

4. make a virtual environment.
```virtualenv venv```

5. Activate the virtual environment.
Windows: ```./venv/Scripts/activate```
Linux: ```source venv/bin/activate```

6. Install the dependencies.
```pip install -r requirements.txt```

7. Run the codes as you want.
