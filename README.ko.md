<div align="center">

# XXD Panel 355｜눌러 새긴 큰 글자

**주인공을 땅 위의 작은 알갱이로 줄이고, 짧은 한 단어를 눌러 판 큰 글자로 가로지르게 합니다.**

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <strong>한국어</strong> · <a href="README.ar.md">العربية</a>

</div>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 355 · 01 · 낙타"><br><sub>01 · 낙타</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 355 · 02 · 해변 카약"><br><sub>02 · 해변 카약</sub></td>
  </tr>
</table>

<p align="center"><sub>위는 원본 사진, 아래는 이 스타일로 다시 그린 모습입니다.</sub></p>

## 무엇인가요

Claude Code, Codex 같은 AI 에이전트용 Skill입니다. 사진 한 장을 주면 Panel 355의 원본 프롬프트대로 완성된 PNG를 그립니다.

- **어떤 그림이 되나요:** 위에는 원사진을 두고, 주체의 정체, 구조, 자세, 실제 질감과 자연광은 그대로 두고 색만 아주 가볍게 맞추며, 머리 위에 하늘을 남기고, 간판과 인쇄된 글자는 그 사진 안에만 둡니다. 아래는 바로 위에서 본, 사진에서 가장 넓은 재질의 평평하고 깨끗한 땅으로, 지평선도 다른 경물도 없으며, 짧은 한 단어가 가운데보다 조금 아래를 가로지르고 양쪽은 비워 가장자리에 닿지 않습니다. 획은 그 재질을 눌러 판 홈이고 가장자리는 부드럽게 솟으며, 낮은 빗빛이 한쪽을 비추고 다른 쪽은 얕은 그림자에 들어가며, 마지막 획은 긴 자국이 되어 물방울 모양의 큰 고리를 한 바퀴 돕니다. 주체는 바로 위에서도 자세가 읽히는 몇 개의 큰 형태로 줄여 그 자국 위에 온전히 서고, 몸의 색 두세 점과 자신보다 긴 그림자만 보이며, 머리 위에 조금 비우고 위아래는 넓은 빈 땅이며, 장면 사진은 가장 대표적인 하나만 남기고, 땅은 그 한 색, 홈은 한 단계 어둡고 그림자가 가장 어두우며, 글자는 둥근 기하 산세리프 한 단어, 라틴 문자는 소문자, 끝에 큰 점 하나, 색은 땅보다 한 단계 어둡고, 중국어는 간체이며, 보이는 디테일에서 끌어낸 은유로 이 순간에 이름을 붙이고 사물의 이름은 부르지 않습니다.
- **키워드:** 바로 위에서 본 시점 · 지평선 없는 한 가지 지면 · 눌러 판 홈 글자 · 물방울형 긴 자국 · 아주 작은 주체와 긴 그림자 · 둥근 산세리프 한 단어
- **만들 수 있는 것:** 위아래 비교(위 사진, 아래 디자인), 좌우 비교, 디자인만, 또는 휴대폰·태블릿·PC·워치 배경화면 세트. 여러 개를 함께 고를 수 있고 비율과 픽셀도 자유입니다.
- **이런 것은 아닙니다:** 필터도 템플릿도 아닙니다. 매번 사진에서 새로 그리며, 사진 한 장이 하나의 독립된 작업입니다.

## 세 단계로 시작하기

**1. 설치.** Claude Code, Codex 등 Skills를 지원하는 에이전트에서 쓸 수 있습니다:

```bash
npx skills add https://github.com/nevertoday/xxd-panel-355 --skill xxd-panel-355
```

설치 후 에이전트 세션을 다시 시작하세요. 이 저장소를 `git clone`한 뒤 `~/.claude/skills/xxd-panel-355` 또는 `~/.codex/skills/xxd-panel-355`에 링크해도 됩니다.

**2. 에이전트가 이미지를 생성할 수 있는지 확인.** 이 Skill에는 자체 이미지 모델이 없고, 에이전트의 이미지 생성(GPT Image 2 권장)을 사용합니다.

