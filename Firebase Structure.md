Firebase Structure

Instead of:

{
  "soil": 68
}

We'll use something that can support many users and many ESP32s:

{
  "users": {
    "uid123": {
      "plants": {
        "plant1": {
          "name": "Aloe Vera",
          "deviceId": "ESP32-001",
          "soil": 68,
          "temperature": 29,
          "humidity": 73,
          "waterTank": 81,
          "battery": 7.8,
          "pump": false,
          "lastWatered": "2026-06-29 20:42"
        },
        "plant2": {
          "name": "Rose",
          "deviceId": "ESP32-002"
        }
      }
    }
  }
}
