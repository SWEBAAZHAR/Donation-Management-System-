Java-based application designed to efficiently manage donors, track financial contributions, and maintain organizational records. This project demonstrates practical implementation of core Object-Oriented Programming (OOP) principles and transitions from a console-based architecture to a fully functional Graphical User Interface (GUI).
Features
Donor & Donation Tracking: Add, manage, and filter donor profiles and their associated donation records.

Graphical User Interface (GUI): Provides an intuitive and user-friendly interface for seamless interaction, upgrading from the initial console-based system.

Persistent Data Storage: Implements file handling to save and load donation data. Transitions from basic object serialization to a human-readable CSV format for better data accessibility.

Advanced Filtering Logic: Easily query and filter records to locate specific donations or donor profiles.

 Tech Stack
Language: Java

Concepts: Object-Oriented Programming (OOP), Data Persistence, Event-Driven Programming

Storage: CSV File Handling / Serialization
OOP Concepts Applied
This system was architected using strict OOP methodologies to ensure modularity and code reusability:

Inheritance: The Donor class extends the base Person class to inherit common attributes while adding specific donation-related properties.

Association: Establishes a clear relationship where a Donation object has an associated Donor.

Aggregation: The Organization class contains a list of Donation objects, demonstrating a "has-a" relationship where donations exist independently but are grouped under the organization.

 How to Run
Clone this repository to your local machine:

Bash
git clone https://github.com/SWEBAAZHAR/[Donation-Management-System-].git
Open the project in your preferred Java IDE (such as IntelliJ IDEA, Eclipse, or VS Code).

Ensure your IDE is configured with the standard Java Development Kit (JDK).

Compile and run the main application file to launch the GU
