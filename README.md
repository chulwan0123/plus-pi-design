# PLUS Market Cap Mobile

PLUS Pi 모바일 ETF 교육 페이지의 독립 산출물입니다.

이 폴더는 `plus-design-system` 문서와 분리되어 있습니다. 디자인시스템 HTML 안에 포함되는 문서가 아니라, 375px 모바일 기준으로 만든 별도 HTML 페이지입니다.

## 파일

```text
/Users/hanwha/Documents/GitHub/plus-market-cap-mobile/PLUS-Market-Cap-Mobile.html
```

## 로컬 미리보기

이 폴더에서 서버를 실행합니다.

```sh
cd /Users/hanwha/Documents/GitHub/plus-market-cap-mobile
python3 -m http.server 8788
```

브라우저에서 엽니다.

```text
http://127.0.0.1:8788/PLUS-Market-Cap-Mobile.html
```

파일로 직접 열어도 됩니다.

```text
file:///Users/hanwha/Documents/GitHub/plus-market-cap-mobile/PLUS-Market-Cap-Mobile.html
```

## 디자인 기준

- 기준 화면: 375px 모바일
- 기본 좌우 패딩: 20px
- 기본 콘텐츠 폭: 335px
- 문서형 단일 페이지 구조
- 디자인시스템 문서와 독립적으로 동작
- 외부 빌드 없이 HTML 파일 하나로 실행
- CSS, SVG, 차트 데이터, 스크립트는 HTML 내부에 포함

## 주요 스타일 값

```text
Orange/60: #F37521
Orange/10: #FFF2E5
Orange/20: #FFE4CC
Blue/10: #E9F3FD
Blue/20: #DEEDFC
Gray/10: #F2F2F3
Gray/20: #DDDDDF
Gray/40: #A2A2A5
Gray/60: #707075
Gray/90: #141415
```

## 현재 섹션 순서

1. `우리아이 첫 투자 미국 ETF 입문 가이드`
2. `20년간 주요국가별 지수의 상대 주가 흐름`
3. `10년, 20년 주요 국가 주요 지수의 가격 변화율`
4. `전 세계 기업들의 시가총액 순위`
5. `VOO`
6. `QQQM`
7. `SCHD`
8. `ETF vs 주식 vs 펀드, 어떤 차이가 있을까요?`
9. 레버리지 ETF 변동성 잠식 그래프
10. `실제로 벌어진 레버리지 ETF 괴리`
11. `포트폴리오 전략 예시`
12. `종합계좌와 연금저축계좌 비교`
13. `유기정기금(적립식) 증여 활용`
14. 장기 투자 수익 SVG 그래프
15. `증여 공제한도`
16. `테마별 ETF 종류`
17. 2행 기업 로고 marquee 애니메이션

## 수정 원칙

- 사용자가 준 문구는 임의로 바꾸지 않습니다.
- 그래프 수치 변경은 반드시 근거 확인 후 진행합니다.
- Figma 화면을 그대로 복사하지 않고 PLUS Pi 모바일 스타일로 재해석합니다.
- 화면에 `Standalone Mobile`, `Design System 문서와 분리` 같은 작업 설명 문구를 노출하지 않습니다.
- 불필요한 페이지 전체 좌우 스크롤을 만들지 않습니다.
- 의도된 표 영역만 가로 스크롤을 허용합니다.

## 확인 체크리스트

- 375px 기준으로 전체 페이지가 깨지지 않는지 확인합니다.
- 표/그래프 텍스트가 겹치거나 잘리지 않는지 확인합니다.
- `전 세계 기업들의 시가총액 순위` 표는 의도한 가로 스크롤만 동작해야 합니다.
- `증여 공제한도` fill block, 세로 가이드, 나이 라벨이 겹치지 않아야 합니다.
- 장기 투자 수익 SVG의 그라데이션과 그래프 끝점이 콘텐츠 폭에 맞아야 합니다.
- 로고 marquee는 2행으로 움직이고, 아이콘은 80x80, 간격은 12px입니다.

## 디자인시스템과의 관계

디자인시스템 문서는 별도 저장소/폴더에서 관리합니다.

```text
/Users/hanwha/Documents/GitHub/plus-design-system
```

디자인시스템 HTML:

```text
/Users/hanwha/Documents/GitHub/plus-design-system/dist/PLUS-Design-System.html
```

이 모바일 페이지는 디자인시스템 문서의 `dist` 산출물이 아니라 별도 독립 페이지로 관리합니다.
