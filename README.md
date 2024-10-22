# CCTV Recorder with Brightness and Contrast controller

이 프로젝트는 실시간 CCTV 비디오 스트림을 기록하고, 사용자가 밝기 및 대비를 조절할 수 있는 기능을 제공합니다. OpenCV를 사용하여 구현되었습니다.

## 기능

- **실시간 비디오 스트리밍**: RTSP URL을 통해 CCTV 카메라의 비디오 스트림을 실시간으로 표시합니다.
- **비디오 기록**: 녹화 중인 비디오를 AVI 형식으로 로컬에 저장합니다.
- **밝기 조절**: 사용자는 'w' 키를 눌러 밝기를 증가시키고, 's' 키를 눌러 밝기를 감소시킬 수 있습니다.
- **대비 조절**: 사용자는 'a' 키를 눌러 대비를 감소시키고, 'd' 키를 눌러 대비를 증가시킬 수 있습니다.
- **녹화 타이머**: 녹화가 진행되는 동안 화면에 경과 시간이 표시됩니다.

<br>

<img src="https://github.com/arombin/CCTV_Recorder_with_Brightness_Contrast_controller/blob/master/image/example.gif" width="600">


<br>

## 사용 방법

1. RTSP URL을 변경하여 자신의 CCTV 카메라 스트림을 입력합니다.
2. 스크립트를 실행하여 비디오 스트리밍을 시작합니다.
3. '공간' 키를 눌러 녹화를 시작하거나 중지합니다.
4. 'w' 키와 's' 키로 밝기를 조절합니다.
5. 'a' 키와 'd' 키로 대비를 조절합니다.
6. 'ESC' 키를 눌러 프로그램을 종료합니다.
