# Spare Parts Management System

The Spare Parts Management System is a comprehensive application designed to manage spare parts effectively. This README provides an overview of the project's flow and explains the functionality of each component.

## Project Flow

### Components

The project consists of the following major components:

1. **Warehouse Management:**
   - **Add Spare Parts:** Allows users to add new spare parts to the warehouse inventory.
   - **Update Spare Parts:** Provides the ability to update existing spare parts in the warehouse.
   - **Get Information:** Enables users to retrieve information about spare parts stored in the warehouse.

2. **Service Center Management:**
   - **Add Spare Parts:** Allows service center staff to add spare parts to the service center inventory.
   - **Update Spare Parts:** Provides the ability to update existing spare parts in the service center inventory.
   - **Get Information:** Enables service center staff to retrieve information about spare parts stored in the service center.

3. **Consumer:**
   - **Order Spare Parts:** Consumers can place orders for spare parts by specifying the Service Center ID and Zone ID. The service center fulfills these orders.
   
4. **Planning Team:**
   - **Request Spare Parts:** Service centers can request spare parts from the warehouse by providing their own ID and the warehouse ID. The warehouse fulfills these requests.

### Zones

There are four zones in the system:
- North Zone (Zone ID: 1)
- South Zone (Zone ID: 2)
- East Zone (Zone ID: 3)
- West Zone (Zone ID: 4)

### Naming Convention

The naming convention for spare parts is as follows: "modelname_partname." For example, a spare part for model Y1 named "camera" should be named "y1_camera."

This naming convention helps maintain a consistent and organized inventory of spare parts.

Feel free to explore each component's functionality to effectively manage spare parts in the system.
