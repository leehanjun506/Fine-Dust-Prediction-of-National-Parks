# 국립공원 미세먼지 예측 서비스


## Description

본 프로젝트는 지정한 위치의 1일 뒤 미세먼지를 예측하는 서비스이다. 날씨는 시계열 데이터로 7일 단위로 데이터를 입력하여 "좋음", "중간", "나쁨", "매우나쁨"을 결과로 반환한다. 사용자가 원하는 지역을 선택하면 지역에 대한 현재 시간, 온도, 풍속 등 데이터를 확인할 수 있으며 원하는 공원 선택 시 공원의 1일 뒤 미세먼지 예측 결과를 확인할 수 있다. 



-----



## Environment

| Client                                                       | Server                                                       | Model                                                        |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| <img alt="html" src ="https://img.shields.io/badge/HTML-red"/> / <img alt="html" src ="https://img.shields.io/badge/JavaScript-brightgreen"/> | <img alt="html" src ="https://img.shields.io/badge/AWS-orange"/>/ <img alt="html" src ="https://img.shields.io/badge/Lambda-yellowgreen"/> / <img alt="html" src ="https://img.shields.io/badge/APIGateway-yellow"/> / <img alt="html" src ="https://img.shields.io/badge/Nodejs-green"/> | <img alt="html" src ="https://img.shields.io/badge/Keras(LSTM)-darkred"/> |



-----



## Project Structure

![프로젝트 설계 이미지3](https://user-images.githubusercontent.com/79822924/159753304-aed626a2-d8c6-437c-a3f5-aa6e357d34ba.png)



------






## Contents

```
Dust_Predict_Service/
├── client
│  └─ front.html
│  └─ currentweather.js
│  └─ pmrequest.js
│  └─ region.js
│  └─ package.json
│  └─ package-lock.json
│  └─ Good.jpg
│  └─ Medium.jpg
│  └─ Bad.jpg
│  └─ VeryBad.jpg
|  └─ node_modules
├── lambda_server
│  └─ weatherPM.js
└── model
   └─ train.py
   └─ flask.py
   └─ X_data.csv
```



-----



## Result

![시연 사진](https://user-images.githubusercontent.com/79822924/159752293-9f6061d8-f938-4107-9173-b9bd55169e3e.png)



------



## Demonstration Video

[Dust_Predict_DemonstrationVideo](https://www.youtube.com/watch?v=2D2PTczZHa4)
