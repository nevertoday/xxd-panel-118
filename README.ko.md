<div align="center">

# XXD Panel 118｜흑연 여백 스케치 기록

사진에서 기억할 관계를 남기고 연필과 여백으로 다시 구성합니다.

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <strong>한국어</strong> · <a href="README.ar.md">العربية</a>

</div>

## 샘플 작품

本项目已发布 8 张实际样片，图片文件位于 `assets/examples/`。

| sample-05 | sample-06 |
| --- | --- |
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| sample-07 | sample-08 |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |
| sample-09 | sample-10 |
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
| sample-11 | sample-12 |
| ![sample-11](assets/examples/sample-11.png) | ![sample-12](assets/examples/sample-12.png) |

## 잘 맞는 상황과 해결하는 문제

주체가 작거나 배경이 복잡하거나 평범한 사진에 독립 출판물의 표현이 필요할 때, **Panel 118**은 실제 사진을 보존하고 디자인 영역을 흑연 연필 주제 조합으로 다시 연출합니다. 무엇을 남길지 판단한 뒤 크기, 위치, 여백을 재구성합니다.

### 이런 경우에 적합합니다

- 사진의 정체성과 질감을 보존하며 독립적 미술 판단이 담긴 편집 포스터가 필요할 때.
- 모든 사물이나 원래 구도를 따라 그리지 않고 주제 관계를 알아보게 하고 싶을 때.
- 복잡한 아카데믹 사실주의보다 흑백 흑연, 자연스러운 해칭, 넓은 여백을 좋아할 때.
- 상하, 좌우, 디자인 전용, 배경화면, 폴더 일괄 출력이 필요할 때.

### 해결하는 것

- 작은 주체, 복잡한 배경, 평범한 구도를 적극적으로 개선합니다.
- 삭제, 재조합, 크롭, 크기 변화로 주제 조합을 만듭니다.
- 양과 음의 형태, 밀도, 비대칭 균형을 통해 여백이 구도에 참여하게 합니다.
- 각 원본에서 독립적으로 한 번에 생성하고 비교 모드는 두 개의 50:50 영역으로 유지합니다.

## 원본 프롬프트 · 5개 언어

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

중국어 원문은 글자 그대로 보존하며 런타임의 유일한 창작·미학 권위입니다. 다른 네 언어는 완전한 열람용 번역이며 생성 지시를 되쓰지 않습니다.

**핵심 특징:** 흑연 연필 · 자연스러운 해칭 · 소량 교차 해칭 · 옅은 회색조 · 주제 조합 · 적극적 덜어내기 · 넓은 여백 · 선택적 원본 식별색 1–2색

## 빠른 적합성 확인

| 궁금한 점 | Panel 118의 답 |
|---|---|
| 원본 구도가 평범하다면? | 원본 배치에 의존하지 않고 디자인을 다시 연출합니다. |
| 대응 관계가 남는가? | 가장 의미 있는 주제, 구조 흐름, 관계를 남깁니다. |
| 전통적 사실 소묘인가? | 느슨하고 소박한 형태의 일러스트 속사화입니다. |
| 여러 크기를 지원하는가? | 네 모드, 일반·사용자 비율, 정확한 픽셀, 폴더 일괄 처리. |

## 사진을 결과물로 바꾸는 흐름

주제와 구조 관계 이해 → 적극적 삭제 → 재배치와 크롭 → 흑연 윤곽·자연 해칭·옅은 회색 → 여백과 소량의 글로 편집 구도 완성.

## 완성작의 식별 특징

- 흑백 또는 자연 흑연 회색조가 중심이며 원본 1–2색을 극소량 강조에 선택적으로 사용합니다.
- 느슨하고 소박한 윤곽, 자연스러운 해칭과 소량의 교차 해칭.
- 주체는 중심 이탈, 가장자리 배치, 부유, 확대, 축소, 부분 크롭이 가능합니다.
- 여백은 주체만큼 중요하며 채우기보다 정보를 덜어냅니다.
- 소량의 단어나 짧은 문구는 주제·장소·감정·은유에서 나오며 언어·글꼴·형식은 고정하지 않습니다.
- 사진 복제, 복잡한 배경, 과밀한 세부, 기계적 배치, 템플릿 느낌을 피합니다.

## 네 가지 출력 모드

- `top-bottom`: 전폭 상하 두 영역만 사용합니다. 실제 사진은 위, 디자인은 아래에 정확히 50%씩 둡니다.
- `left-right`: 전고 좌우 두 영역만 사용합니다. 실제 사진은 왼쪽, 디자인은 오른쪽에 정확히 50%씩 두며 상하 구도로 돌리지 않습니다.
- `design-only`: 전체 캔버스에 Panel 118의 디자인 번역만 표시하고 사진은 보이지 않는 참고 자료로 사용합니다.
- `wallpaper-pack`: 휴대폰, iPad, 데스크톱, 시계용 완성 이미지를 각각 만들며 `linked` 또는 `independent`를 선택합니다.

