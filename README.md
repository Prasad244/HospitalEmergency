# HospitalEmergency
A Java + swing based GUI which helps to assign priorities to patients based on their time of arrival, the severeness of the illness and the potential emergency cases that might arrive at the hospital

# **Patient Management System**

## **Overview**

This project is a simple **Patient Management System** built using Java's **AWT** and **Swing** libraries. The application allows users to fill out a form with various inputs such as patient age, type of illness, and other relevant attributes. The system manages the patients using a **first-come, first-served (FCFS)** approach, automatically dequeuing the first patient after a period of **30 seconds**.

## **Features**

- **Patient Registration Form**: Users can input patient details such as age, type of illness, and more.  
- **Illness Selection**: A combobox is provided with several options, including:  
  - **Heart Attack**
  - **Cardiac Arrest**
  - **Stroke**
  - **Pregnancy**
  - **Regular Checkup**
- **FCFS Queue Management**: The system assigns patients to a queue based on the time of form submission.  
- **Automatic Dequeueing**: After **30 seconds**, the first patient in the queue is automatically dequeued, and the next patient in line takes their place.

## **Technologies Used**

- **Java AWT**: For creating the graphical user interface components.  
- **Java Swing**: For handling events and managing user interactions.

## **How It Works**

1. **Form Submission**: Users fill in the patient details in the form and select the type of illness from the combobox.  
2. **Queue Management**: Patients are added to a queue based on the order of submission.  
3. **Automatic Processing**: Every **30 seconds**, the system automatically dequeues the patient at the front of the queue.  
4. **Next Patient**: After dequeuing, the next patient in the queue is processed.

## **Getting Started**

### **Prerequisites**

- **JDK 8** or later installed on your machine.

### **Installation**

1. **Clone the repository**:
    ```bash
    https://github.com/Prasad244/HospitalEmergency.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd HospitalEmergency
    ```
3. **Compile the Java files**:
    ```bash
    javac *.java
    ```
4. **Run the application**:
    ```bash
    java EmergencyQueue
    ```
   

### **Running the Application**

- After running the application, a form will appear where you can enter the patient details.  
- Choose the illness type from the dropdown menu and submit the form.  
- The system will handle the patient queue automatically, processing one patient every **30 seconds**.


## **Contact**

For any questions or feedback, feel free to contact me at prasadsatpute244@gmail.com 
