# 얼굴을 반영한 인스타툰 샘플 v2

- 제작일: 2026-10-25
- 요청: 사용자가 제공한 본인 사진의 얼굴을 반영해 이전 샘플을 다시 제작.
- 결과: [얼굴 반영 2컷 샘플](sample-02-portrait.png)
- 제작 도구: 내장 image_gen 이미지 편집 도구.
- 반영한 외형: 둥근 얇은 금속테 안경, 자연스럽게 가른 짧은 검은 머리, 얼굴 윤곽과 차분한 표정.
- 유지한 요소: 기존 2컷 구도, 책상과 노트, 맨투맨, 흑백 선화, 대사.
- 육안 검수: 두 컷의 얼굴·안경·머리 일관성과 한글 말풍선 확인.
- 대사: “내 일상도 만화가 될까?” / “일단 한 컷부터.”
- 기존 sample-01.png는 비교용으로 보존. 원본 얼굴 사진은 저장소에 복사하지 않음.

## 최종 편집 프롬프트

```text
Use case: identity-preserve
Asset type: revised two-panel black-and-white Korean Instagram comic, portrait 4:5 page.
Primary request: Edit reference image 1, the previous two-panel comic, replacing the placeholder protagonist in BOTH panels with a recognizably stylized likeness of the actual user in reference image 2, the photographic portrait.
Input roles: Image 1 = comic EDIT TARGET and layout/linework reference. Image 2 = facial identity reference ONLY, not a background or scene to reproduce.
Facial likeness to prioritize: adult man with an oval face and soft but defined jaw, fuller cheeks, short black hair parted slightly off center with natural volume, a swept fringe curving across the forehead, short neat sides exposing ears; thin dark metallic round eyeglasses with a delicate bridge; fairly straight brows, natural moderately sized almond-shaped eyes, medium straight nose, subtle closed lips, calm reserved expression, clean shaven. Use adult masculine proportions. Translate his recognizable features into simple ink manga linework. Do not use the placeholder's fluffy bob, very large sparkling eyes, lashes or childlike face. Keep clear consistent identity in both views.
Keep unchanged: two stacked wide panels, white gutters and thin black borders, room and desk, notebook, cup, pen, loose plain sweatshirt, scene composition, hand poses, narrative beats, black-and-white palette and legible Korean dialogue. The user's suit in photo is not required: keep the comic sweatshirt. Top: protagonist resting cheek on hand and pondering. Bottom: protagonist starting to draw with a very small determined smile.
Style: warm restrained everyday Korean indie comic, fine hand-drawn black ink lines on pure white, selective black fill in hair, simplified adult face, sparse hatching, no color, no gray wash, no photoreal skin.
Text verbatim: top speech bubble "내 일상도 만화가 될까?" ; bottom speech bubble "일단 한 컷부터."
No other text, no title, no watermarks, no social UI. Preserve the comic's general composition and edit the character carefully to honor the portrait likeness.
```

