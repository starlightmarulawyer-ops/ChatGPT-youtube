# 인스타툰 스타일 샘플

- 제작일: 2026-10-25
- 요청: 사용자가 첨부한 흑백 일상툰과 같은 방향으로 본인의 인스타툰 제작이 가능한지 확인.
- 결과: [2컷 샘플](sample-01.png)
- 제작 도구: 내장 image_gen 이미지 생성 도구.
- 임시 캐릭터와 창작 대사로 만든 스타일 검토용 샘플이며 사용자 외모 또는 실제 경험을 반영한 결과물이 아니다.
- 참고 요소: 가는 흑백 선화, 단순한 배경, 짧은 말풍선, 표정 중심의 일상 장면.
- 생성 결과는 참고 이미지보다 눈과 머리카락 묘사가 풍성하다. 다음 버전에서는 더 단순한 선과 작은 표정을 선택할 수 있다.
- 후속 제작에 필요한 정보: 주인공 외형·성격, 첫 화로 쓸 실제 에피소드, 원하는 컷 수.
- 육안 검수: 두 컷의 캐릭터 일관성과 한글 대사 확인. 대사: “내 일상도 만화가 될까?” / “일단 한 컷부터.”
- 사용자가 첨부한 타 작가의 원본 스크린샷은 저장소에 복사하지 않았다.

## 최종 생성 프롬프트

```text
Use case: illustration-story
Asset type: Korean Instagram comic visual direction sample, single portrait page, 4:5 aspect ratio.
Primary request: Create an original two-panel black-and-white everyday-life webcomic inspired by the general visual qualities of the supplied reference: thin lively hand-drawn ink lines, expressive simple eyes, restrained facial expressions, sparse interior details, clear speech bubbles, intimate gentle humor.
Input images: Image 1 is STYLE REFERENCE ONLY. It is a screenshot of an existing comic in a social feed. Do not reproduce its characters, story, dialogue, panel artwork, account name, or social UI.
Subject: One original young adult placeholder protagonist, short softly wavy dark hair, rounded small glasses, loose plain sweatshirt, seated at a desk with a blank notebook and pen. This is a provisional design, not a claimed likeness of the user. Keep protagonist visually consistent in both panels. No additional characters.
Composition: Two generous horizontal panels stacked vertically on a white portrait page. Thin black panel borders, white gutters, ample breathing room. Top panel medium view of protagonist looking thoughtfully at notebook, pen poised. Bottom panel slightly closer view, protagonist makes the first pen stroke with a small determined smile. Background only desk, small cup and a few simple room lines. Not too cute or chibi; clean readable Korean indie slice-of-life comic.
Palette: pure white background and black ink only, very light sparse line hatching, no color, no gray wash, no photographic effects.
Text (verbatim, Korean lettering large, crisp and easy to read): In a speech bubble in top panel: "내 일상도 만화가 될까?" In a speech bubble in bottom panel: "일단 한 컷부터."
Constraints: No other words, no title, no signature, no watermark, no logos, no Instagram interface. Both bubbles must be fully within panel edges. Draw completely new compositions and character design; reference only general monochrome linework and quiet conversational pacing. Polished coherent artwork suitable for a first style preview.
```

