# Elevator Management System - Database Schema

## Overview
This project contains the Entity-Relationship (ER) diagram and database schema for a comprehensive **Elevator Management and Dispatch System**. It tracks building infrastructure, elevator operations, maintenance records, and ride assignments.

## Database Tables

### Static Infrastructure
- **Building**: Core building information (ID, name, location, type)
- **Floor**: Floors within buildings with floor numbers
- **Elevator_Shaft**: Physical shafts containing elevators
- **Elevator**: Individual elevators with capacity and current floor tracking
- **Elevator_Floor_Map**: Junction table mapping which elevators service which floors

### Dynamic Request Data
- **Floor_Request**: Customer requests for elevator service (includes direction and status)
- **Ride_Assignment**: Maps requests to specific elevators with timing information

### Operational Tracking
- **Ride_Log**: Historical record of all elevator movements
- **Elevator_Status**: Real-time status of each elevator
- **Maintenance_Record**: Tracks maintenance issues, dates, and status

## Key Features
- **Multi-building support** with multiple floors and shafts
- **Request management** with direction tracking (up/down)
- **Ride assignment** with pickup/drop time tracking
- **Maintenance logging** for operational monitoring
- **Status tracking** for real-time elevator availability

## Schema Structure
See `Schema.txt` for the complete ER diagram with all fields, primary keys, and foreign key relationships.
