# .NET Azure IoT Hubs Device-Twins Demo

A .NET Core Azure IoT Hubs Device Twins Demo App

# Instructions

- Create a new Azure IoT Hub in the Standard or Free Tier.
- Create an IoT Device.
- Add a Desired Property of;

```JSON
"<Name of desired property>": 10,
```

- Run the application with;

```
dotnet run
```

- Copy the Primary Key from the IoT Hub registryRead Shared Access Policy
- Paste into the console when prompted
- Copy the Primary Connection String from the IoT Device
- Paste into the console when prompted
- Copy the Device ID from the Device Details Page
- Paste into the conosle when prompted
- Enter the key name of the Desired Property you created above
- Enter the name of a Reported Property
- Change the Desired Property value in the Device Twin and hit the `Save` button.
- View the change in the console.
- Enter a value for the Reported Property.
- Refresh the Device Twin and view the Reported Property change.