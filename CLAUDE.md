# CLAUDE.md

## 프로젝트 개요

영어 유치원 Show & Tell용 HTML 프레젠테이션입니다.

- **Topic:** Animal Traits
- **Essential Question:** What is a perfect pet like?
- **대상:** 한국 영유 6~7세, SL2
- **발표 시간:** 약 2~3분 / 9 슬라이드
- **개인 맥락:** 발표자의 할머니 댁에 흰 강아지 한 마리와 검정·흰색 고양이 한 마리가 있음

## 구성 원칙

- `index.html`: 키워드와 사진 중심의 발표 화면
- `script.html`: 영어 full sentence, 한국어 뜻, 몸동작, 예상 질문
- `cards.html`: 9장 큐 카드와 Quick Reference
- `images/`: 사용자가 제공한 사진의 축소·메타데이터 제거 사본

## 발표 구조 결정

1. Title
2. At Grandma’s House — 강아지와 고양이 소개
3. Trait = how an animal looks or acts
4. Dog body traits — white fluffy fur / pointed ears / curly tail
5. Dog behavior traits — friendly / gentle / playful / active
6. Cat traits — black-and-white fur / bright eyes / curious climber
7. Good care — food / water / playtime / clean bed / love
8. Essential Question 답 — friendly / gentle / healthy / loved
9. Thank You + 청중 질문

## 언어 수준

- 한 문장은 가능한 한 4~10단어로 짧게 유지합니다.
- `trait`, `behavior`, `curious`는 주제 핵심 어휘라 사용하되 사진과 쉬운 말로 설명합니다.
- 강아지와 고양이의 성별·이름은 제공되지 않았으므로 대본에서 `it`을 사용합니다.
- “완벽한 반려동물”을 특정 동물이나 외모로 단정하지 않고, 좋은 성격·건강·돌봄의 관계로 답합니다.

## 사진 파일 매핑

| 파일 | 용도 |
|---|---|
| `dog-portrait.jpg` | 타이틀, 할머니 댁 소개 |
| `cat-portrait.jpg` | 타이틀, 할머니 댁 소개, 고양이 외모 |
| `dog-outside.jpg` | 강아지 body traits |
| `child-with-dog.jpg` | friendly / gentle |
| `dog-walk.jpg` | playful / active |
| `cat-curious.jpg` | curious / climb |

사진은 원본의 EXIF를 제거했고, 원본은 프로젝트에 포함하지 않습니다.

## 수정 시 함께 확인할 곳

- traits 문구를 바꾸면 `index.html` 4~8장, `script.html`, `cards.html`의 Quick Reference를 함께 수정합니다.
- 슬라이드 수를 바꾸면 모든 `slide-num`, `totalSlides`, 숫자 키 범위를 함께 수정합니다.
- 개인 사진을 외부에 배포하기 전 공개 동의를 확인합니다.
