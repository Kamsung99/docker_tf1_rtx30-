# RTX3060ti에서 tensorflow 1 (1.15) 실행환경 구현
* Tensorflow 1버전의 코드를 RTX3060ti환경에서 수행을 해야 하는 상황이 발생
* RTX30XX 버전부터는 CUDA 11부터 지원
* 그러나 CUDA버전이 10인 환경에서 tensorflow 1.X버전을 사용 가능
    [참고](https://forums.developer.nvidia.com/t/cuda-10-1-on-rtx-3090/185255)
* Docker와 NVIDIA에서 제공하는 
# 2023/01/02~
* ros2 연습 git
- - -
# 2023_01_02
- - -
* 우분투 20.04 버전 Vmware 안에 설치

* ROS2 설치:
	* foxy : sudo apt install ros-foxy-desktop ros-foxy-rmw-fastrtps* ros-foxy-rmw-cyclonedds*

* Ros2가 정상작동함을 확인 (test,pub, testsub를 통하여