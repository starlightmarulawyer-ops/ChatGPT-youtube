# 헤어와 볼살 비교 샘플 3종

- 제작일: 2026-10-25
- 기준: [만화적 표현 강화 버전](../2026-10-25-style-sample/sample-03-cartoon.png)
- 도구: 내장 image_gen 이미지 편집 도구. 같은 기준 이미지를 각각 독립 편집.
- 요청: 가르마를 살짝만 탄 수수한 모습, 헤어를 유지하고 얼굴 살만 조금 줄인 모습, 두 변경을 합친 모습을 각각 제작.

| 번호 | 샘플 | 헤어 | 얼굴 |
| --- | --- | --- | --- |
| 1 | [가르마만 살짝](01-subtle-part.png) | 이마를 덜 드러내고 앞머리를 자연스럽게 내린 수수한 가르마 | 기준의 둥근 볼 유지 |
| 2 | [볼살만 조금 줄임](02-slightly-slimmer-face.png) | 기준 헤어 유지 | 볼의 부피만 조금 줄임 |
| 3 | [가르마 살짝 + 볼살 조금 줄임](03-subtle-part-and-slimmer-face.png) | 가르마 강조를 줄임 | 볼의 부피도 조금 줄임 |

공통 유지 요소: 2컷 구도, 흑백 선화, 큰 만화 눈, 둥근 안경, 작은 코·입, 맨투맨, 대사. 원본 사진은 저장소에 복사하지 않았다.

육안 확인: 3종 모두 구도와 말풍선 대사가 유지됨. 1번은 앞머리가 가장 내려오며 얼굴은 둥근 형태 유지. 2번은 기준의 가르마를 유지하고 볼 윤곽 변화는 미세함. 3번은 가르마와 얼굴 윤곽 변화가 함께 반영됨. 이미지 편집 결과이므로 선 단위로 동일하지는 않음.

## 최종 생성 프롬프트

### 1. 1번 · 가르마만 살짝

```text
Use case: precise-object-edit
Asset type: one full portrait 4:5 page of a two-panel black-and-white Korean everyday Instagram comic.
Input image 1 is the EDIT TARGET, the user's approved playful cartoon version. Make a controlled variation of this exact image, not a new story or new drawing style.
Keep invariant: both stacked panels and borders, composition, room background, desk, pen, notebook, mug, sweatshirt, body and hand poses, cute oversized simple eyes and black pupils, round wire glasses, tiny nose and mouth, small cheek marks, friendly cartoon style and restrained expressions. Maintain the same character in BOTH panels. Keep pure black ink on white with no colors. Do not make him realistic or serious.
Text verbatim and unchanged: top bubble "내 일상도 만화가 될까?" bottom bubble "일단 한 컷부터." No extra text, labels, title, watermark or interface.

Requested controlled variation:
Change ONLY THE HAIRSTYLE in BOTH panels. Replace the pronounced swept curtain part and broad exposed forehead with a modest everyday low-volume haircut: soft black fringe falling naturally forward across most of the forehead, only a very small discreet off-center opening indicating a slight part. The hair should lie closer to the head with less lifted roots, fewer dramatic curved swoops, and simple casual understated styling. Not a perfect symmetrical curtain haircut; not a wide V of exposed forehead; not slicked back. Keep short neat sides and the recognizable short black hairstyle. Preserve the face outline and full rounded cheeks EXACTLY as the edit target. Do not slim the face. This version is hair change only.
```

### 2. 2번 · 볼살만 조금 줄임

```text
Use case: precise-object-edit
Asset type: one full portrait 4:5 page of a two-panel black-and-white Korean everyday Instagram comic.
Input image 1 is the EDIT TARGET, the user's approved playful cartoon version. Make a controlled variation of this exact image, not a new story or new drawing style.
Keep invariant: both stacked panels and borders, composition, room background, desk, pen, notebook, mug, sweatshirt, body and hand poses, cute oversized simple eyes and black pupils, round wire glasses, tiny nose and mouth, small cheek marks, friendly cartoon style and restrained expressions. Maintain the same character in BOTH panels. Keep pure black ink on white with no colors. Do not make him realistic or serious.
Text verbatim and unchanged: top bubble "내 일상도 만화가 될까?" bottom bubble "일단 한 컷부터." No extra text, labels, title, watermark or interface.

Requested controlled variation:
Change ONLY THE CHEEK/FACE OUTLINE in BOTH panels. Slightly reduce cheek fullness, a subtle reduction around 5 to 8 percent of the lower face width, giving a gently slimmer but still soft cute face. Keep the chin round, not pointed; no sharp jaw, cheekbones, hollow cheeks or adult realistic anatomy. Keep head size, eyes, glasses and expression. Preserve the exact original pronounced side-parted black haircut including its fringe direction, part opening, height and volume. DO NOT modify the hair in this version. This version is slightly slimmer cheeks only.
```

### 3. 3번 · 가르마 살짝 + 볼살 조금 줄임

```text
Use case: precise-object-edit
Asset type: one full portrait 4:5 page of a two-panel black-and-white Korean everyday Instagram comic.
Input image 1 is the EDIT TARGET, the user's approved playful cartoon version. Make a controlled variation of this exact image, not a new story or new drawing style.
Keep invariant: both stacked panels and borders, composition, room background, desk, pen, notebook, mug, sweatshirt, body and hand poses, cute oversized simple eyes and black pupils, round wire glasses, tiny nose and mouth, small cheek marks, friendly cartoon style and restrained expressions. Maintain the same character in BOTH panels. Keep pure black ink on white with no colors. Do not make him realistic or serious.
Text verbatim and unchanged: top bubble "내 일상도 만화가 될까?" bottom bubble "일단 한 컷부터." No extra text, labels, title, watermark or interface.

Requested controlled variation:
Make BOTH changes together in BOTH panels. Hair: replace the pronounced lifted curtain part and broad exposed forehead with an understated everyday low-volume short black haircut, soft fringe naturally falling forward across most of the forehead and only a tiny discreet off-center opening suggesting a slight part. Hair lies closer to head, fewer dramatic swoops, no wide V or symmetrical curtains, short neat sides. Face: gently reduce cheek fullness by about 5 to 8 percent of lower-face width, still round and cute, no sharp chin, angular jaw, hollow cheeks or realistic features. Retain large simple eyes, tiny nose/mouth and round glasses. This version combines a subtle part AND slightly slimmer cheeks.
```

