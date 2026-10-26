# Water Healer – Test Cases

## 1. Purpose

These test cases are intended to verify the basic operation of the Water Healer prototype.

## 2. Water Intake Test

**Objective:** Verify that the pump can draw water into the system.

**Procedure:**
1. Place the intake in the test water container.
2. Power the pump.
3. Observe the water flow.

**Expected Result:**  
Water should enter the treatment system without major leakage.

## 3. Preliminary Filtration Test

**Objective:** Verify removal of larger debris.

**Procedure:**
1. Pass water containing visible debris through the preliminary filter.
2. Inspect the filter outlet.

**Expected Result:**  
Large debris should be retained by the preliminary filter.

## 4. Sensor Test

**Objective:** Verify that the sensors provide readings.

**Procedure:**
1. Connect the sensors to the microcontroller.
2. Power the system.
3. Observe the sensor readings.

**Expected Result:**  
The microcontroller should receive and display sensor readings.

## 5. Solar Power Test

**Objective:** Verify power generation and battery charging.

**Procedure:**
1. Connect the solar panel to the charge controller.
2. Connect the battery.
3. Expose the solar panel to suitable sunlight.
4. Monitor the charging status.

**Expected Result:**  
The system should receive power from the solar panel and charge the battery when conditions are suitable.

## 6. Dashboard Test

**Objective:** Verify that water-quality data can be displayed.

**Procedure:**
1. Send sample sensor data to the dashboard.
2. Open the dashboard.
3. Check the displayed values.

**Expected Result:**  
The dashboard should display the received sample readings correctly.

## 7. Integrated Prototype Test

**Objective:** Verify interaction between major system modules.

**Procedure:**
1. Connect the floating platform, pump, filtration, sensors, controller, and power system.
2. Start the system.
3. Monitor operation.

**Expected Result:**  
The connected modules should operate together without unexpected failures.

## 8. Data Logging Test

**Objective:** Verify that sensor readings can be recorded.

**Procedure:**
1. Generate or collect sensor readings.
2. Record the readings with timestamps.
3. Review the stored data.

**Expected Result:**  
The readings should be stored with corresponding timestamps.

## 9. Safety Check

Before testing, inspect:

- Electrical connections
- Waterproofing
- Pump connections
- Battery connections
- Floating stability
- Loose wires
- Water leakage

Testing should be performed under controlled conditions.

## 10. Prototype Status

These are planned prototype test cases. Actual test results should be added only after the corresponding tests have been performed and measured.
