# 세미나 (환경설정 진행관련)
<br>

## GPU에 맞는 NVIDIA 드라이버 설치
Q. NVIDIA 드라이버 왜 필요할까요? <br>

A. 많은 연산을 cpu에서만 담당하게 되면 cpu가 해야할 컴퓨터의 프로세스 관리 업무를 효율적으로 수행하지 못할 뿐더러 요구되는 연산 처리에 대한 소요시간이 증가하기 때문에 gpu를 활용해야 하고 이 때 필요한게 gpu 드라이버

<p align="center">
  <img src="https://github.com/user-attachments/assets/9e9e7879-0b21-428a-b9db-41526f73d75e" width="600px" height="500px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8fbbb298-31a7-425f-864e-56b831f96e4a" width="600px" height="500px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e016f113-9341-4546-8000-49dbe1605f40" width="600px" height="300px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/29e40d46-09ee-489d-bbf9-4760fd0e7d1b" width="600px" height="300px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bfbc2918-f094-4cbc-8904-220ff90f90a0" width="600px" height="300px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/eb5eedf8-d568-48a2-9867-eefc9429e7fc" width="600px" height="300px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bfbc2918-f094-4cbc-8904-220ff90f90a0" width="600px" height="300px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bfbc2918-f094-4cbc-8904-220ff90f90a0" width="600px" height="300px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b707d68f-301b-4486-b042-ee060a6a5682" width="600px" height="300px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c0545f1d-27d3-432c-9099-67df0d0bac64" width="600px" height="300px">
</p>


## Pycharm설치

----

<!-- 이미지 정렬과 크기 조정 -->
<p align="center">
  <img src="https://github.com/wu-sung/seminar-2024-07-11-/assets/119473043/8badb8ab-8df0-417f-b186-05f0b9536722" width="800px" height="700px">
</p>

<br>

<p align="center">
  <img src="https://github.com/wu-sung/seminar-2024-07-11-/assets/119473043/5f197811-2236-4dd9-b308-2ad8cd427360" width="800px" height="700px">
</p>

<p align="center">
  <img src="https://github.com/wu-sung/seminar-2024-07-11-/assets/119473043/afe11694-fbc7-4655-95af-293d72943c23" width="800px" height="700px">
</p>

<p align="center">
  <img src="https://github.com/wu-sung/seminar-2024-07-11-/assets/119473043/09957b7f-8177-4854-a363-10841d1f8bd6" width="800px" height="700px">
</p>

<p align="center">
  <img src="https://github.com/wu-sung/seminar-2024-07-11-/assets/119473043/79f4da44-4dc1-4479-82e1-7dc09b00f45e" width="800px" height="700px">
</p>

<p align="center">
  <img src="https://github.com/wu-sung/seminar-2024-07-11-/assets/119473043/e44f634b-bbcd-4b69-82dc-a3e663be5907" width="600px" height="400px">
</p>

### 위의 과정을 거치며 pycharm education (무료버전) 설치를 완료합니다.

----

## CUDA Toolkit 설치

Q. CUDA는 왜 필요한가요? <br>

A. CUDA(Computed Unified Device Architecture) NVIDIA 사에서 개발한 GPU (Graphic Processing Unit)개발 툴루써
많은 양의 연산을 동시에 처리하기 위해 사용


<p align="center">
  <img src="https://github.com/user-attachments/assets/5f89bc5e-4e67-4504-bf89-6733699929a0" width="600px" height="500px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/35f4085d-99ec-45d1-9652-15cabda4cf84" width="600px" height="500px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/62dcf530-803c-4548-8230-a837238ba268" width="600px" height="500px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1c1822a8-2599-4bb0-b99c-d69e5f1241a0" width="600px" height="500px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/dd1dee9b-6d80-4690-b6f1-131ff561cc78" width="600px" height="500px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8374265d-92d2-4b8d-8e32-41fb5c894065" width="600px" height="500px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f8aa8611-f9bb-42f2-9407-68e19a4929d8" width="600px" height="500px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cbdae225-9b24-4077-a50a-1106480f96b5" width="600px" height="500px">
</p>

### 위의 과정을 거쳐 CUDA(12.2)의 설치를 완료

----

### 버전에 맞는 cudnn 설치

## cuDNN이란? <br>
#### 딥 러닝 및 인공 신경망(ANN) 프레임워크를 가속화하기 위한 라이브러리 (convolution, pooling, normarization, activation)

