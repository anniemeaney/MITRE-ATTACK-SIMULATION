# MITRE ATT&CK SIMULATION: Defending Cyborgia

Welcome to the **MITRE ATT&CK Game**, a technical simulation where you serve as the Castellan of Cyborgia. Your mission is to protect the realm from the Shadow Guild by strategically deploying defenses based on the real-world MITRE framework.

## 🛡️ Project Overview
This project is an interactive cybersecurity simulation developed to teach the application of defensive tactics against escalating adversarial threats. The game progresses through three levels of increasing difficulty as the Shadow Guild launches more complex attacks.

### The Team
*  Sophia Campione 
*  Anne Drago 
*  Annie Meaney 

---

## 🕹️ Gameplay Mechanics
The simulation is divided into three distinct phases to emphasize strategy and analysis:

1.  **Build Phase:** Utilize your "Intel Report" to analyze incoming threats and purchase defenses from the cabinet using the King’s Gold.
2.  **Attack Phase:** Launch a 3-second simulation to see how your defensive "sockets" hold up against the Guild's movement .
3.  **Mission Debrief:** The server evaluates your performance based on the **70% Rule**—you must cover at least 70% of the requirements for every attack in the round to succeed.

**Key Rules:**
*  **Persistence:** Built defenses stay on the board for subsequent levels, allowing for layered security.
*  **Health:** Your health is final and carries over between levels; if it hits zero, the kingdom falls.
*  **Edge Case Handling:** The game server prevents illegal moves, such as building during an active attack or placing defenses you cannot afford.

---

## 📁 Repository Structure
Based on the project's public-facing distribution, the following files are included in each download:

```text
├── MacOS/
│   ├── MITRE Game/            # Supporting assets for MacOS
│   ├── MITRE Game             # MacOS Application executable
│   ├── MITRE Game Teacher Resource Guide.pdf
│   └── MITRE Game User Guide.pdf
├── Windows OS/
│   ├── MITRE Game.exe         # Windows Application executable
│   ├── MITRE Game Teacher Resource Guide.pdf
│   └── MITRE Game User Guide.pdf
├── README.md                  # Project overview and setup
└── MITRE Game User Manual.pdf # Full system documentation
```

---

## 🚀 Installation & Setup

###  For Mac Users
1.   Download and unzip the MacOS package.
2.   Open your terminal and run the following command to clear the "quarantine" attribute:
    `xattr -dr com.apple.quarantine MITREGame.app`
3.   Launch the game from the folder.

###  For Windows Users
1.  Download and unzip the Windows package.
2.  Run `MITRE Game.exe` to begin.

---

## 📈 Future Scalability
The Kingdom of Cyborgia is built on a flexible backend designed for growth. Future developers can easily:
*  Extend the game beyond the initial three levels.
*  Add new MITRE ATT&CK techniques and defenses by inheriting existing framework logic.
*  Enhance the visual experience with custom sprites and detailed environments.

## 📚 Additional Resources
For more information, please refer to the following documents included in your download:
* **Teacher Resource Guide:** Detailed mapping of the simulation.
* **User Guide:** Comprehensive walkthrough of all interface elements.
* **Guidebook:** In-game button available to see a full breakdown of every defense.