모드와 크기는 여러 개 선택할 수 있습니다. `1:1`, `3:4`, `4:3`, `4:5`, `5:4`, `2:3`, `3:2`, `9:16`, `16:9`, `21:9`, `5:7`, `7:5`, 정확한 픽셀을 지원합니다. 텍스트는 모델 생성, 사용자 원문, 없음 중에서 선택합니다. 폴더 입력은 각 소스를 분리 처리하고 최종 PNG를 하나의 새 작업 폴더에 평면으로 저장합니다.

## 시작하기

```bash
git clone https://github.com/nevertoday/xxd-panel-118.git
npx skills add https://github.com/nevertoday/xxd-panel-118 --skill xxd-panel-118
```

설치 후 Agent 세션을 다시 시작하고 `$xxd-panel-118`을 호출하세요. 사용자 단위 Codex 설치에는 `--global --agent codex --yes`를 추가할 수 있습니다.

```text
/xxd-panel-118 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale ko-KR
/xxd-panel-118 photo.jpg --mode left-right --size 16:9 --text prompt --locale en-US
/xxd-panel-118 photo.jpg --mode design-only --size 9:16 --text none
/xxd-panel-118 ./photos --mode design-only --size auto,3:4 --text prompt --locale ja-JP
```

전체 실행 계약은 [SKILL.md](SKILL.md), 런타임 어댑터는 [영어](references/xxd-panel-118-prompt.en.md)와 [중국어](references/xxd-panel-118-prompt.zh-CN.md)를 확인하세요.

<!-- xxd-readme-ads:start -->
## XXD 소개

XXD는 Xiaoxiaodong 브랜드 이름의 약자입니다. 제작 및 유지관리: [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## 지원과 멤버십

> **광고 안내:** 이 섹션의 QR 코드와 유료 멤버십·서비스 링크는 XXD의 홍보 정보입니다. 스캔이나 구매는 선택 사항이며, 오픈 소스 이용에는 영향을 주지 않습니다.


<!-- xxd-panel-command-system:start -->

모든 장군 Skills는 연 CNY 699 통합 멤버십에 포함되며 별도 구매가 필요하지 않습니다.

| 등급 | Skill | 역할 |
|---|---|---|
| **장군급** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | 사용 가능한 번호형 Skills 탐지, 이미지·주제·용도별 추천, 번호 지정 파견, 동일 입력의 여러 스타일 시안, 이미지 폴더의 일괄 배정과 개별 작업 파견. |
| **병사급** | `xxd-panel-NNN` | 각 번호가 고유한 원본 프롬프트와 미학만 실행해 장군이 배정한 하나의 작업을 완성합니다. |

<!-- xxd-panel-command-system:end -->

### 지식성구＋회원 프롬프트 라이브러리＋모든 장군 Skills 멤버십 · CNY 699/년

[지식성구](https://wx.zsxq.com/group/15554814142882), [XXD 회원 프롬프트 라이브러리](https://vip.xiaoxiaodong.ai/), 모든 장군 Skills 멤버십은 하나의 회원권입니다. **연회비를 한 번 결제하면 세 가지 혜택을 모두 이용할 수 있으며 추가 구매는 필요하지 않습니다.**

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## 라이선스

이 프로젝트(Skill, 프롬프트, 스크립트, 문서, 함께 제공되는 샘플 이미지 포함)는 **PolyForm Noncommercial License 1.0.0**을 따릅니다. 전체 법률 문구는 [LICENSE](LICENSE), 공식 페이지는 <https://polyformproject.org/licenses/noncommercial/1.0.0>에서 확인하세요.

쉽게 말하면 다음과 같습니다.

- 개인은 학습, 연구, 실험, 테스트, 취미 프로젝트, 사적 오락에 사용할 수 있습니다. 자선 단체, 교육 기관, 공공 연구·안전·보건 기관, 환경보호 단체, 정부 기관도 사용할 수 있습니다.
- **비상업적 목적**이라면 사용, 복사, 수정, 파생 작업 제작, 공유가 가능합니다. 공유할 때는 이 라이선스(또는 위 링크)와 저자가 제공한 모든 `Required Notice:` 문구를 함께 제공해야 합니다.
- 상업 제품이나 서비스, 유료 납품, 접근권 또는 라이선스 판매, 상업적 적용으로 이어질 것으로 예상되는 용도에는 사용할 수 없습니다. 상업적으로 사용하려면 저작권자에게 별도의 서면 허가를 받아야 합니다.
- 이 계약은 명시된 저작권 라이선스와 제한된 특허 라이선스만 부여합니다. 상표, 브랜드명 또는 명시되지 않은 다른 권리를 부여하지 않으며 라이선스를 제3자에게 재허여할 수도 없습니다.
- 서면으로 위반 통지를 받으면 32일 안에 준수 상태로 돌아가고 실질적인 시정 조치를 해야 하며, 그렇지 않으면 라이선스가 즉시 종료됩니다. 특허 침해를 서면으로 주장해도 특허 라이선스가 종료됩니다.
- 콘텐츠는 법이 허용하는 범위에서 어떠한 보증도 없이 “있는 그대로” 제공됩니다. 사용에 따른 위험과 잠재적 손실은 사용자가 부담합니다.
