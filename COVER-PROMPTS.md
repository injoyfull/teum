# 틈 — 표지 이미지 생성 프롬프트 (ChatGPT / GPT Image)

시즌 1 여섯 틈의 표지 그림. ChatGPT에 하나씩 붙여넣어 생성한 뒤,
`assets/cover-01.png` ~ `cover-06.png` 로 저장하면 사이트에 바로 반영됩니다.

---

## 공통 규칙 (모든 프롬프트에 이미 포함되어 있음)

- **비율**: 5:6.2 세로 (정사각에 가까운 세로형). 지원 안 되면 4:5로.
- **바탕**: 각 호 지정 파스텔색. 크림색 종이 느낌.
- **스타일**: 플랫 벡터 일러스트, 굵고 단순한 형태, 그라데이션·질감·그림자 없음.
- **금지**: 사진, 3D, 사실적 렌더, 텍스트/글자, 사람 얼굴, 워터마크.
- **여백**: 위쪽 15%와 아래쪽 30%는 비워둘 것 (호수·제목이 얹힘).

> 생성 후 마음에 안 들면 "make it simpler, flatter, fewer elements" 를 덧붙여 재생성하세요.
> 틈의 디자인은 **덜어낼수록** 좋아집니다.

---

## No.01 — 시각 · 초록

```
A flat vector illustration for a magazine cover, 5:6.2 vertical ratio.

Soft pale green background (#ECF3D9). Two organic leaf-like blobs in bright
lime green (#A6E22E) — one large blob in the upper right area, one small blob
in the lower left. Simple rounded organic shapes, like abstract summer foliage.
No outlines, no gradients, no texture, no shadow.

Editorial minimal style, generous negative space. Keep the top 15% and the
bottom 30% of the canvas completely empty. No text, no letters, no people.
```

---

## No.02 — 촉각 · 물

```
A flat vector illustration for a magazine cover, 5:6.2 vertical ratio.

Soft pale blue background (#E2EFF6). Concentric circular ripples in blue
(#2F9BC4) radiating from a single point in the upper-middle area — like the
ripple made by one fingertip touching still water. Four rings: the innermost
is a solid small dot, the outer rings get progressively thinner and more
transparent. Clean geometric circles, no gradients, no texture, no shadow.

Editorial minimal style, generous negative space. Keep the top 15% and the
bottom 30% of the canvas completely empty. No text, no letters, no people.
```

---

## No.03 — 청각 · 비

```
A flat vector illustration for a magazine cover, 5:6.2 vertical ratio.

Soft pale lavender background (#E8EAF6). Vertical rounded bars in deep indigo
(#4E58B0) falling like rain — about eight bars of varying lengths and opacities,
scattered irregularly across the upper half. Some long and solid, some short
and semi-transparent, like raindrops of different weights. Rounded caps.
No gradients, no texture, no shadow.

Editorial minimal style, generous negative space. Keep the top 15% and the
bottom 30% of the canvas completely empty. No text, no letters, no people.
```

---

## No.04 — 미각·후각 · 수박

```
A flat vector illustration for a magazine cover, 5:6.2 vertical ratio.

Soft pale pink background (#FBE9EC). One half-slice of watermelon shown as a
simple semicircle in the upper-middle area — flat pink-red flesh (#E2566A)
with a bright green rind arc (#A6E22E) along the curved edge, and four small
black oval seeds scattered inside. Facing downward like a dome. Bold simple
shapes, no gradients, no texture, no shadow, no highlights.

Editorial minimal style, generous negative space. Keep the top 15% and the
bottom 30% of the canvas completely empty. No text, no letters, no people.
```

---

## No.05 — 온도 · 그늘과 볕

```
A flat vector illustration for a magazine cover, 5:6.2 vertical ratio.

Soft warm sand background (#F7EDDC). One large solid circle in warm amber
(#E8A13C) in the upper right — like the sun. Below it, one long rounded
horizontal band in deep dusty purple (#4A4668), tilted slightly, stretching
past the left and right edges — like a cast shadow. The warm circle and the
cool band should feel like two different temperatures meeting.
No gradients, no texture, no shadow.

Editorial minimal style, generous negative space. Keep the top 15% and the
bottom 30% of the canvas completely empty. No text, no letters, no people.
```

---

## No.06 — 이름 없는 감각 · 부력

```
A flat vector illustration for a magazine cover, 5:6.2 vertical ratio.

Soft pale teal background (#E1F0EC). A horizontal waterline across the middle
in teal (#3AA394) — a solid rounded bar with a lighter translucent teal fill
below it representing water. Sitting exactly on that line, one circle outlined
in teal with cream (#F5F1EA) fill, floating half above and half below the
surface, with one small solid orange dot (#E85D1C) at its center.
Calm and buoyant. No gradients, no texture, no shadow.

Editorial minimal style, generous negative space. Keep the top 15% and the
bottom 30% of the canvas completely empty. No text, no letters, no people.
```

---

## 받은 이미지 넣는 법

1. 여섯 장을 `assets/` 폴더에 저장 — 이름은 `cover-01.png` … `cover-06.png`
2. 클로드에게 "표지 이미지 넣어줘" 라고 말하면 SVG 자리에 교체해 드립니다
   (지금은 코드로 그린 도형이 들어가 있습니다)
3. 파일이 크면 (장당 1MB 넘으면) 웹용으로 줄여서 넣습니다

## 참고 — 지금 상태

현재 표지는 **코드로 그린 도형**입니다. 그대로 두어도 완성된 상태이고,
ChatGPT 이미지는 더 손맛 있는 느낌을 원할 때의 선택지입니다.
둘을 섞지 말고 여섯 장 전부 한 방식으로 통일하는 편이 좋습니다.