- Codex는 내장 이미지 생성이 켜져 있으면 바로 쓸 수 있습니다.
- Claude Code처럼 내장 이미지 생성이 없는 에이전트는 OpenAI 호환 이미지 API가 필요합니다. 5분 정도면 됩니다: [이미지 생성 설정](#이미지-생성-설정).

잘 모르겠다면 그냥 써 보세요. 생성할 수 없으면 작업을 시작하기 전에 Skill이 멈추고 알려 줍니다.

**3. 사진을 보내고 한 문장으로 말하기:**

> xxd-panel-355으로 이 사진을 3:4 위아래 비교 포스터로 만들고 한국어 제목을 붙여 줘.

요청이 충분하면 바로 생성하고, 빠진 것(레이아웃, 비율, 글자)은 보통 한두 가지만 묻습니다. 결과 PNG는 `~/Desktop/xxd/xxd-panel-355/` 아래 새 폴더에 저장됩니다.

## 잘 맞는 사진

**잘 맞아요**

- 지면 재질이 넓게 보이는 사진: 모래밭의 사람, 눈 속의 개, 마른 풀밭 가장자리의 자전거
- 윤곽과 자세가 분명한 단일 대상: 한 사람, 새 한 마리, 건물 한 채, 자동차 한 대
- 구도가 약하거나 배경이 어수선하거나 주체가 작은 사진(위에서 보게 바꾸고 주변을 덜어 냅니다)

**잘 맞지 않아요**

- 거리 전체, 무리, 풍경 전체를 남기고 싶은 사진(하나만 놓습니다)
- 눈높이나 비스듬한 풍경, 표면에 인쇄한 글자, 주체를 크게 그리려는 요청
- 색을 많이 쓰거나, 제목이 그림 속 사물 이름을 그대로 불러야 하는 요청

## 샘플

아래 이미지는 모두 이 Skill이 사진 한 장으로 만든 완성작입니다. 위아래 비교와 좌우 비교는 서로 다른 사진을 썼습니다.

### 위아래 비교: 위 사진, 아래 디자인

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 355 · 01 · 낙타"><br><sub>01 · 낙타</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 355 · 02 · 해변 카약"><br><sub>02 · 해변 카약</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-03.png" alt="XXD Panel 355 · 03 · 해변 요가"><br><sub>03 · 해변 요가</sub></td>
    <td width="50%"><img src="./assets/examples/sample-04.png" alt="XXD Panel 355 · 04 · 눈밭의 갈색 말"><br><sub>04 · 눈밭의 갈색 말</sub></td>
  </tr>
</table>

<details>
<summary>16장 더 보기</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-05.png" alt="XXD Panel 355 · 05 · 눈밭의 여우"><br><sub>05 · 눈밭의 여우</sub></td>
    <td width="50%"><img src="./assets/examples/sample-06.png" alt="XXD Panel 355 · 06 · 붉은 옷의 행인"><br><sub>06 · 붉은 옷의 행인</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-07.png" alt="XXD Panel 355 · 07 · 서커스 천막"><br><sub>07 · 서커스 천막</sub></td>
    <td width="50%"><img src="./assets/examples/sample-08.png" alt="XXD Panel 355 · 08 · 풀밭의 빨간 자전거"><br><sub>08 · 풀밭의 빨간 자전거</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-09.png" alt="XXD Panel 355 · 09 · 풀밭의 흰 거위"><br><sub>09 · 풀밭의 흰 거위</sub></td>
    <td width="50%"><img src="./assets/examples/sample-10.png" alt="XXD Panel 355 · 10 · 풀밭에 누운 사람"><br><sub>10 · 풀밭에 누운 사람</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-11.png" alt="XXD Panel 355 · 11 · 염호의 행인"><br><sub>11 · 염호의 행인</sub></td>
    <td width="50%"><img src="./assets/examples/sample-12.png" alt="XXD Panel 355 · 12 · 가족 소풍"><br><sub>12 · 가족 소풍</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-13.png" alt="XXD Panel 355 · 13 · 들판의 건초 더미"><br><sub>13 · 들판의 건초 더미</sub></td>
    <td width="50%"><img src="./assets/examples/sample-14.png" alt="XXD Panel 355 · 14 · 얼음 위의 물개"><br><sub>14 · 얼음 위의 물개</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-15.png" alt="XXD Panel 355 · 15 · 들판의 호박"><br><sub>15 · 들판의 호박</sub></td>
    <td width="50%"><img src="./assets/examples/sample-16.png" alt="XXD Panel 355 · 16 · 초원의 코끼리"><br><sub>16 · 초원의 코끼리</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-17.png" alt="XXD Panel 355 · 17 · 풀밭의 양"><br><sub>17 · 풀밭의 양</sub></td>
    <td width="50%"><img src="./assets/examples/sample-18.png" alt="XXD Panel 355 · 18 · 들판의 흰 의자"><br><sub>18 · 들판의 흰 의자</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-19.png" alt="XXD Panel 355 · 19 · 정원의 손수레"><br><sub>19 · 정원의 손수레</sub></td>
    <td width="50%"><img src="./assets/examples/sample-20.png" alt="XXD Panel 355 · 20 · 호수 위의 돛단배"><br><sub>20 · 호수 위의 돛단배</sub></td>
  </tr>
</table>

</details>

### 좌우 비교: 왼쪽 사진, 오른쪽 디자인

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-21.png" alt="XXD Panel 355 · 21 · 서퍼"><br><sub>21 · 서퍼</sub></td>
    <td width="50%"><img src="./assets/examples/sample-22.png" alt="XXD Panel 355 · 22 · 노란 옷으로 선 사람"><br><sub>22 · 노란 옷으로 선 사람</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-23.png" alt="XXD Panel 355 · 23 · 마당을 쓰는 사람"><br><sub>23 · 마당을 쓰는 사람</sub></td>
    <td width="50%"><img src="./assets/examples/sample-24.png" alt="XXD Panel 355 · 24 · 풍선을 든 사람"><br><sub>24 · 풍선을 든 사람</sub></td>
  </tr>
</table>

<details>
<summary>16장 더 보기</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-25.png" alt="XXD Panel 355 · 25 · 해변의 개 한 마리"><br><sub>25 · 해변의 개 한 마리</sub></td>
    <td width="50%"><img src="./assets/examples/sample-26.png" alt="XXD Panel 355 · 26 · 모래밭의 홍학"><br><sub>26 · 모래밭의 홍학</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-27.png" alt="XXD Panel 355 · 27 · 전신 기린"><br><sub>27 · 전신 기린</sub></td>
    <td width="50%"><img src="./assets/examples/sample-28.png" alt="XXD Panel 355 · 28 · 눈밭의 펭귄"><br><sub>28 · 눈밭의 펭귄</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-29.png" alt="XXD Panel 355 · 29 · 마당의 수탉"><br><sub>29 · 마당의 수탉</sub></td>
    <td width="50%"><img src="./assets/examples/sample-30.png" alt="XXD Panel 355 · 30 · 앉은 주황 고양이"><br><sub>30 · 앉은 주황 고양이</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-31.png" alt="XXD Panel 355 · 31 · 해바라기 밭"><br><sub>31 · 해바라기 밭</sub></td>
    <td width="50%"><img src="./assets/examples/sample-32.png" alt="XXD Panel 355 · 32 · 선인장 한 그루"><br><sub>32 · 선인장 한 그루</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-33.png" alt="XXD Panel 355 · 33 · 대숲의 대나무 그루터기"><br><sub>33 · 대숲의 대나무 그루터기</sub></td>
    <td width="50%"><img src="./assets/examples/sample-34.png" alt="XXD Panel 355 · 34 · 배 한 개"><br><sub>34 · 배 한 개</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-35.png" alt="XXD Panel 355 · 35 · 구리 찻주전자"><br><sub>35 · 구리 찻주전자</sub></td>
    <td width="50%"><img src="./assets/examples/sample-36.png" alt="XXD Panel 355 · 36 · 기둥 위 새집"><br><sub>36 · 기둥 위 새집</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-37.png" alt="XXD Panel 355 · 37 · 정원의 물뿌리개"><br><sub>37 · 정원의 물뿌리개</sub></td>
    <td width="50%"><img src="./assets/examples/sample-38.png" alt="XXD Panel 355 · 38 · 정원에 물 주는 사람"><br><sub>38 · 정원에 물 주는 사람</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-39.png" alt="XXD Panel 355 · 39 · 모래언덕을 걷는 사람"><br><sub>39 · 모래언덕을 걷는 사람</sub></td>
    <td width="50%"><img src="./assets/examples/sample-40.png" alt="XXD Panel 355 · 40 · 카라 한 송이"><br><sub>40 · 카라 한 송이</sub></td>
  </tr>
</table>

</details>

## 이렇게 말하면 됩니다

파라미터를 외울 필요 없이 그대로 말하세요:

| 원하는 것 | 이렇게 말하기 |
|---|---|
| 위아래 비교 | 3:4 위아래 비교로 만들어 줘 |
| 좌우 비교 | 16:9 좌우 비교, 왼쪽에 사진 |
| 디자인만 | 사진 없이 디자인만, 9:16 세로 |
| 배경화면 세트 | 휴대폰, 태블릿, PC, 워치 배경화면을 통일된 세트로 |
| 여러 비율 | 같은 사진으로 1:1, 3:4, 16:9 한 장씩 |
| 내 글자 그대로 | 제목은 「바람이 지나가는 곳」, 한 글자도 바꾸지 마 |
| 글자 없음 | 글자는 하나도 넣지 마 |
| 글자 언어 | 글자는 일본어로 |
| 폴더 전체 | 이 폴더의 사진을 전부 위아래 비교로 |
| 지난번과 같이 | 지난번 설정 그대로 |

명령줄이 편하다면 파라미터가 위와 일대일로 대응합니다:

```text
/xxd-panel-355 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale ko-KR
/xxd-panel-355 photo.jpg --mode design-only --size 9:16 --text none
/xxd-panel-355 ./photos --mode left-right --size 16:9 --text prompt --locale en-US
```

전체 파라미터는 [파라미터 목록](#파라미터-목록)에 있습니다.

## 자주 묻는 질문

**원본 사진이 꼭 들어가나요?** 아니요. "디자인만"이나 배경화면을 고르면 화면 전체가 디자인입니다.

**글자는 누가 쓰나요?** 기본적으로 이미지 모델이 사진을 보고 쓰고, 여러분은 언어만 고릅니다. 직접 쓴 글자를 주면 한 글자도 바꾸지 않고, 글자 없이도 만들 수 있습니다. 사실처럼 보이는 정보(지명, 날짜, 숫자)는 여러분이 준 것이나 사진에 보이는 것만 쓰고 지어내지 않습니다.

**마음에 들지 않으면요?** "한 장 더"라고 하세요. 이전 결과를 고치는 대신 원본 사진에서 다시 그리므로 매번 결과가 다릅니다.

**여러 장을 한꺼번에 하면 섞이지 않나요?** 섞이지 않습니다. 사진마다 따로 생성하고 다른 사진의 색, 글자, 구도를 빌리지 않습니다. 설정은 한 번만 묻습니다.

**제 사진은 어디로 가나요?** 에이전트가 쓰는 이미지 모델로만 갑니다. Skill은 다른 곳에 올리지 않고 접속 주소나 키도 표시하지 않습니다.

**다른 Panel과는 어떤 관계인가요?** XXD Panel은 번호마다 스타일이 하나씩인 독립된 모음입니다. 마음에 드는 것만 설치해도 됩니다. 사진에 맞는 스타일을 AI가 추천하게 하거나 여러 개를 비교하려면 카탈로그 [xxd-panel-all](https://github.com/nevertoday/xxd-panel-all)을 쓰세요.

## 원본 프롬프트

이 스타일은 샤오샤오둥이 쓴 [원본 프롬프트](references/original-prompt/zh-CN.md)(중국어)만으로 정해집니다. Skill은 여러분이 고른 레이아웃, 크기, 글자 설정을 뒤에 덧붙일 뿐, 요약하거나 번역하거나 고쳐 쓰지 않습니다.

참고 번역(읽기용이며 이미지 생성에는 쓰지 않음): [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

## 이미지 생성 설정

`gpt-image-2`(또는 호환 모델)를 제공하는 OpenAI 호환 API와 그 API 키가 필요합니다. 아래 방법은 별도 설정을 만들어 Codex 자체 설정에는 영향을 주지 않습니다:

```bash
mkdir -p ~/.xxd-imagegen
cat > ~/.xxd-imagegen/config.toml <<'EOF'
model_provider = "image"

[model_providers.image]
base_url = "https://api.openai.com/v1"   # 또는 호환 엔드포인트
env_key = "XXD_IMAGE_API_KEY"
EOF

# ~/.zshrc 또는 ~/.bashrc에 넣어 에이전트도 읽을 수 있게
echo 'export XXD_IMAGEGEN_CODEX_DIR=~/.xxd-imagegen' >> ~/.zshrc
echo 'export XXD_IMAGE_API_KEY=내-키' >> ~/.zshrc
```

터미널과 에이전트를 다시 연 뒤, 이 Skill 폴더에서 한 번 확인하세요:

```bash
python3 scripts/configured_imagegen.py probe
```

`"ok":true`가 나오면 성공입니다. 사용 가능 여부만 보여 주고 주소나 키는 출력하지 않습니다. Codex가 이미 호환 API로 이미지를 만들고 있다면 이 단계는 필요 없습니다.

## 파라미터 목록

| 파라미터 | 값 |
|---|---|
| `--mode` | `top-bottom` 위아래 비교 · `left-right` 좌우 비교 · `design-only` 디자인만 · `wallpaper-pack` 4종 배경화면; 여러 개 선택 가능 |
| `--size` | `auto` 추천 · `source` 사진 비율 · `1:1` `3:4` `4:3` `4:5` `5:4` `2:3` `3:2` `9:16` `16:9` `21:9` `5:7` `7:5` · 정확한 픽셀(예 `2160x3840`); 여러 개 선택 가능 |
| `--text` | `prompt` 사진을 보고 작성 · `exact` 내 글자 그대로(`--copy "…"`와 함께) · `none` 글자 없음 |
| `--locale` | 글자 언어. 예: `zh-CN` `en-US` `ja-JP` `ko-KR` `ar` |
| `--wallpaper` | `linked` 통일된 세트 · `independent` 네 장 각각 독립 |
| `--wallpaper-size` | 기기별 픽셀. 예: `phone=1440x3200,desktop=3840x2160` |
| `--out` | 출력 루트 변경(기본 `~/Desktop/xxd/xxd-panel-355/`) |
| `--prefs` | `last` 지난번 그대로 · `edit` 지난번에서 수정 · `new` 새로 고르기 · `off` 이번엔 기억 안 함 · `clear` 기록 삭제 |

- 값이 모두 있으면 묻지 않고, 빠진 것만 묻습니다. `photo.jpg` 대신 폴더를 주면 일괄 처리합니다.
- 조합은 한 장씩 생성합니다. 모드 2개 × 크기 3개 = 6장이며, 잘라 낸 것이 아니라 캔버스마다 구도를 새로 잡습니다.
- 비교 이미지는 정확히 50:50입니다. 보통 모델은 디자인 쪽만 그리고 스크립트가 원본 사진을 그대로 옆에 붙이므로, 경계는 가운데이고 사진은 바뀌지 않습니다.
- 파일 이름은 `source-001-street-top-bottom-3x4-1152x1536.png` 형식이며 모두 작업 폴더 하나에 평평하게 저장됩니다.
- 레이아웃, 크기, 글자 방식과 언어만 기억하고 사진, 문구, 키는 저장하지 않습니다.

<!-- xxd-readme-ads:start -->
## XXD 소개

XXD는 Xiaoxiaodong 브랜드 이름의 약자입니다. 이 프로젝트는 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01)이 만들고 관리합니다.

## Xiaoxiaodong 멀티플랫폼 멤버십 · CNY 699/년

> **광고 안내:** 아래 QR 코드와 멤버십·유료 서비스 링크는 XXD의 홍보 정보입니다. 스캔이나 구매는 선택 사항이며 이 프로젝트 이용에는 영향을 주지 않습니다.

연간 멤버십 하나로 **Knowledge Planet + XXD 회원 프롬프트 라이브러리 + 모든 General Skills 멤버십**을 함께 이용할 수 있습니다. 각각 따로 구매할 필요가 없습니다.

<!-- xxd-panel-command-system:start -->

### Skills가 함께 작동하는 방식

| 등급 | 포함 내용 | 역할 |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | 사용 가능한 번호형 Skills를 찾고, 이미지·주제·용도에 맞춰 추천하며, 여러 스타일과 일괄 작업을 정리합니다. |
| **Soldier** | `xxd-panel-NNN` | 각 번호가 고유한 원본 프롬프트와 미학에 따라 General이 배정한 구체적인 작업을 완성합니다. |

<!-- xxd-panel-command-system:end -->

### 회원 혜택

1. **WeChat 일대일 AI 학습·프로젝트 상담**
   아래 QR 코드로 Xiaoxiaodong의 WeChat을 추가해 AI 학습, 도구, 실제 프로젝트를 일대일로 상담하고 실용적인 답변과 안내를 받을 수 있습니다. 대표적인 질문은 회원 자료로 정리됩니다.
2. **계속 업데이트되는 회원 프롬프트 라이브러리**
   [XXD 회원 프롬프트 라이브러리](https://vip.xiaoxiaodong.ai/)에는 현재 약 3만 2천 개의 프롬프트가 있으며, 10만 개 이상을 목표로 계속 확장합니다.
3. **모든 General Skills와 사용 지원**
   하나의 멤버십으로 모든 General Skills를 이용하고, 사용 중 도움이 필요할 때 안내와 Q&A를 받을 수 있습니다.
4. **필요성이 높은 요청을 우선 검토**
   회원이 제안한 수요가 높고 꼭 필요한 프롬프트와 Skills는 우선 검토하고 개발합니다.

### 가입 방법

- [회원 웹사이트에서 직접 가입](https://vip.xiaoxiaodong.ai/)할 수 있습니다.
- 또는 아래 QR 코드로 Xiaoxiaodong의 WeChat을 추가해 일대일 가입 지원을 받을 수 있습니다.

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="Xiaoxiaodong 연락처" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## 라이선스

**비상업적 이용은 무료이며, 상업적 이용은 별도 허가가 필요합니다.** 이 프로젝트(Skill, 원본 프롬프트, 스크립트, 문서)는 [PolyForm Noncommercial 1.0.0](LICENSE)을 따릅니다. 소스는 공개되어 있지만 OSI가 정의한 오픈 소스는 아닙니다.

- **무료:** 개인 학습과 취미 창작, 내 사진으로 만든 이미지를 보관하거나 개인 계정에 공유하는 것(광고, 협찬, 상품 홍보 제외), LICENSE를 함께 제공하는 비상업적 수정과 재배포.
- **개인의 상업적 이용은 허가 필요:** 의뢰받은 유료 작업, 광고·상품 홍보 콘텐츠, 소량 굿즈 판매, 유료 강의나 커뮤니티. 대체로 협의할 수 있으며 작성자의 서면 확인을 기준으로 합니다.
- **기관 이용은 계약 필수:** 회사, 스튜디오, MCN, 브랜드 등의 모든 상업적 이용(내부 이용 포함)과 앱, 웹사이트, SaaS, API로의 통합.
- **허가하지 않음:** Skill, 프롬프트, 샘플의 재판매, 이름 변경, 재포장 배포.
- Xiaoxiaodong 멤버십에는 상업 라이선스가 포함되지 않습니다. 샘플의 원본 사진은 각 촬영자에게 권리가 있으며 효과를 보여 주기 위해서만 싣습니다.

신청하려면 Xiaoxiaodong의 WeChat을 추가하고 "상업 라이선스"라고 적어 주세요. 전체 조건과 QR 코드는 [상업 라이선스 안내](COMMERCIAL.md)(중국어·영어)에 있습니다.
