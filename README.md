# Sensors System Architecture
Coursework of Systems Architecture itec3030

🧰 Java | 🤝 group assignment (team of 3) w/ [Chris](https://github.com/ZenonZeni?tab=repositories)👤 and T.👤 | 📚 YorkU <br>

🗂 Interfaces: all the interfaces JAR of need-to-be-implemented components of the systems<br>
🗂 JavaDocs: documentation for all the interfaces

📑prof's requirements: desgin the SmartHomeConsortium sensors system that devices from different vendors are able to implemented through the use of Interfaces.<br>
⚙️SHC system components:
- 🌡Sensors (collect temperature):
  - various temperature sensors
  - a thermostat (allow building habitants set desired temperature)
- 🌬Actuators (change the temperature): a furnace
- 📟Controller: receives data from sensors and issues actions to actuators
- Simple Smart Device Collaboration Standard (SSDCS) in form of a set of Java Interfaces: 
📦[SSDC](https://github.com/phganh/sensorArchitecture/blob/80786227e58a51d54d3d0cf95da3ba33c41991a8/Interfaces/Standards.jar)
📦[JavaDoc](https://github.com/phganh/sensorArchitecture/blob/80786227e58a51d54d3d0cf95da3ba33c41991a8/JavaDocs/Standards-javadoc.zip)
---
📑 implemnt the system to an apartment:
- [x] 🛋living room: 2 sensors OmniTempSensorXS3 by OmniTemp Inc
- [x] 🛏bedroom: 1 OmniTempSensorXS3
- [x] 🌬use SaharaFurnaceHL42 by Sahara GmbH for furnace component
- [x] complete the missing parts in Room, Building, Controller, Main classes to build the apt's system

🌡OmniTempSensorXS3:
📦[SSDCS-compliant driver](https://github.com/phganh/sensorArchitecture/blob/80786227e58a51d54d3d0cf95da3ba33c41991a8/Interfaces/ClassLibrary-Sensor1.jar)
📦[JavaDoc](https://github.com/phganh/sensorArchitecture/blob/80786227e58a51d54d3d0cf95da3ba33c41991a8/JavaDocs/OmniTempSensor-JavaDoc.zip)<br>
🌬SaharaFurnaceHL42:
📦[SSDCS-compliant driver](https://github.com/phganh/sensorArchitecture/blob/80786227e58a51d54d3d0cf95da3ba33c41991a8/Interfaces/ClassLibrary-Furnace.jar)
📦[JavaDoc](https://github.com/phganh/sensorArchitecture/blob/80786227e58a51d54d3d0cf95da3ba33c41991a8/JavaDocs/Furnace-JavaDoc.zip)

---
📑 implemnt thermostats-ThermoSetX19 to SHC system:
- [x] implement SSDCS-compliant driver for ThermoSetX19
- [x] build ThermoSetX19's documentation
- [x] implement ThermoSetX19 to the apartment



- [x] [Description and Models of the system](https://drive.google.com/file/d/1OYRd4QGu8zFz1OGtQFMtCy0CRYKcKgQq/view?usp=sharing)

✏️knowledge outcome:
- documentation style, interfaces, abstract classes
