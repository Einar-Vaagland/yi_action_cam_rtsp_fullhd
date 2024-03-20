# Use the Yi Action 4K+ camera as an ip camera

## Stream HD 1920x1080 1.2Mb/s 48kHz video over RTSP. 

Using the live stream function, the camera will connect to a WiFi network, 
making it available to VLC or any other app using RTSP. Here’s how to do it.

## 1: On the phone 

Download, install and run [Yi Action Camera](https://www.xiaoyi.com/yi_action_camera/download_en.html) on your phone:
 
<img width="217" alt="yi1" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/fc0439ef-21ca-497d-9e61-118e2fd4ab01">
 

Select **Live** in the upper right corner:
 
<img width="255" alt="yi2" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/f6935de1-399e-416b-92a6-d9e8674248ac">


In the setup, enter these settings: 
 
<img width="176" alt="yi3" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/01c7ccbb-60fc-47f9-b858-10dd0eeb8c05">

**Live description**: Write anything, like **Yi**.

**Network for Live**: The **name** and **password** of your WiFi network.

**Live plattform**: Choose **Other** and write any web address, like **127.0.0.1**
 
<img width="171" alt="yi4" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/146da4f0-470c-47c6-8a16-e764134d47bf">
<img width="171" alt="yi5" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/489604f8-d205-4800-ba04-b32b5c1afef8">
 


Click **Start Live**:
 
<img width="173" alt="yi6" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/06449370-ffa4-46b1-833c-9d019e2a1487">

The app generates a **QR code** the camera can scan:
 
<img width="173" alt="yi7" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/24d90e1a-0b6b-481b-90a2-506c6f85dce2">

## 2: On the camera 

On the camera select **Live** on the main screen:
 
<img width="200" alt="yi8" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/55293ebb-4d3d-4fb3-9cc1-326aa6525645">

Scan the **QR code**:
 
<img width="198" alt="yi9" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/f6e451ba-9a37-4a6d-906a-573e38510d82">

The camera connects to the WiFi:
 
<img width="196" alt="yi10" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/b61dcdc3-3bf6-490e-9d10-8ba574a06ee3">

And when it fails to connect to a live server, the **setup is complete**.
 
<img width="197" alt="yi11" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/95e048b8-59c3-4cdf-b19b-a09ebd89d9f0">

The camera is now connected to the WiFi network, let’s **find the ip address**. 

## 3: On the PC 

Download, install and run [Advanced IP Scanner](https://www.advanced-ip-scanner.com/) on your computer:
  
<img width="266" alt="yi12" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/61435d47-9adc-412d-8ec4-de04a905cfe7">

Click **Scan**:
 
<img width="266" alt="yi13" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/ee292121-8a14-43ad-ab5d-120dd0ef7a1e">

The program scans the network for all available devices.

Look for the manufacturer **Shanhai Xiaoyi Technology Co., Ltd.** 

This is the Yi Action 4K+ camera. 

In this example we want the ip address **192.168.1.44**. 

Now we can **connect to the camera**.

Download, install and run [VLC](https://www.videolan.org) on your PC: 
 
<img width="266" alt="yi14" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/a9112188-8935-4e28-93eb-d4b9db87d8f0">

Select **Open Network Stream…**
 
<img width="170" alt="yi15" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/2038adec-2d0a-4dcf-8e8e-aaf774af0490">

Input **rtsp://192.168.1.44/live** and click **Play**.
 
<img width="232" alt="yi16" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/ea5f185b-a7ee-480c-ae0f-faa50567328e">

The video should be playing.
  
<img width="262" alt="yi17" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/b3798d1e-b4a0-4a8e-bda7-4db405b29046">

In full HD.
 
<img width="229" alt="yi18" src="https://github.com/Einar-Vaagland/yi_action_cam_rtsp_fullhd/assets/163604084/ef5f0720-c93b-463f-8cfc-179c2e7b68f0">

