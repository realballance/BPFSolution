# Reusable Business Process Flow Component (Power Apps)

## Overview
This project provides a reusable Business Process Flow (BPF) component built for Power Apps Canvas Apps. It enables developers to visually represent and manage multi-stage business processes with flexibility and consistency across applications.

The component is designed to simplify workflow tracking by providing a structured, configurable, and visually intuitive process flow experience.

---

## Features
- ✅ Dynamic stage-based progression
- ✅ Visual status indicators (Completed, In Progress, Not Started)
- ✅ Customizable colors and themes
- ✅ Configurable steps and labels
- ✅ Reusable across multiple apps
- ✅ Lightweight and easy to integrate
- ✅ Supports business logic for stage transitions

---

## Use Cases
- Approval workflows
- Sales pipelines
- Project tracking
- Onboarding processes
- Ticket lifecycle management

---

## Component Structure
- **Stages**: Defines each step in the process
- **State Logic**: Controls progression (Completed / In Progress / Not Started)
- **UI Layer**: Progress bar and step indicators
- **Configuration Inputs**: Allows dynamic customization

---

## Getting Started

### Import Component
1. import via Solution
2. Open your Canvas App
3. Go to **Insert → Get more components**
4. Import the component library

---

### Usage
1. Drag and drop the component into your screen
2. Configure:
   - Stage list
   - Current stage
   - Color theme (optional)
3. Bind it to your app data or logic

---

## Configuration Example

```powerapps
Stages: ["Start", "Review", "Approval", "Complete"]
CurrentStage: 2
