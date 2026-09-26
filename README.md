# SmartWash 🚿

### Smart Washroom Monitoring & Cleaning System

An academic prototype designed to monitor washroom occupancy and
cleanliness conditions and provide a mechanism for timely cleaning.

## 📌 Overview

SmartWash was developed as an ECS academic project with the idea of
making washroom maintenance more responsive through sensor-based
monitoring.

The system considers multiple conditions inside the washroom and
provides an external status indication when the washroom becomes
overcrowded or requires attention.

## 💡 Key Features

- Occupancy monitoring based on a predefined threshold
- External LED/LCD status indication
- Odor-based cleanliness monitoring
- Water/moisture detection near the lower section
- Condition-based cleaning trigger concept
- Prototype developed using electronic components and jumper-wire
  connections

## ⚙️ System Concept

```text
             ┌─────────────────────┐
             │      Washroom       │
             │                     │
             │  Occupancy Sensor  │
             │         │           │
             │  Odor Sensor       │
             │         │           │
             │  Water Sensor      │
             └─────────┬───────────┘
                       │
                       ▼
              ┌─────────────────┐
              │ Control Circuit │
              └────────┬────────┘
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
       Status Display       Cleaning Trigger
        LED / LCD              Mechanism
