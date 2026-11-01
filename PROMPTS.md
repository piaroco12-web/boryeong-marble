# 그림 프롬프트 — 「다 같이 돌자, 보령 한 바퀴」(보령탐험대)

> 각 프롬프트는 공통 스타일 문장까지 들어 있는 완성본입니다. 코드 블록 오른쪽 위 복사 버튼으로 복사해 ChatGPT에 그대로 붙여 넣으세요.
> 저장 위치: `public/regions/boryeong/art/` · 파일 이름을 그대로 쓰면 게임에 바로 들어갑니다.

그림 **47장 완료** · 앱 아이콘 1장 ⬜ 필요 (⬜ 필요 · ✅ 완료)

## 목차

- [0. 기준 이미지 — 가장 먼저](#base)
- [1. 지도 바탕](#map)
- [2. 장소 건물 12](#bld)
- [3. 안내 캐릭터 — 보미 · 령이](#char)
- [4. 플레이어 말 4](#piece)
- [5. 미니게임 그림 10](#mg)
- [6. 화면(UI) 그림 9](#ui)
- [7. 앱 아이콘 2](#icon)

## 체크리스트

| 상태 | 파일 | 그림 |
|---|---|---|
| ✅ | `style-anchor.png` | 기준 이미지: 보령머드테마파크 |
| ✅ | `map-base.png` | 지도 바탕 (건물 없이) |
| ✅ | `bld-mudpark.png` | 보령머드테마파크 (= 기준 이미지) |
| ✅ | `bld-beach.png` | 대천해수욕장 |
| ✅ | `bld-muchangpo.png` | 무창포 신비의 바닷길 |
| ✅ | `bld-inkstone.png` | 남포벼루 마을 |
| ✅ | `bld-coal.png` | 보령석탄박물관 |
| ✅ | `bld-seongju.png` | 성주사지 |
| ✅ | `bld-suyeong.png` | 충청수영성 |
| ✅ | `bld-oyster.png` | 천북 굴단지 |
| ✅ | `bld-tunnel.png` | 보령해저터널 |
| ✅ | `bld-oeyeon.png` | 외연도 상록수림 |
| ✅ | `bld-start.png` | 출발: 머드축제 마당 |
| ✅ | `bld-rest.png` | 쉼터: 죽도 상화원 솔숲 |
| ✅ | `bld-chance.png` | 찬스: 머드 보물 상자 |
| ✅ | `char-bomi-normal.png` | 보미 기본 |
| ✅ | `char-bomi-think.png` | 보미 생각 |
| ✅ | `char-bomi-happy.png` | 보미 정답 |
| ✅ | `char-bomi-sad.png` | 보미 오답 |
| ✅ | `char-bomi-surprised.png` | 보미 시간 초과 |
| ✅ | `char-ryeongi-normal.png` | 령이 기본 |
| ✅ | `char-ryeongi-think.png` | 령이 생각 |
| ✅ | `char-ryeongi-happy.png` | 령이 정답 |
| ✅ | `char-ryeongi-sad.png` | 령이 오답 |
| ✅ | `char-ryeongi-surprised.png` | 령이 시간 초과 |
| ✅ | `piece-mud.png` | 말: 머드 요정 |
| ✅ | `piece-oyster.png` | 말: 천북 굴돌이 |
| ✅ | `piece-shrimp.png` | 말: 보령 대하 |
| ✅ | `piece-lighthouse.png` | 말: 등대 로봇 |
| ✅ | `mg-tidal-flat.png` | 갯벌에서 캐기: 갯벌 배경 |
| ✅ | `mg-oyster.png` | 갯벌에서 캐기: 굴 |
| ✅ | `mg-card-back.png` | 짝 맞추기: 카드 뒷면 |
| ✅ | `mg-card-1.png` | 짝 맞추기: 머드 방울 |
| ✅ | `mg-card-2.png` | 짝 맞추기: 굴 |
| ✅ | `mg-card-3.png` | 짝 맞추기: 남포벼루 |
| ✅ | `mg-card-4.png` | 짝 맞추기: 해저터널 |
| ✅ | `mg-drill.png` | 해저터널 뚫기: 굴착기 (출발점) |
| ✅ | `mg-wonsando.png` | 해저터널 뚫기: 원산도 (도착점) |
| ✅ | `mg-rock.png` | 해저터널 뚫기: 암반 장애물 |
| ✅ | `ui-title-bg.png` | 첫 화면 배경 |
| ✅ | `ui-bus.png` | 보령 버스 아이콘 |
| ✅ | `ui-heart.png` | 하트 (가득) |
| ✅ | `ui-heart-empty.png` | 하트 (빈칸) |
| ✅ | `ui-score.png` | 점수 아이콘 |
| ✅ | `ui-hint.png` | 힌트 아이콘 |
| ✅ | `ui-stamp.png` | 도장 자국 |
| ✅ | `ui-trophy.png` | 완주 트로피 |
| ✅ | `ui-paper.png` | 카드 바탕 종이 (반복 무늬) |

## 공통 스타일 문장

ChatGPT가 스타일을 잊은 것 같을 때 따로 붙여 넣으세요. (아래 프롬프트에는 이미 들어 있습니다.)

```text
[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

---

<a id="base"></a>

## 0. 기준 이미지 — 가장 먼저

1. **한 대화창에서 끝까지** 만드세요. 새 대화를 열면 스타일이 달라집니다.
1. 기준 이미지(`style-anchor.png`)를 확정한 뒤, 이후 모든 요청에 **그 그림을 첨부**합니다.
1. 투명 배경이 안 나오면 "make the background pure white #FFFFFF"로 다시 요청하고 배경은 정리 도구로 지웁니다.
1. 이미 있는 그림도 더 좋게 다시 만들고 싶으면 같은 프롬프트로 다시 요청해 같은 이름으로 덮어쓰면 됩니다.

### ⬜ 기준 이미지: 보령머드테마파크 — `style-anchor.png` + `bld-mudpark.png`

1024×1024 · 투명 배경

```text
A single miniature diorama building piece: a cheerful seaside mud-spa pavilion inspired by the Boryeong Mud Theme Park in Boryeong, Korea — a low modern building with a wavy blue roof, big round windows, open-air mud pools with soft grey-brown mud and bubbles beside it, a tiny mud slide, and small stacked jars of mud cosmetics at the entrance. The building sits on a round grassy base disc with a strip of pale beach sand on one side, like a board-game tile piece. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

→ 마음에 들 때까지 다시 만들고, 확정한 그림을 `style-anchor.png`와 `bld-mudpark.png` 두 이름으로 저장합니다.

---

<a id="map"></a>

## 1. 지도 바탕

### ⬜ 지도 바탕 — `map-base.png`

1536×1024 · 불투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a wide isometric miniature diorama landscape of a Korean west-coast county on a tabletop: a wide pale sandy beach and blue sea along the whole LEFT (west) side with two or three small green islands offshore, a long low mud flat with shallow tide pools at the top-left, a gentle wooded mountain ridge with pine forest on the right (east), a small town basin in the middle, a reservoir lake at the bottom-right, and a thin road that disappears into a tunnel portal near the coast. Leave plenty of empty open flat ground spread across the land where game pieces will be placed later. NO buildings, no text. Wide landscape format, the land fills the frame like an island board on a table.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

건물이 그려져 나오면 "remove all buildings"로 다시 요청하세요.

---

<a id="bld"></a>

## 2. 장소 건물 12

모든 건물 프롬프트는 아래 **공통 앞부분**으로 시작합니다. 프롬프트 블록에 이미 들어 있습니다.

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.
```

### ⬜ 대천해수욕장 — `bld-beach.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A wide sandy beach scene: pale soft sand with gentle blue waves on one edge, three colorful striped beach parasols, a small white lifeguard tower with a round roof, a tiny red-and-white beach ball and a bucket, and a short wooden boardwalk. The whole scene sits on a round base disc, half sand and half grass. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 무창포 신비의 바닷길 — `bld-muchangpo.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A magical sea-parting scene: the blue sea split open down the middle so a narrow wet stony path appears, leading from the shore to a tiny rocky green island; shallow water walls on both sides of the path with little shells and starfish on the exposed seabed, a small white-and-red striped lighthouse on the shore. The whole scene sits on a round base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 남포벼루 마을 — `bld-inkstone.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A small stone-carving workshop village: a tiled-roof Korean workshop with an open front, a low wooden workbench with chisels and a hammer, several polished black stone inkstones of different sizes displayed on a rack, a pile of raw dark stone blocks beside it, and a small brush and ink stick on a tray. The whole scene sits on a round grassy base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 보령석탄박물관 — `bld-coal.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A small coal-mining museum: a sturdy brick-and-concrete building with a pitched roof, a tall steel pit-head winding tower with a big wheel beside it, a short rail track coming out of a dark timber-framed mine entrance, and two small coal wagons filled with shiny black coal. A yellow miner's helmet with a lamp rests on a crate. The whole scene sits on a round grassy base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 성주사지 — `bld-seongju.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A quiet ancient temple site with only stone remains: a wide flat grassy field with low square stone foundation blocks where wooden halls once stood, three small weathered stone pagodas in a row, and one tall stone memorial stele standing on a turtle-shaped stone base under a small protective wooden canopy. A few pine trees and a stone path. Calm and respectful, not scary, nothing written on the stele. The whole scene sits on a round grassy base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 충청수영성 — `bld-suyeong.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A small Joseon-era naval fortress on a coastal hill: a curved stone rampart wall with a traditional arched stone gate topped by a tiled-roof gatehouse, a small tiled-roof command pavilion inside, and a tiny wooden Korean warship moored at a little stone pier below the wall. Plain cloth banners with no letters. The whole scene sits on a round grassy base disc with a thin strip of blue sea. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 천북 굴단지 — `bld-oyster.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A cozy seaside oyster-grilling hut: a small blue-roofed hut with an open side, a round grill drum with a wire mesh on top covered with oysters in their shells and a little steam, woven baskets heaped with oysters, a stack of oyster shells, a short wooden pier with a tiny fishing boat. The whole scene sits on a round base disc, half grass and half mud flat. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 보령해저터널 — `bld-tunnel.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

An undersea road tunnel piece: a cut-away cross-section of the seabed showing a bright arched tunnel tube running under blue water, with a tiny car driving inside and small round ceiling lights; on top, the sea surface with gentle waves and two little fish, and a clean concrete tunnel portal with a curved canopy on the land side where the road enters. The whole scene sits on a round base disc, half grass and half blue sea. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 외연도 상록수림 — `bld-oeyeon.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A small round green island piece: a rocky island rising from blue water, covered with a dense dark-green evergreen broadleaf forest of rounded treetops, a tiny stone path winding up through the trees, a few seabirds, and a small stone jetty with one little blue fishing boat at the shore. The whole island sits on a round base disc of blue sea. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 출발: 머드축제 마당 — `bld-start.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부 · **다른 건물보다 살짝 크게**

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base, but slightly larger than the other pieces.

A festive beach festival plaza: a small outdoor stage with a wavy blue canopy, colorful bunting flags with no letters, two big playful mud pools with bubbles and a mud slide, a shower arch spraying water, a few food stalls with striped awnings, and a big cute mascot statue of a smiling mud drop (original design). The whole scene sits on a round base disc, half beach sand and half grass. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 쉼터: 죽도 상화원 솔숲 — `bld-rest.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A restful seaside garden corner: a small traditional Korean pavilion (jeongja) with a tiled roof on a low wooden deck walkway that curves among twisted pine trees, a wooden bench, and a little table holding a steaming pot of oyster soup and two small bowls. A glimpse of calm blue sea at the edge. The whole scene sits on a round grassy base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 찬스: 머드 보물 상자 — `bld-chance.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create another building piece in exactly the same style, scale, camera angle, lighting, and round grassy base.

A cute wooden treasure chest with its lid open, overflowing with glossy grey-brown mud, little round jars of mud cream, pearly shells, a starfish and a few shiny bubbles rising out of it, all on the same round base disc. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

---

<a id="char"></a>

## 3. 안내 캐릭터 — 보미 · 령이

먼저 **기본(normal)** 1장을 만들고, 그 그림을 첨부해 표정 4장을 뽑습니다. 같은 옷·같은 자세를 유지하는 것이 중요합니다.

### ⬜ 보미 기본 — `char-bomi-normal.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a cute chibi child explorer character as a small painted toy figure: a girl with two short braids wearing a wide-brim straw sun hat with a blue ribbon, a sleeveless sky-blue vest over a white tee, rolled-up shorts, little rubber boots, carrying a small bamboo clam basket in one hand and a short hand hoe in the other. Full body, standing, facing slightly to the left, friendly smile. Centered, the whole figure visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 령이 기본 — `char-ryeongi-normal.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a cute chibi child explorer character as a small painted toy figure: a boy with short tousled hair wearing a navy sailor-style cap, an orange life-vest-shaped sleeveless jacket over a striped tee, shorts, little rubber boots, with a small telescope hanging on his chest and a rolled map tucked under his arm. Full body, standing, facing slightly to the left, bright cheerful smile. Centered, the whole figure visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 표정 4장씩 — 기본 그림을 첨부하고 `<표정>`만 바꿔 8장

1024×1024 · 투명 배경 · 📎 **그 캐릭터의 기본 그림** 첨부

```text
Same character as the attached image, same pose, same outfit, same camera angle and lighting. Only change the facial expression to: <표정>. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop. No text, no letters, no logos, no watermark.
```

| 보미 | 령이 | `<표정>`에 넣을 영어 | 게임에서 쓰는 곳 |
|---|---|---|---|
| `char-bomi-think.png` | `char-ryeongi-think.png` | `thinking with a finger on the chin, eyes looking up` | 문제를 낼 때 |
| `char-bomi-happy.png` | `char-ryeongi-happy.png` | `happy and cheering with both arms up` | 정답 |
| `char-bomi-sad.png` | `char-ryeongi-sad.png` | `a little sad, downturned mouth` | 오답 |
| `char-bomi-surprised.png` | `char-ryeongi-surprised.png` | `surprised, wide open eyes and round mouth` | 시간 초과 |

---

<a id="piece"></a>

## 4. 플레이어 말 4

네 개 모두 **같은 크기의 작은 둥근 받침** 위에 세웁니다. 받침 색은 서해 파랑 `#2E7FA8`입니다.

### ⬜ 머드 요정 — `piece-mud.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a board-game player piece: a cute glossy mud-drop character, a rounded grey-brown blob with a soft swirl on top, tiny arms and legs, big round friendly eyes and rosy cheeks, a few small bubbles floating around it. It stands on a small round blue (#2E7FA8) pedestal. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 천북 굴돌이 — `piece-oyster.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a board-game player piece: a cute oyster character, a rough beige-grey shell slightly open like a smiling mouth with a soft pearly body peeking out, two tiny arms at the shell edges, big round eyes. It stands on a small round blue (#2E7FA8) pedestal. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 보령 대하 — `piece-shrimp.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a board-game player piece: a cute big shrimp character standing upright on its tail, pale pink-orange shell with soft stripes, long curly whiskers, tiny claws raised cheerfully, big round eyes. It stands on a small round blue (#2E7FA8) pedestal. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 등대 로봇 — `piece-lighthouse.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a board-game player piece: a cute small robot shaped like a red-and-white striped lighthouse, with a glowing round lamp head, a small glass dome, two short arms and stubby feet, a friendly face on the tower body. It stands on a small round blue (#2E7FA8) pedestal. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

---

<a id="mg"></a>

## 5. 미니게임 그림 10

| 미니게임 | 쓰는 그림 |
|---|---|
| 갯벌에서 캐기 (타이밍) | `mg-tidal-flat.png`, `mg-oyster.png` |
| 머드 짝 맞추기 | `mg-card-back.png`, `mg-card-1~4.png` |
| 해저터널 뚫기 (순차 명령) | `mg-drill.png`, `mg-wonsando.png`, `mg-rock.png` |

### ⬜ 갯벌 배경 — `mg-tidal-flat.png`

1536×1024 · 불투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a wide front-view background of a Korean west-coast tidal mud flat at low tide: smooth grey-brown wet mud in the foreground with shallow winding water channels, scattered shells and tiny crab holes, a line of oyster racks and a few wooden stakes in the middle distance, calm blue sea and a soft hazy sky at the top. No characters, no buildings, no text. Wide landscape format, viewed straight from the front.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 굴 — `mg-oyster.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a single whole oyster in its shell, front view, slightly tilted: a rough layered beige-grey shell with a pearly cream interior just visible at the opening, a little wet shine and one drop of water. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 카드 뒷면 — `mg-card-back.png`

768×1024 · 불투명 배경

```text
Create a flat playing-card back design, front view, no 3D perspective: a vertical card filled with a traditional Korean pattern of blue waves and small shell shapes on a soft beige ground, with a thin double border frame and a small circular wave emblem in the center. Symmetrical, evenly repeating, calm and clean. No letters, no numbers, no logos, no watermark.
```

### ⬜ 짝 맞추기 카드 그림 4장 — `mg-card-1.png` ~ `mg-card-4.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부 · 한 장씩 만드세요

```text
Using the attached image as the style reference, create a single centered object in the same toy-diorama style, simple and bold so it reads clearly at small size: <아래 표의 설명>. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

| 파일 | `<설명>`에 넣을 영어 |
|---|---|
| `mg-card-1.png` | `a glossy grey-brown mud drop with a few bubbles` |
| `mg-card-2.png` | `a single oyster in its rough beige shell, slightly open` |
| `mg-card-3.png` | `a polished black rectangular Korean inkstone with a small ink well and a brush resting on it` |
| `mg-card-4.png` | `a small arched undersea tunnel portal with blue water above it` |

### ⬜ 터널 굴착기 (출발점) — `mg-drill.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a single cute tunnel boring machine, side view, simple and bold so it reads clearly at small size: a chunky yellow-orange machine with a big round silver cutting head of concentric rings at the front, small tracks underneath, a tiny flashing lamp on top. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 원산도 (도착점) — `mg-wonsando.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a single small round island, simple and bold so it reads clearly at small size: a cute green island with two gentle hills, a few pine trees, a tiny white lighthouse on the right hill and a small sandy beach at the front, sitting on a small disc of blue sea with a soft white wave ring around it. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 암반 장애물 — `mg-rock.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a single chunky block of hard rock, simple and bold so it reads clearly at small size: a rough grey-brown granite boulder with flat angular faces and a few cracks, slightly wider at the bottom, no moss. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

---

<a id="ui"></a>

## 6. 화면(UI) 그림 9

아이콘은 화면에서 작게(64px) 보입니다. **단순하고 굵게** 나오는지 확인하세요. 파일이 없으면 지금처럼 이모지로 보이고, 넣으면 바로 바뀝니다.

### ⬜ 첫 화면 배경 — `ui-title-bg.png`

1536×1024 · 불투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a wide key-art background for the title screen of a board game: the Boryeong miniature island board seen from a low angle along the bottom of the frame — a sandy beach with mud pools, a small lighthouse, an oyster hut, a green offshore island and a tunnel portal — with a soft warm sunset sky above, fluffy clouds, a few seagulls and floating soap-like bubbles. Keep the CENTER and upper middle of the image calm and empty (soft sky) for the title text. No characters, no text.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 보령 버스 아이콘 — `ui-bus.png`

1024×1024 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a game UI icon in the same toy-diorama style, but simpler and bolder so it reads clearly at small size (64px). Front view, slightly tilted, chunky and glossy.

A cute chunky little country bus, cream and sea-blue colors with a wavy white stripe along the side, round headlights, three-quarter front view. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 하트 (가득) — `ui-heart.png`

512×512 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a game UI icon in the same toy-diorama style, but simpler and bolder so it reads clearly at small size (64px). Front view, slightly tilted, chunky and glossy.

A glossy plump heart made of a pearly shell, warm coral-red with a soft pearl shine in the middle and a tiny bubble on top. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 하트 (빈칸) — `ui-heart-empty.png`

512×512 · 투명 배경 · 📎 `ui-heart.png` 첨부

```text
The same plump heart shape as the attached image but empty: pale beige translucent with a soft outline, like an empty slot, no shine. Same size, same angle, same position. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop. No text, no letters, no logos, no watermark.
```

### ⬜ 점수 아이콘 — `ui-score.png`

512×512 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a game UI icon in the same toy-diorama style, but simpler and bolder so it reads clearly at small size (64px). Front view, slightly tilted, chunky and glossy.

A shiny golden coin with an embossed scallop shell on its face (no letters), slightly tilted. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 힌트 아이콘 — `ui-hint.png`

512×512 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a game UI icon in the same toy-diorama style, but simpler and bolder so it reads clearly at small size (64px). Front view, slightly tilted, chunky and glossy.

A cute magnifying glass with a wooden handle and a small glowing white shell inside the lens. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 도장 자국 — `ui-stamp.png`

512×512 · 투명 배경

```text
Create a flat game UI element, front view, no 3D perspective: a round red ink seal stamp impression like a traditional Korean seal, slightly rough ink texture at the edges, with a simple wave-and-shell symbol in the center and a double ring border. No letters. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop. No logos, no watermark.
```

### ⬜ 완주 트로피 — `ui-trophy.png`

512×512 · 투명 배경 · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a game UI icon in the same toy-diorama style, but simpler and bolder so it reads clearly at small size (64px). Front view, slightly tilted, chunky and glossy.

A cute golden trophy cup with two handles on a small base, a big pearl set in the front of the cup and a tiny wave pattern around the rim, a few sparkles around it. No letters. Centered, the whole object visible with a small margin, nothing cut off. Isolated on a fully transparent background (PNG with alpha channel), no floor, no backdrop.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

### ⬜ 카드 바탕 종이 — `ui-paper.png`

768×768 · 불투명 배경 · **이어 붙여도 자연스럽게(seamless)**

```text
Create a flat seamless tileable paper texture, front view, no 3D perspective: warm ivory handmade Korean paper (hanji) with soft visible fibers, a very faint pale blue wave watermark pattern spread evenly, slightly uneven tone. Very low contrast so dark text stays readable on top. Seamless on all four edges. No letters, no numbers, no logos, no watermark.
```

---

## 사진 준비 (선택)

사진 퀴즈(`questions.json`의 문항에 `"image": "photos/파일명.jpg"`를 더하면 문제 위에 사진이 나옵니다)를 쓰려면 아래 사진을 모아 `public/regions/boryeong/photos/`에 넣고 출처 표를 함께 주세요.

| 분류 | 사진 |
|---|---|
| 장소 | 대천해수욕장, 머드축제 현장, 무창포 바닷길, 성주사지 석탑과 비, 충청수영성 성문, 보령석탄박물관, 천북 굴단지, 보령해저터널 입구, 외연도, 남포벼루 |
| 특산물·음식 | 머드 화장품, 굴구이, 대하구이, 남포벼루, 보령 김 |
| 인물·유물 | 낭혜화상탑비, 수영성 관련 유물 |

- 가로 4:3, 가로 1200px 이상, 간판·이름이 보이지 않는 사진이 퀴즈용으로 좋습니다.
- 파일 이름은 영문 소문자 (예: `daecheon-beach.jpg`, `mud-festival.jpg`).
- **직접 촬영**, **공공누리 제1유형**, **기관 허락 사진**만 씁니다. 블로그·뉴스 사진은 허락 없이 쓰지 않습니다.

---

<a id="icon"></a>

## 7. 앱 아이콘 — `public/icons/`

바탕화면에 "앱 설치"로 둘 때 쓰는 아이콘입니다. 지금은 **금산판 아이콘이 그대로 들어 있어** 반드시 다시 만들어 덮어써야 합니다.
한 장(1024×1024)을 만들고 **512×512**와 **192×192**로 줄여 저장하세요. 저장 위치는 `public/icons/`이고 파일 이름은 `icon-512.png`, `icon-192.png`입니다.

### ⬜ 앱 아이콘 — `icon-512.png` + `icon-192.png`

1024×1024 · **불투명 배경** (아이콘은 배경이 꽉 차야 합니다) · 📎 `style-anchor.png` 첨부

```text
Using the attached image as the style reference, create a square mobile app icon, front view, centered, simple and bold so it reads clearly at 64px: a glossy cute mud drop with a tiny white shell and one small bubble beside it, sitting on a sea-blue rounded-square background with a soft radial glow and a thin pale sand strip across the bottom corner. Fill the whole square edge to edge with the background, leave a small safe margin around the subject, no rounded corner cut out. No text, no letters, no numbers, no logos, no watermark.

[STYLE]
Style: cute miniature diorama, like a premium handmade toy model photographed on a tabletop.
Isometric 3/4 view from the front-right, camera about 35 degrees above.
Soft rounded shapes, chunky proportions, smooth clay and painted-wood texture with fine hand-painted details.
Soft warm key light from the upper-left, gentle ambient occlusion, soft contact shadow only directly under the object.
Pastel colors with these accents: West Sea blue #2E7FA8, mud grey-brown #7A6652,
shell beige #D8C4A8, sunset orange #E4713A, pine green #3F7A52.
High detail, crisp clean silhouette edges, cohesive with the attached reference image.
Clean, bright, friendly, for elementary school children.
No text, no letters, no numbers, no signs with writing, no logos, no watermark.
```

> 아이콘은 `public/icons/`에 들어가며 `art/` 폴더가 아닙니다. 파일 이름을 바꾸면 `public/manifest.webmanifest`도 함께 고쳐야 합니다.
