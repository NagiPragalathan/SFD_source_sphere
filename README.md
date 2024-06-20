# SFD Source Sphere

SFD Source Sphere is a project focused on simulating and visualizing fluid dynamics using spherical source fields. This project uses computational techniques to model fluid behavior and visualizes the results in a 3D environment.

![Output Image](https://github.com/NagiPragalathan/SFD_source_sphere/blob/main/Screenshot%202024-06-20%20213026.png?raw=true)

## Features

- **Fluid Dynamics Simulation**: Simulate fluid dynamics using spherical source fields.
- **3D Visualization**: Visualize the simulation results in a 3D environment.
- **Interactive Controls**: Adjust simulation parameters and observe changes in real-time.
- **High-Performance Computing**: Leverage efficient algorithms for high-performance simulations.

## Technologies Used

- **Backend**: Python
- **Visualization**: Three.js
- **Computational Libraries**: NumPy, SciPy

## Installation and Setup

### Prerequisites

- Python 3.x
- Node.js
- npm (Node Package Manager) or yarn

### Steps

1. **Clone the Repository**
    
    bash
    
    Copy code
    
    `git clone https://github.com/NagiPragalathan/SFD_source_sphere.git
    cd SFD_source_sphere` 
    
2. **Backend Setup**
    
    - Install Python dependencies:
        
        bash
        
        Copy code
        
        `pip install -r requirements.txt` 
        
3. **Frontend Setup**
    
    - Navigate to the frontend directory:
        
        bash
        
        Copy code
        
        `cd frontend` 
        
    - Install Node.js dependencies:
        
        bash
        
        Copy code
        
        `npm install` 
        
4. **Run the Development Server**
    
    - Start the backend server:
        
        bash
        
        Copy code
        
        `python main.py` 
        
    - Start the frontend server:
        
        bash
        
        Copy code
        
        `cd frontend
        npm start` 
        
5. **Access the Application**
    
    Open your browser and navigate to `http://localhost:3000` for the frontend and `http://localhost:8000` for the backend.
    

## Project Structure

arduino

Copy code

```
SFD_source_sphere/
├── backend/
│   ├── simulations/
│   │   ├── __init__.py
│   │   ├── fluid_simulation.py
│   ├── app.py
│   ├── config.py
│   ├── requirements.txt
│   └── README.md
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── styles/
│   ├── package.json
│   └── README.md
├── main.py
└── README.md
``` 

## Usage

- **Dashboard**: Access the main dashboard to control and visualize fluid simulations.
- **Simulation Controls**: Adjust parameters such as source strength, viscosity, and others to observe their effects on fluid behavior.
- **3D Visualization**: Interact with the 3D visualization to better understand fluid dynamics.

## Contribution

Contributions to the SFD Source Sphere project are welcome! If you would like to contribute, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](https://chatgpt.com/c/LICENSE) file for details.
