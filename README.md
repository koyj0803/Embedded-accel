# 임베디드 시스템 기말고사 작품
## 팀원 : 1601675 황준원, 1601636 송호근
___
## 블록도
![가속도2](https://user-images.githubusercontent.com/103561996/175487207-0a29f44e-657f-422d-bebe-105624b11cc2.PNG)
___
### 구동 환경
#### Jetson Nano Kit(4GB), OS Ver: Ubuntu 18.04 (jetpack)
#### Rp2040
#### IDE:Thonny
___
## 작품 설명
### Thonny accel
#### 1. thonny에서 rp2040의 가속도센서를 활용하여 3초 동안의 가속도 값을 받아 평균을 구합니다.
#### 2. 평균 값을 mqtt를 사용하여 Jetson Nano의 Node-Red로 보냅니다.
#### 3. Node-Red dashboard에서 정지, 걷는지, 뛰는지를 text로 나타냅니다.
___
### 참고한 github
https://github.com/shkim1224/rp2040-mqtt-test/blob/main/rp2040_mqtt_test.py
___

## node-red flow
![가속도 노드레드](https://user-images.githubusercontent.com/65066914/174582831-d46b6292-9dac-4f29-b364-b0d5b69ec47c.PNG)

## 결과 영상
https://www.youtube.com/watch?v=ygLKSFusXfM
