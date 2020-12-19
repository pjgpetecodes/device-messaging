# .NET Azure IoT Hubs Device Messagin Demo

A .NET Core Azure IoT Hubs Device Messaging Demo App

# Instructions

- Create a new Azure IoT Hub in the Standard or Free Tier.
- Create an IoT Device.
- Install and run the Azure IoT Explorer Application - https://github.com/Azure/azure-iot-explorer/releases
- Copy the Connection String from the IoT Hub `iothubowner` Shared Access Policy
- Paste the Connection String into the IoT Hub Explorer Application where prompted
- Copy the Primary Connection String from the IoT Device

- Run the Demo application with;

```
dotnet run
```

- Paste into the console when prompted
- Enter a Message to Send to the IoT Hub
- Send a Cloud-to-Device Message with a property added using the Azure IoT Explore Application
- Invoke a Direct Method called `performUpdate` with a Payload using the Azure IoT Explore Application
- Monitor the Telemetry using the Azure IoT Explore Application
- Enter a Message into the Demo Application and view the message using the Azure IoT Explore Application