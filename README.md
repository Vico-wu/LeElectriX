

 <img src="./Assets/Images/LeE_LogoWithEnName.png" alt="MainView" width="500">

<p align="right">
    <span>English</span> |  
    <a href="../README.zh-CN.html">中文</a>
</p>

---
 # Le-ElectriX Flashing Tool User Manual

## Getting Started

### Software Setting

#### 1. Before using this software, please ensure that you have one of the following devices.
<div style="display: flex; justify-content: space-around; flex-wrap: wrap;">

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/CXUSBCANII.png" alt="CXUSBCANII" width="300">
    <p>ChuanXin Technology-USBCANII</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/CXCANalyst_Red.png" alt="CXUSBCANII" width="300">
    <p>ChuanXin Technology-CANalystII</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/CXCANalyst_White.png" alt="CANalystII" width="300">
    <p>ChuanXin Technology-CANalystII</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/GCUSBCANIIC.png" alt="CANalystII" width="300" >
    <p>GugangCheng Technology-GCUSBCANIIC</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/PCAN_USB.png" alt="PCAN_USB" width="300">
    <p>PEAK-PCAN_USB</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/VN1610.png" alt="VN1610" width="300">
    <p>Vector-VN1610</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/VN1630A.png" alt="VN1630A" width="300">
    <p>Vector-VN1630A</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/VN1640A.png" alt="VN1640A" width="300">
    <p>Vector-VN1640A</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/VN3600.png" alt="VN3600" height="200" >
    <p>Vector-VN3600</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/VN5640.png" alt="VN5640" width="300" >
    <p>Vector-VN5640</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/VN7610.png" alt="VN7610" width="300" >
    <p>Vector-VN7610</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/VN7640.png" alt="VN7640" width="300" >
    <p>Vector-VN7640</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/VN8900.png" alt="VN8900" width="300" >
    <p>Vector-VN8900</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/ZLG_USBCANFD_100U.png" alt="ZLG_USBCANFD_100U" width="300">
    <p>ZLG-USBCANFD_100U</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/ZLG_USBCANFD_100U_mini.png" alt="ZLG_USBCANFD_100U_MINI" width="300">
    <p>ZLG_USBCANFD_100U_MINI</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/ZLG_USBCANFD_200U.png" alt="ZLG_USBCANFD_200U" width="300">
    <p>ZLG-USBCANFD_200U</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/ZLG_USBCANFD_400U.png" alt="ZLG_USBCANFD_400U" width="300">
    <p>ZLG-USBCANFD_400U</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/ZLG_USBCANFD_800U.png" alt="ZLG_USBCANFD_800U" width="300">
    <p>ZLG-USBCANFD_800U</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/ZLG_USBCAN_2E_U.png" alt="ZLG_USBCAN_2E_U" width="300">
    <p>ZLG_USBCAN_2E_U</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/ZLG_USBCAN_4E_U.png" alt="ZLG_USBCAN_4E_U" width="300">
    <p>ZLG_USBCAN_4E_U</p>
  </div>

  <div style="text-align: center; margin: 10px;">
    <img src="./Assets/Images/ZLG_USBCAN_8E_U.png" alt="ZLG_USBCAN_8E_U" width="300">
    <p>ZLG_USBCAN_8E_U</p>
  </div>


</div>


#### 2. Install the drivers for the existing hardware

#### 3. Open the software and check if the corresponding hardware can be detected
<img src="./Doc/Images/MainView_En.png" alt="MainView" width="800">

If the hardware is not detected, please check if the driver is installed correctly. 

Alternatively, reconnect the hardware and click the refresh button to scan the hardware again.

#### 4. Import the license file.
<img src="./Doc/Images/SettingsView_En.png" alt="SettingsView" width="800">

After switching to the settings interface, click the import button next to 'Update License' to update the license file.

<img src="./Doc/Images/SettingsView_LicenseSucceed_En.png" alt="SettingsView" width="800">

---

### MCU software flashing

#### 1. Open the valid Hex file through the 'Browse Folder' button.

The image below shows a valid Hex file.

<img src="./Doc/Images/FlashingView_MCU_OverView_En.png" alt="SettingsView" width="800">

The image below shows an invalid Hex file, which may be encrypted, or the Hex file may correspond to an unsupported MCU model.

<img src="./Doc/Images/FlashingView_MCU_HexInvalid_En.png" alt="SettingsView" width="800">

#### 2. Click the download button to start the download

<span style="color: red;">Warning：</span>

