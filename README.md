# Cash Register Management System

A **C# project** implementing a **3-tier architecture (UI, BL, DAL)** with **XML data storage**.  
The project demonstrates maintainable, reusable, and modular code layers for a simple cash register application.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Architecture](#architecture)
3. [Setup](#setup)
4. [Usage](#usage)
5. [Screenshots / Diagrams](#screenshots--diagrams)
6. [License](#license)

---

## Project Overview

This system is designed to manage cash register operations, including sales, inventory, and reporting.  
Key features:

- Modular 3-tier architecture:
  - **UI (User Interface)**: Handles user interactions and input.
  - **BL (Business Logic Layer)**: Implements core application logic and rules.
  - **DAL (Data Access Layer)**: Manages XML-based data storage and retrieval.
- Easy maintenance and task distribution.
- Reusable code layers for future extensions.

---

## Architecture

    +-----------------+
    |      UI Layer    |
    +-----------------+
             |
             v
    +-----------------+
    |  Business Logic  |
    +-----------------+
             |
             v
    +-----------------+
    | Data Access Layer|
    +-----------------+
             |
             v
         XML Files


---

## Setup

1. Clone the repository:

   git clone https://github.com/TovaShmuelevits/cash-register-management-system.git

2. Open the solution in Visual Studio 2022.

3. Restore any NuGet packages if needed.

4. Build the project.

## Usage

1. Run the application via the DotNet2025_0793_7214.sln solution.

2. Navigate through the UI to add, update, or delete records.

3. Data is saved in XML files under the DAL folder.F

Screenshots / Diagrams

(Optional: Add actual screenshots of the UI or architecture diagrams here.)

The ASCII diagram above represents the 3-tier structure.

License

This project is for educational purposes.
You can freely review and modify the code for personal learning.