<p align="center">
  <img src="https://github.com/user-attachments/assets/115a3758-42b7-4ec9-ad7e-c04a02e441dc" width="600px" height="500px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7c92a0ef-7503-4800-ac49-c9e3860e0b9c" width="600px" height="500px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1fe05ae2-f5ab-4d58-b85e-0bef04eada37" width="600px" height="500px">
</p>

https://developer.nvidia.com/rdp/cudnn-archive <br>

### 위의 사이트를 참고하여 버전에 맞게 cudnn을 설치 <br>
### 설치 후 bin, include, lib, cudnn.txt파일을 cuda toolkit을 설치했던 파일경로에 넣어준다.  <br>

- C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v12.2
위의 경로로 들어가 bin, inlucde, lib디렉터리 위치를 확인 해준다. <br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/070b495c-974a-4a21-9f94-07508889df08" width="600px" height="500px">
</p>

압축풀기가 된 cuDNN파일에 들어가 각각의 파일들을 옮긴다.(bin, include, lib) <br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cb4990cd-16f7-44c7-8a75-3de9871330f1" width="600px" height="500px">
</p>


넣은 후 환경변수 편집에 들어가 path에 각각 경로를 지정하여 넣어준다. <br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/99c79cf1-a941-420f-8bbe-e70d902eed18" width="500px" height="200px">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/90975db3-68c5-47b7-98d9-b341dcfab16a" width="700px" height="370px">
</p>

* nvcc --verison 명령어를 쳤을 때 위의 사진처럼 나온다면 CUDA라이브러리가 잘 설치된 것
----
<p align="center">
  <img src="https://github.com/user-attachments/assets/e51d1f2f-ca29-4238-b8dd-e2cf0d9a4c4b" width="700px" height="370px">
</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/079e56ad-ab4c-447f-a694-1376557f57c8" width="700px" height="370px">
</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/6fa788bf-183c-41eb-9e8c-096d28cd3312" width="700px" height="600px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b80d3713-e770-40ee-a8d2-d2a9e1cbc0f4" width="700px" height="350px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/677d9c9d-2b69-41b2-a674-90c8bcf2cf94" width="700px" height="600px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/90813e30-6b85-4557-a198-5a1e0999d032" width="700px" height="600px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/90813e30-6b85-4557-a198-5a1e0999d032" width="700px" height="600px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a7ecb86e-6045-4f0a-95a6-8de531b357c5" width="700px" height="600px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/a7ecb86e-6045-4f0a-95a6-8de531b357c5" width="700px" height="600px">
</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/e6812f42-4983-4d48-9446-765fb4f6ad56" width="700px" height="600px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4b579ca2-243a-4797-802d-1027a44452f5" width="700px" height="600px">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ea0b999d-bae8-4515-9a57-2580044c3bf0" width="700px" height="600px">
</p>


### pytorch 및 torchvision 설치 (버전 호환 중요)
https://pytorch.org/get-started/previous-versions/
위의 사이트 참고 <br>

pkg 설치시 오류가 발생하는 이유는 대표적으로 '버전 충돌'인데 왜 발생할까라는 의문이 들었고 이를 찾아본 결과<br>

기존 패키지를 설치하게 되면 cpu로 동작하게 하는 패키지로 설치가 된다.<br>

### 이를 해결하기 위해서는 어떻게 해야할까? <br>
- 따로 버전을 타겟팅해서 실행을 하면 된다. <br>
<br>
<br>
## 토익 공부 ##
1. RC를 하면서 몰랐던 단어를 필기 및 암기
2. LC에 집중하여 듣고 있고 들리지 않던 발음을 들리게끔 연습하고 있다.

- 어떻게 들리게 하는가?
대체적으로 LC를 할 때 듣고 흘리게 되는 경우의 원인을 생각해보면 내가 몰랐던 단어이거나
평소 들어보지 못한 발음 및 연속적으로 이어지는 발음으로 인해 알아듣지 못하는 경우가 대다수이다.

이를 해결하기 위해서는 음원보다 더 빠르게 문장을 읽으며 발음을 연습하는 것이다.
또한 내가 아는 단어들이라 해서 넘겨짚을 게 아니라 상황에 따라 해석되는 뜻이 다르므로 손으로 직접 써보며 머리에 새기는 것이 좋은 방법이라 생각한다.





