🔥 Fire and Gas Detector Using Arduino
📌 Project Description

This project is a simple Fire and Gas Detector using Arduino Uno.
It detects:

Gas / Smoke using MQ-2 sensor

Fire / Flame using flame sensor

When gas or fire is detected, a buzzer turns ON to warn people.

🧰 Components Used

Arduino Uno

MQ-2 Gas Sensor

Flame Sensor Module

Active Buzzer

Breadboard

Jumper Wires

USB Cable

🔌 Circuit Connections
MQ-2 Gas Sensor

VCC → 5V

GND → GND

A0 → A0 (Arduino)

Flame Sensor

VCC → 5V

GND → GND

D0 → D2 (Arduino)

Buzzer

→ D8 (Arduino)

– → GND

⚙️ Working Principle

Arduino continuously reads the gas sensor and flame sensor.

If gas value is high or flame is detected, the buzzer turns ON.

If no danger is detected, the buzzer remains OFF.


  delay(200);
}

🧪 Testing

Open Serial Monitor (9600 baud)

Bring smoke near MQ-2 sensor → buzzer ON

Bring flame near flame sensor → buzzer ON

✅ Applications

Home safety system

Kitchen gas leakage detection

Fire alert system

Industrial safety (basic level)
