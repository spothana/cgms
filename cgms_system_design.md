# Continuous Glucose Monitoring System (CGMS)
## System Architecture & Safety Design

---

## 1. System Context
![System Context](out/documents/diagrams/context/cgms_context/cgms_context.png)

---

## 2. System Architecture (SysML)

### 2.1 Block Definition Diagram
![BDD](out/documents/diagrams/sysml/cgms_bdd/cgms_bdd.png)

### 2.2 Internal Block Diagram
![IBD](out/documents/diagrams/sysml/cgms_ibd/cgms_ibd.png)

---

## 3. Interfaces

### 3.1 BLE GATT Interface
![BLE GATT](out/documents/diagrams/interfaces/cgms_ble_gatt/cgms_ble_gatt.png)

### 3.2 Cloud API Interface
![Cloud API](out/documents/diagrams/interfaces/cgms_cloud_api/cgms_cloud_api.png)

### 3.3 Sensor Interface
![Sensor IF](out/documents/diagrams/interfaces/cgms_sensor_if/cgms_sensor_if.png)

---

## 4. Software Design (UML)

### 4.1 Class Diagram
![Class Diagram](out/documents/diagrams/uml/cgms_class/cgms_class.png)

### 4.2 Sequence Diagram
![Sequence Diagram](out/documents/diagrams/uml/cgms_sequence/cgms_sequence.png)

### 4.3 Sensor Lifecycle State Machine
![State Machine](out/documents/diagrams/uml/cgms_sensor_state/cgms_sensor_state.png)

---

## 5. Safety & Risk Management

### 5.1 Safety-Critical Data Flow (IEC 62304)
![Safety Flow](out/documents/diagrams/safety/cgms_safety_flow/cgms_safety_flow.png)

### 5.2 Fault Handling
![Fault Handling](out/documents/diagrams/safety/cgms_fault_handling/cgms_fault_handling.png)

### 5.3 Alarm Path
![Alarm Path](out/documents/diagrams/safety/cgms_alarm_path/cgms_alarm_path.png)

### 5.4 Fault Tree Analysis (ISO 14971)
![FTA](out/documents/diagrams/safety/cgms_fta/cgms_fta.png)
