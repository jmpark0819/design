﻿#####4조
- 박지민([jmpark0819][member1])
- 김범영([tibyte][member2])
- 이재영([vkv6581][member3])
- 김영규([younggyu0906][member4])


#
##대중교통 혼잡도를 이용한 정보 제공 시스템

#####대중교통의 **혼잡도**를 활용하여 대중교통을 이용하는데에 도움을 주기 위한 시스템


## 필요성
---------

>*80명 대상 설문조사*

만원버스 | 불친절 | 배차간격 | 버스 노선 | 기타
:---: | :---: | :---: | :---: | :---:
27명 |  23명 | 15명 | 11명 | 4명



 - 설문조사 결과 많은 사람들이 **혼잡한 버스** 또는 **버스 운영**에 관해 불만이 많았다.
불만을 해결하기위하여 대중교통 이용에 도움을 주는 시스템이 필요하다.

#
## 시스템 개요
---------

```
본 시스템은 승하차 계수기, 중앙 서버, 사용자 단말기의 3가지 부분으로 나눌 수 있다.
```

- **승하차 계수기** : 버스에 설치되며, 센서를 이용하여 승차인원과 하차인원을 감지한다. 감지한 정보를 바탕으로 버스의 현재 승차인원을 계산하여 *중앙 서버*로 전송한다.

- **중앙 서버** : 버스의 *승하차 계수기*로부터 전송받은 데이터를 데이터베이스에 저장하고, *사용자 단말기*로부터의 요청이 있을 때 데이터를 제공한다.

- **사용자 단말기** : 스마트폰 애플리케이션 형태로, *중앙 서버*로부터 데이터를 전송받아 사용자에게 제공한다.


#
## 기존 관련 사례
-------------

###- *버스 승차 정보 제공 시스템 (삼성중공업 )*

> 1) 차량 단말기를 사용하여 버스 내부 정보를 생성한다.
>
> 2)  생성된 버스 내부정보에 기초하여 버스 승차 정보를 만든다.
>
> 3) 버스 내부 정보는 중앙 관제 서버에 전달된다.
>
> ![버스 정보](https://raw.githubusercontent.com/jmpark0819/Design/master/image/bus_info.png "bus_info")
>
> [출처 링크](https://patents.google.com/patent/KR20120057195A/ko)

-------------

###*- My Transport Singapore(싱가포르)*

>승객 혼잡도를 **초록, 노랑, 빨강** 색깔을 사용하여 **3단계**로 표시한다. 또한, **사용자의 위치 정보를 활용**하여 주변 택시 승강장 위치를 안내하고 주요 지역 주차장의 공석 정보를 확인할 수 있다.
>
>![싱가포르](https://github.com/jmpark0819/Design/blob/master/image/My_Transport_Singapore.png?raw=true)
>
> [출처 링크](http://www.hankookchon.com/bbs/app/103723)


[member1]: https://github.com/jmpark0819
[member2]: https://github.com/tibyte
[member3]: https://github.com/vkv6581
[member4]: https://github.com/younggyu0906
