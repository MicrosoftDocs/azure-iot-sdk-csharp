---
        public const string DeviceConnectionString = "<replace>";
-   Replace the above placeholder with device connection string you obtained in [Step 1](#Step-1:-Prerequisites) and save the changes.
-   Choose the right architecture (ARM) and set the debugging method to "Remote Machine":
-   To deploy the binaries on your device, right-click on the UWPSample project in the **Solution Explorer**, select **Properties** and navigate to the **Debug** tab:
    Type in the IP Address of your device. Make sure the "Use authentication" box is unchecked.
-   Build the solution.


-   See [Manage IoT Hub][lnk-manage-iot-hub] to learn how to observe the messages IoT Hub receives from the application.
-   See [Manage IoT Hub][lnk-manage-iot-hub] to learn how to send cloud-to-device messages to the application.