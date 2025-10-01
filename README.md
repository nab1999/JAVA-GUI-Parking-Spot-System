# GUI Parking Spot System  
<img width="1918" height="1012" alt="image" src="https://github.com/user-attachments/assets/6e13c898-7641-4072-9018-8ae1a547e771" />
<img width="1600" height="762" alt="image" src="https://github.com/user-attachments/assets/7dd69138-b3bf-4d7c-90eb-0f42ba8c05db" />

## Project Overview  
This project implements a Java-based **Parking Spot System with a Graphical User Interface (GUI)**. The system allows users to manage staff and visitor parking slots through an interactive interface built with Swing and AWT.  

### Features  
- Creation of staff and visitor parking slots  
- Add or remove parking slots  
- Park, find, and remove cars  
- Click-based interactions with parking slots (double-click to add/remove cars, right-click to delete slots)  
- Real-time clock display and parking time tracking  
- Display of all slots with a scrollable view  

---

## Tools & Technologies  
- Java  
- BlueJ IDE  
- Swing and AWT libraries  
- Components: `JFrame`, `JPanel`, `JButton`, `JLabel`, `JTextField`, `JTextArea`, `JScrollPane`, `JOptionPane`, `Timer`  
- Layout Managers: `GridLayout`, `BorderLayout`, `FlowLayout`  

---

## Event Handling Functions  
- `initializeWelcomeGUI()` – Launches welcome window for slot setup  
- `submitSlots()` – Validates input and transitions to main GUI  
- `addParkingSlot()` / `removeParkingSlot()` – Add or delete slots  
- `parkingCar()` / `findCar()` / `removeCar()` – Manage cars in slots  
- `clickAddRemoveCar()` – Double-click slot to add/remove cars  
- `clickRemoveSlot()` – Right-click slot to remove it  
- `displayAllSlots()` – Shows all slots in a scrollable window  
- `updateClock()` – Updates time display in real time  

---

## How to Run (BlueJ App) 
1. **Extract Files**  
   - Unzip the project files into a folder on your computer.  

2. **Open in BlueJ**  
   - Open BlueJ → go to `Project` → `Open Project` → select the project folder (e.g., `Project2`).  

3. **Run**  
   - Locate the main GUI class, right-click it, and select `void main(String[] args)`.  

4. **Set Up**  
   - A Welcome window will prompt for the number of staff and visitor slots.  

5. **Use the Application**  
   - After setup, the Main GUI window opens to manage parking slots.  

---

