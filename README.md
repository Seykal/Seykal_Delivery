Hey guys 
This is my first script for FiveM, and I hope you find it useful. Feedback and suggestions are welcome as I continue to learn and improve my scripting skills.
## **Delivery Job Script**

### **Overview**

The Delivery Job Script adds an engaging delivery mission system to FiveM servers. Players can start a delivery job by interacting with an NPC, which involves spawning a vehicle, following a waypoint to a delivery location, and completing the job by reaching the destination.

### **Features**

* **NPC Interaction**: Players can interact with an NPC to initiate or cancel a delivery job.
* **Vehicle Spawning**: A vehicle is spawned near the player when starting a job.
* **Dynamic Waypoints**: A waypoint is set on the player's map to guide them to the delivery location.
* **Delivery Completion**: When reaching the delivery area and honking, the vehicle is removed, and the player receives payment.
* **Configurable Delivery Points**: Delivery locations and payment amounts are easily adjustable through a `config.lua` file.

### **Configuration**

* **`config.lua`**: This file contains the delivery points and associated payment amounts. The script uses this file to dynamically handle delivery locations.
* **Delivery Points**: You can define multiple delivery points with specific coordinates and payment amounts to customize where players will deliver vehicles and how much they’ll be paid.

### **Framework Used**

The script utilizes the **ESX** framework, a widely-used framework for FiveM servers that provides core features such as player management and in-game economy systems.

### **How to Use**

1. **Installation**: Extract the folder and place it into your server’s resource directory. The folder contains the script files (`client.lua`, `server.lua`, `config.lua`, and `fxmanifest.lua`) required for the delivery job.
2. **Configuration**: Modify `config.lua` to set your Delivery coordinates and configure delivery points with payment amounts.
3. **Start the Script**: Ensure the resource is included in your `server.cfg` and start your FiveM server.

### **Dependencies**

* **ESX Framework**: This script requires the ESX framework for managing player interactions and payments. Ensure that ESX is properly installed and configured on your server.
* 
Showcase : [Watch Script showcase Seykal_Delivery | Streamable](https://streamable.com/s900fo)
