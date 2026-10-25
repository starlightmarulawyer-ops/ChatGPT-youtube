# 만화적 표현을 강화한 인스타툰 샘플 v3

- 제작일: 2026-10-25
- 요청: 얼굴 반영 버전이 너무 진지하므로 첫 샘플처럼 만화적 요소를 되살려 다시 제작.
- 결과: [만화적 표현 강화 2컷 샘플](sample-03-cartoon.png)
- 제작 도구: 내장 image_gen 이미지 편집 도구.
- 유지: 사용자 외형의 둥근 금속테 안경과 짧은 가르마 머리, 기존 구도와 대사.
- 변경: 눈을 키우고 코·입을 작게 단순화, 둥근 얼굴 윤곽, 볼의 짧은 선과 가벼운 표정 추가.
- 육안 검수: 두 컷 캐릭터의 일관성, 이전 버전 대비 만화적 얼굴 표현, 한글 대사 확인.
- 대사: “내 일상도 만화가 될까?” / “일단 한 컷부터.”
- 앞선 버전은 비교용으로 보존. 원본 얼굴 사진은 저장소에 복사하지 않음.

## 최종 편집 프롬프트

```text
Use case: identity-preserve
Asset type: two-panel black-and-white Korean Instagram comic, edited version 3.
Primary request: The user says image 1, the current comic with his face, is TOO SERIOUS AND REALISTIC. Redraw the protagonist in BOTH panels with the playful cartoon simplification of image 2, the original sample. Retain the user's recognizable short side-parted black hair and thin round glasses. Prioritize the cute everyday comic style over realistic portrait rendering.
Input roles: Image 1 = EDIT TARGET, preserve its two-panel layout, poses, background and dialogue. Image 2 = STRONG reference for cartoon proportions, simplified features and lively expressions. Image 3 = user's real photo, use only for broad identity cues (hair part and round glasses), do NOT render realistic facial anatomy.
Specific character changes: Rounder softer cheek outline, slightly bigger head relative to body, large simple rounded eyes about the size and charm of image 2, simple black pupils with one tiny highlight, very small nose represented by just a tiny mark, tiny expressive mouth, minimal eyebrows, slight cheek blush indicated by two short ink strokes. No realistic nose bridge, no lip contours, no cheekbone shading, no realistic jaw shading, no stern brow. Keep unmistakably the same adult male character with short parted hair and round wire glasses, not a fluffy bob hairstyle.
Top panel expression: a lighthearted curious daydream, relaxed raised eyebrows, tiny open mouth, eyes looking up with a playful thoughtful air, cheek resting on hand.
Bottom expression: cheerful small closed smile, lively eyes, friendly gentle determination, two tiny comic excitement lines near the head. Warm and approachable rather than handsome realistic portrait. Natural coherent hands.
Hair: simplify into several clear curved tufts and broad ink masses with limited strand lines, short neat sides and visible ear, preserve side part.
Keep: plain loose sweatshirt, same desk and room, notebook, pen, mug, framing, panel borders, speech bubbles, pure white and black ink, no color or gray wash. Background can retain existing fine line detail. Character should look like a simple endearing slice-of-life webcomic drawing, with approximately 70 percent original cartoon style and 30 percent recognizable portrait cues.
Text verbatim in top bubble: "내 일상도 만화가 될까?"
Text verbatim in bottom bubble: "일단 한 컷부터."
No extra text, titles, logos, watermark or interface. Make cartoon simplification clearly visible compared with image 1, with character consistency in both panels.
```

