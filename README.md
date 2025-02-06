# **Ant Colony Simulation**  

This project is a Java-based simulation of ant colonies, developed as part of an EPFL Coursera course to practice object-oriented programming (OOP) concepts. It models collective intelligence in a toroidal environment where ants collect food, leave pheromone trails, and interact with predators, demonstrating emergent complex behavior from simple individual rules.

## 🚀 **Features**  
✅ Simulation of worker ants (food collection) and soldier ants (territory defense)  
✅ Dynamic pheromone trail system with evaporation mechanics  
✅ Toroidal 2D environment with food sources and predators (e.g., termites)  
✅ Two movement modes: inertial (random) and sensory (pheromone-guided)  
✅ Configurable parameters for pheromone detection (`α`, `β`, `Q₀`)  
✅ JavaFX-based GUI for real-time visualization  

## 🛠️ **Technologies Used**  
- **Language**: Java  
- **OOP Concepts**: Inheritance, polymorphism, encapsulation  
- **GUI**: JavaFX for interactive visualization  
- **Algorithms**: Pheromone-based probabilistic movement (sigmoid detection function)  
## 🔧 **Installation & Execution**
### Prerequisites
- Java Development Kit (JDK) 18+

- JavaFX compatible IDE (IntelliJ, VS Code)

## 📌 **Key Implementation Details**
- Pheromone-Guided Movement: Uses PheromoneRotationProbabilityModel to calculate rotation probabilities based on pheromone concentration (sigmoid detection function).

- Toroidal Environment: Animals reappear on the opposite side when crossing boundaries.

- Class Hierarchy:

- Animal (base class) → Ant → AntWorker, AntSoldier

- Predator (e.g., Termite)

- Environment manages interactions between entities.

