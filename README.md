# beauty-review-writer

네이버 화장품 리뷰 블로그 말투로 리뷰 글을 써 주는 Claude 스킬입니다.

## 구조
```
beauty-review-writer/
├── SKILL.md                     # 스킬 본문 (구조·말투·점검 목록)
└── references/
    └── style-samples.md         # 실제 블로그 글 샘플 (직접 채우기)
```

## 사용법
1. `references/style-samples.md`에 실제 리뷰 글 3~5개를 붙여넣습니다.
2. 이 폴더를 GitHub 저장소에 올리거나 Claude 스킬로 등록합니다.
3. "OO 토너 리뷰 써줘" 처럼 요청합니다.

## 글 구성
[어떤 걸 리뷰] → [제품 소개] → [느낀 점]
