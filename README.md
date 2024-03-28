# Diversity Train Set 다양성 열차세트 /DTS
![DTS_board](https://github.com/DTS-NewGRF/DTS/blob/minengallery/docs/DTS_board.png)
**다양성 열차세트**는 <br>
약 2016년에 [YST set](https://github.com/evepoi/YST)에서 최초로 시작했다.<br>
2022년 4월 2일 YST에서 열차들이 나라별도 분리된 <br>
[한국열차세트 플러스](https://github.com/GBLINER/KoreanTrainSet_Plus), [일본열차세트 플러스](https://github.com/GBLINER/JapaneseTrainSet_Plus), [중국열차세트](https://github.com/GBLINER/ChineseTrainSet), 
[유럽열차세트](https://github.com/GBLINER/EuropeanTrainSet), [세계열차세트](https://github.com/GBLINER/WorldTrainSet), [가상열차세트](https://github.com/GBLINER/VirtualTrainSet)로 파생되었다.<br>
가상열차세트를 제외한 다른 셋은 여전히 파생셋으로 관리되고 있다.<br>
`[YST]는 중단되었다.`<br>

2023년 5월 `Derivative Train Set 파생형 열차세트 / DTS`로 다시 통합하여 진행을 시작했다.<br>
2024년 1월 `Diversity Train Set 다양성 열차세트 / DTS`로 이름을 변경하여 다양한 열차들을 수용하는데 적극적으로 추가진행하고 있다.<br>
[Github release 페이지](https://github.com/DTS-NewGRF/DTS/releases)와 인게임 온라인 컨텐츠에서 다운받을 수 있습니다.<br>

## 최근 등록 릴리즈
```
[1.43] 2024.03.22
[공지사항]
- [제거] 삭제예정오브젝트

[변경]
- [A-Train] 구도색추가 및 등장년도에 따라 등장변경
- [7600호대] 7600호대 도색통합 및 등장년도에 따라 등장변경
- [TGV-Pos] 그래픽 수정 및 블루 & 그레이 → 아틀란틱 블루 이름변경
- [TGV-레조] 그래픽 수정 및 블루 & 그레이 → 아틀란틱 블루 이름변경
- [TGV-아틀랑티크] 그래픽 수정 및 뒤집힘 방지 적용, 블루 & 그레이 → 아틀란틱 블루 이름변경
- [TGV-듀플렉스] 그래픽 수정 및 뒤집힘 방지 적용, 블루 & 그레이 → 아틀란틱 블루 이름변경
- [TGV-레조 듀플렉스] 그래픽 수정 및 뒤집힘 방지 적용, 블루 & 그레이 → 아틀란틱 블루 이름변경, 리리아 → 카밀론 이름변경
- [7X00호대] 등장년도에 따라 도색 변경
- [관광열차] 남도해양관광열차, 서해금빛열차 도색 변경
- [서울교통공사] 4세대 7000호대 구매이미지 변경
```

## 인게임 등록
```
[1.39] 2024.02.01
[공지사항]
- DTS 오브젝트셋 깃허브 릴리즈 공개로 인해 DTS 내 오브젝트 2024년 3월 삭제예정 문구 강제 출력.
- [한국지하철] 열차 정비로 인한 삭제여부 2024년 3월 삭제 예정 강제 공지 및 삭제 그래픽 적용.

[추가]
- [관광열차 그룹] 관광열차 그룹화 전용 디자인
- [서울교통공사] 그룹화 전용 디자인
- [서울교통공사] 초기, 개조저항 신규
- [한국철도공사] 그룹화 전용 디자인 
- [신분당선] 1,2,3세대
- [RDC] 경북나드리 도색 
- [부산교통공사] 1000호대 1,2,3세대
- [부산교통공사] 2000, 3000호대
- [대구교통공사] 그룹화 전용디자인
- [대구교통공사] 1000, 2000호대

[변경]
- [한국 지하철] 열차 정렬 재정비 / 세부사항 인게임에서 확인.
- [서울교통공사] 1,4세대 9000호대 객차 편성 수정.

[사운드]
- [7000호대 디젤기관차] 정지 사운드 추가
- 일부 출발사운드 파일이름 변경 / 게임상 변화 없음
```

## Next 인게임 버전 : 1.50

## 등록기준
### 공통사항
기본 템플릿과 일치하지 않을 경우 적용이 보류된다. 하지만, 그외 자료는 제한을 두지 않고, 적용하고 있다.

### 깃허브 릴리즈 및 온라인컨텐츠 등록
기본 자료는 본 깃허브 릴리즈를 통해 메인 업로드를 기준으로 한다. <br>
릴리즈 등록시 프리 릴리즈가 아닌 최종 릴리즈로 등록된다. <br>
온라인 컨텐츠는 매달 등록되는것으로 정의한다. <br>
매달 기준 최종 깃허브 릴리즈가 온라인컨텐츠로 등록되는 것과 같다. <br>

## 개발
### 빌드하는 방법
이 NewGRF를 빌드하려면 [NML](https://github.com/OpenTTD/nml)과 **Python 3**이 필요합니다. <br> 
터미널 쉘에서 ``make``를 실행하세요. Windows 환경이라면, 그 전에 명령 프롬포트를 열고 ``bash``를 입력하세요.  <br>
``make clean``을 입력하면 모든 생성된 파일이 초기화됩니다.