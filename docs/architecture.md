# Water Healer – System Architecture

## 1. Architecture Overview

Water Healer is a modular, solar-powered floating water treatment and monitoring system designed for suitable surface water bodies such as rivers, lakes, ponds, and reservoirs.

The system is organized into five major layers:

1. Floating Platform
2. Water Intake and Treatment
3. Solar Power System
4. Monitoring and Control
5. Data Dashboard

## 2. System Flow

```text
                 SOLAR PANEL
                     |
                     v
              CHARGE CONTROLLER
                     |
                     v
                  BATTERY
                     |
          +----------+----------+
          |                     |
          v                     v
     WATER PUMP             ESP32 / MCU
          |                     |
          v                     |
   PRELIMINARY FILTER            |
          |                     |
          v                     |
   TREATMENT MODULES             |
          |                     |
          v                     |
      TREATED WATER              |
                                |
          WATER QUALITY SENSORS -+
                                |
                                v
                         DATA PROCESSING
                                |
                                v
                         MONITORING DASHBOARD