<span style="color: red;"> Different versions of the Bootloader have different flashing logic. </span>

<span style="color: red;"> If clicking the download button does not initiate the download, it will appear as shown in the image below. </span>

<img src="./Doc/Images/FlashingView_MCU_RequestSession_En.png" alt="SettingsView" width="800">

<span style="color: red;"> Please try clicking the download button, then power off for 5 seconds and power on again.</span>

<span style="color: red;"> During this period, do not stop the host computer's download request. </span>

<img src="./Doc/Images/FlashingView_MCU_IsOnFlashing_En.png" alt="SettingsView" width="800">

<img src="./Doc/Images/FlashingView_MCU_FlashingSucceed_En.png" alt="SettingsView" width="800">

---

### Record Trace

#### 1. Open the device that needs to record Trace under the status module.
#### 2. Open the Trace button in the tool module.
#### 3. Click the export button and choose the save location.

Click the play button as shown in the image below.

<img src="./Doc/Images/Tools_RecordTrace_En.png" alt="SettingsView" width="800">

The button is red, indicating that it is in the recording state, as shown in the image below.

<img src="./Doc/Images/Tools_RecordTraceisOn_En.png" alt="SettingsView" width="800">

The following image shows how to export the Trace content to Vector, which can be replayed using CANalyzer or CANOE.

<img src="./Doc/Images/Tools_ExportToVector_En.png" alt="SettingsView" width="800">

The following image shows the Trace content that can be parsed by Vector.

<img src="./Doc/Images/Tools_VectorTrace.png" alt="SettingsView" width="800">

The following image shows how to export the Trace content to PCAN, which can be replayed using PCAN-Explorer.

<img src="./Doc/Images/Tools_ExportToPcan_En.png" alt="SettingsView" width="800">

The following image shows the Trace content that can be parsed by PCAN.

<img src="./Doc/Images/Tools_PcanTrace.png" alt="SettingsView" width="800">

---
### Trace Format Conversion

#### 1. Import the Trace file to be converted, which can be in the format of *.asc or *.trc.

<img src="./Doc/Images/Tools_OpenConvert_En.png" alt="SettingsView" width="800">

#### 2. Click the target format to generate (Vector for CANalyzer or CANOE, PCAN for PCAN-Explorer).

<img src="./Doc/Images/Tools_ConvertToVector_En.png" alt="SettingsView" width="800">

<img src="./Doc/Images/Tools_ConvertToPcan_En.png" alt="SettingsView" width="800">

#### Note: Conversion is also supported between the same type of formats, and during the conversion process, error frames and other alarm information will be filtered out.

---

## Changelog

### V1.0.0.13
1. Added compatibility for parsing the new Hex file format from Inovance. 
   The new Hex format has modified the file header and version information content. 
   If the new upper computer version is not used, the 0xB1 information verification service will fail.  
2. Added certificate classification functionality. 
   The displayed functional modules in the application will vary based on different certificate levels. 
   Currently, the classifications include RC controller DTC diagnostics, RC controller calibration, flashing, and Inovance upper computer calibration. 
   However, the calibration feature is not yet available.  
### V1.0.0.14
1. Added Bootloader flashing functionality for the F28384S chip based on the 240 joint development platform.
2. Adjusted CPU utilization logic by removing the 1ms wait time for each frame message. Due to time precision issues, the actual wait time was 5–15ms, which increased CPU load during the flashing process but significantly reduced the overall flashing duration.
3. Modified the logging logic during the message flashing process. New log entries will now appear at the top, and a log entry counter has been added.
4. Updated the progress bar control. The original control caused unclear flashing progress display in dark mode. The updated control now provides a clear display.

### V1.0.0.15  
1. Added a tool module for exporting message traces:  
   a. Supports exporting the entire network content in Vector ASCII format or PCAN trace format.  
   b. Added a trace conversion feature to convert Vector ASCII files into PCAN trace format files.  
   c. Added a trace conversion feature to convert PCAN trace files into Vector ASCII format files.  
   d. During format conversion, warnings or error contents in the records will be filtered out.  

### V1.0.0.16 

1. Added MCU Flash ID modification functionality to update the MCU when the Hex file information does not match the actual Flash ID.
2. Added MCU Flash ID scanning functionality, allowing users to select the chip model to be scanned. After starting the scan, a 20-second Flash ID scanning process will begin.
3. During this period, if results are found, they will be displayed in the dropdown list of scanned IDs.
4. Added a one-click Flash ID modification feature. It is recommended to use this feature in conjunction with Bootloader updates; otherwise, subsequent program updates may fail.

