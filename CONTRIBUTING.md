# Contributing to JS Edge Cases 🧩

First off, thank you for considering contributing to this project! It's people like you who make the JavaScript ecosystem so... "interesting."

---

## 🌐 Language Requirements (Mandatory)

To ensure accessibility for a global audience, please follow these language rules:
- **At least one language (English or Korean) is MANDATORY** for all text fields (`title`, `desc`, `challenge`, `result`).
- If you only provide one language, you can leave the other field empty or use the same text for both.
- **English is highly recommended** as the primary language for global accessibility.

### 🇰🇷 한국어 기여자분들께
- 모든 텍스트 필드에 **한국어 또는 영어 중 최소 하나는 반드시 입력**해 주셔야 합니다.
- 한쪽 언어 번역이 어렵다면, 동일한 내용을 양쪽 필드(`ko`, `en`)에 모두 적어주셔도 무방합니다.

---

## 🛠️ How Can I Contribute?

### 1. Suggesting New Edge Cases
If you've found a weird JavaScript behavior that isn't in our collection yet:
1. Go to the [Issues](https://github.com/kangjung/js-edge-cases/issues) page.
2. Click **New Issue** and select the **🧩 New Edge Case Suggestion** template.
3. Fill out the form with your code snippet and explanation.

### 2. Direct Code Contributions (Pull Requests)
If you want to add the case directly:
1. **Fork** the repository.
2. Open `cases.json` in the root directory.
3. Add your new case following the schema below.
4. Open a **Pull Request** to the `main` branch.

---

## 📝 `cases.json` Schema Guide

Every entry in `cases.json` must follow this structure. Note that the **ID is handled automatically** by the system.

```json
{
  "title": { "ko": "한국어 제목", "en": "English Title" },
  "desc": { "ko": "설명", "en": "Description" },
  "code": "for(let x = 5; x --> 0; ) { console.log(x); }",
  "challenge": { "ko": "질문", "en": "Challenge question" },
  "result": { "ko": "결과 및 해설", "en": "Result and explanation" }
}