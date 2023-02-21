# RTX3060ti에서 tensorflow 1 (1.15) 실행환경 구현
* Tensorflow 1버전의 코드를 RTX3060ti환경에서 수행을 해야 하는 상황이 발생
* RTX30XX 버전부터는 CUDA 11.1부터 지원
* 그러나 CUDA버전이 10인 환경에서 tensorflow 1.X버전을 사용 가능
* * [참고](https://forums.developer.nvidia.com/t/cuda-10-1-on-rtx-3090/185255)
---
* 참조사이트 링크
[참조1](https://sseongju1.tistory.com/62)

---
* Docker와 NVIDIA에서 제공하는 NGC(Nvidia GPU Cloud)를 사용해 해결
* Nvidia에서 공식으로 제공하는 Tensorflow 컨테이너와 벤치마킹을 위한 최신 모델을 제공함
* * [NGC참고링크](https://catalog.ngc.nvidia.com/)
---
# 2023/02/21~
* ros2 연습 git
* 에러수정후 수정 예정 -> 