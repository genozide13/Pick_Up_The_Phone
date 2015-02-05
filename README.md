# Pick_Up_The_Phone
Answer a call by using Proximity Sensor and Light Sensor.

Permission 
<uses-permission android:name="android.permission.READ_PHONE_STATE" />
<uses-permission android:name="android.permission.RECEIVE_BOOT_COMPLETED" />

Services
RD - Wait for a call > start LD
LD - Check for light, no light > Pre_PD : light detected > PD
Pre_PD - Wait for sensor value change > start PD
PD - Detect near Proximity and answer a call
