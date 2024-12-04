## 차트 데이터 샘플
차트 데이터는 보통 nssao에서 사용하는 차트 데이터로 생각하면 될 것 같습니다. 범례가 엄청 많아진다거나.. 데이터가 엄청 달라진다거나 그러진 않을 것 같습니다. 그저 nssao에 있는 그대로만...

아래는 차트 예시와 출처입니다.

![title](https://www.nssao.or.kr/situaction/images/000002/20181212155307238_HMR5W5FS.png)   
![title](https://www.nssao.or.kr/situaction/images/000003/20190719212419219_7J1XSHZL.png)     
![title](https://www.nssao.or.kr/situaction/images/000002/20181211150903139_R97TQ8PL.jpg)   
![title](https://www.nssao.or.kr/situaction/images/000003/20190717110830602_7Q397V4P.jpg) 
![title](https://www.nssao.or.kr/situaction/images/000002/20181217125342235_W3XK3Z79.jpg) 

https://www.nssao.or.kr/html/35

위에서 사용된 차트 svg 파일도 같이 여기 repository에 올렸습니다. 디자인에 도움이 될진 모르겠지만... 더 필요한거 있으면 말씀해주세요ㅠ


## 차트 라이브러리
사용할 라이브러리는 visx 아니면 recharts, nivo 사용 생각하고 있습니다. 그래프 디자인에 따라 셋 중에 하나 고르려고합니다.

### nivo
커스텀 자유도가 높습니다. 다만 multi axis가 안되는 것으로 알고있습니다.

nivo가 제일 데모 홈페이지가 잘되어있어 있습니다.
데모 페이지에서 custom도 가능하더라구요. 아마...차트 디자인시에 참고하셔도 좋을 것 같습니다...

https://nivo.rocks/bar/

### visx
역시 커스텀 자유도가 높은 편이라 디자인 구현 시 제약사항은 없을 것 같습니다.
얘는 multi axis도 지원합니다.
아래는 차트 샘플입니다.

https://airbnb.io/visx/gallery


### recharts
차트, 툴팁 등 커스텀이 가능하지만 visx, nivo 보다는 자유도가 높진않습니다. 그래도 아마 다 되긴할거같아요 

아래는 차트 샘플 사이트입니다.
https://recharts.org/en-US/examples