### V1.0.0.17
1. Bug Fix: The PCAN record encoding into Vector format causes data misalignment, resulting in inconsistencies between the converted content and the original data. Update this issue.

### V1.0.1.0  
1. Added DBC parsing functionality.  
2. Added DBC merging functionality.  
3. Added DBC-to-Excel conversion functionality, currently supporting both `.xls` and `.xlsx` formats.  

### V1.0.1.1
1. Bug Fixes:   
    - Fixed an issue where files with multiple formats during the DBC merging or conversion process could not be automatically recognized. 
    Now, source files can be in any of the following formats: .dbc, .xls, or .xlsx. All formats can be intelligently parsed and converted.

### V1.0.1.2
1. Bug Fixes:
    - Fixed the parsing error problem where the information of newly added cell nodes was null when parsing Excel into DBC.
2. Function Optimizations:
    - Optimized the parsing algorithm for PCAN records. The compatibility with previous versions has been expanded from V1.1 and V1.3 to V1.0, V1.1, V1.3, V2.0, and V2.1. The parsing logic has been optimized as well.

### V1.0.1.3
1. Bug Fixes:
    - Fixed an issue where the conversion from PCAN logs to Vector logs would fail when the data length was less than 8.

### V1.0.2.0
1. New Features:
    - Added compatibility for the Vector VN1610 device.
    - Added compatibility for the ZLG USBCANFD-200 device.
    - Added compatibility for the Chuangxin device.

### V1.0.3.0
1. New Features:
    - Added automatic CAN baud rate scan functionality for ZLG devices.
    - Added compatibility for all Vector devices.
    - Added Chuangxin hardware device type detection.
    - Added compatibility for all ZLG can devices.
### V1.0.3.1
1. Bug Fixes:
    - Fixed the issue where RC40 UDS flashing failed and device information could not be retrieved.

### V1.0.4.0
1. Bug Fixes:
    - Fixed the issue where the device could not be turned off after the hardware connection was disconnected.
    - Fixed the slow dynamic update of device connection status and baud rate value.
    - Fixed the issue of excessive load during the calibration process.
    - Fixed the issue where only one MCU could be detected during the MCU scanning process. Now it scans for a fixed duration of 10 seconds.

2. New Features:
    - Added parameter calibration functionality for Enpower.
    - Added modification and reading functionality for commonly used Enpower parameters.
    - Added a highlight display feature for values that change after batch parameter writing.
    - Added batch parameter writing and batch export functionality.
    - Added a function to batch export parameters to code (first 293 parameters).
    - Added a function to convert parameter files into code in batches (first 293 parameters).
    - Added a data check and missing parameter prompt feature when converting parameter files to code (first 293 parameters).
    - Added dynamic adjustment of CPU usage for calibration and flashing threads to reduce CPU load.
    - Added a Hex dynamic refresh information feature.
    - Added a direct navigation feature to path files.

### V1.0.4.1
1. Bug Fixes:
    - None

2. New Features:
    - Added a feature to prevent accidental triggering of buttons on the MCU default parameter page.
    - Added independent certificate verification for the MCU default parameter page; the original certificate file cannot access this page.
    - Added an interface for setting thresholds related to MCU speed on the MCU default parameter page.

### V1.0.4.2
1. Bug Fixes:
    - Fixed the issue of duplicate parameter display after importing Excel in Enpower.
2. New Features:
    - None

### V1.0.4.3
1. Bug Fixes:
    - None
2. New Features:
    - Added MCU extended parameter search functionality

### V1.0.4.4  
1. Bug Fixes:  
   - Fixed an issue where the flashing tool couldn't load parameter files when the Excel file was open  

2. New Features:  
   - Enhanced Trace saving experience by adding navigation prompts to the target folder  
   - Enhanced Trace conversion experience by adding navigation prompts to the target folder  
   - Enhanced DBC export experience by adding navigation prompts to the target folder  
   - Enhanced Excel export experience by adding navigation prompts to the target folder  
   - Improved Excel parsing logic - now skips empty rows to prevent parsing issues  
   - Added new firmware version upgrade functionality  
---

### Respositary URL See [releases](https://rb-svn1.de.bosch.com/svn/c113_ELMOCN_Master/branches/01_Toolchain/04_CSharp/03_LeElectriX_FlashTool/LeElectriX_FlashTool/bin/Release).


---
