# 2주차 과제 float을 사용하여 이미지 만들기

## 사용한 코드

- 아바타 이미지는 배경 방식이 아닌 콘텐츠 이미지로 마크업 한다. <br>
  -> 이미지 삽입을 위한 img src 를 통한 코드 사용 <br>

- 이미지 상태 최적화 방법에 대해 고민해본다.<br>
  -> 이미지의 로딩을 천천히 재누느 방향으로 코드 사용 <br>
  -> loading="lazy를 적용하여 로딩 속도를 지연 <br>

- 아바타 이미지의 크기 64px \* 64px <br>
  -> 이미지 크기는 width, height 의 코드를 사용 <br>

- 아바타 이미지 간의 간격 - 20px <br>
  -> style=margin-right: 20px; 코드를 사용하여 이미지간 간격 조절 <br>

- 이미지 상단의 Avatars 제작 <br>
  -> h1 코드로 입력 후, CSS 부분에서 font-size를 통하여 글씨 크기 조정 <br>
  -> box-sizing: border-box; 통하여 박스 생성 후, border-radius 를 통한 일부 원형<br

- html 코드 정리 <br>
  -> 이미지 부분이 너무 지저분 하여 devi -> section -> span -> img로 묶어줌 <br>
  -> border-radius:50% 로 설정하여 이미지를 원형으로 변경 <br>

- 이미지 2단 정렬<br>
  -> div에 image-float 라는 class값 지정 <br>
  -> image-float에 float:rigth를 설정하여 오른쪽 정렬로 설정<br>

- online-offline 원형 이미지 설정 <br>
  -> 이미지 삽입 하단에 span class="circle" 를 입력하여 원형 이미지 설정 <br>
  -> background-color를 통하여 기본의 배경 이미지를 설정 <br>

## 작업 중 어려운점

- 처음 이미지 삽입하고 크기 및 간격 설정은 간단하게 하였으나, <br>
  상태정보를 위한 사진 안에 on-line, off-line 을 위한 원형 삽입이 막힘 <br>
