# Airproof Drone Products Management

## Introduction
This document outlines the process for managing drone products and manufacturing operations at Airproof.

## 1. Creating New Products:

- Drone Y
- Drone Battery
- Drone Blades
- Drone Plastic Structure
- Drone Engine

## 2. Setting Reordering Rules for Drone Y:

- Navigate to `Inventory` > `Configuration` > `Reordering Rules`
- Add a new rule for Drone Y with minimum and maximum quantities set (5 to 20 units).

## 3. Creating a Drone Kit:

### Components:
- 1 Drone Case
- 1 Drone Y
- 1 Pack of Drone Lights
- 1 Airproof Backpack

- Create a Bill of Materials (BoM) with BoM Type: Kit.

## 4. Manufacturing Drone 4.0:

- Unarchive MTO (made to order) in `Inventory` > `Configuration` > `Warehouses` > `Pick a warehouse` > `Routes`.
- Edit the Drone 4.0 product template:
  - Navigate to `Manufacturing` > `Products` > select Drone 4.0.
  - In the Inventory tab, under Operations, select Replenish on Order (MTO) and Manufacture.
- Create a Bill of Materials for Drone 4.0:
  - Product: Drone 4.0
  - Components: Battery, Blade, Plastic structure, Engine, Waterproof Camera
  - BoM Type: Manufacture this Product
  - Operations:
    - Assembly: Assembly Station, Duration: 45 minutes
    - Painting: Painting Station, Duration: 60 minutes
    - Waterproof Camera Assembly: Assembly Station, Duration: 25 minutes

These steps should help organize the process of creating products, managing reordering rules, creating kits, and manufacturing Drone 4.0.
