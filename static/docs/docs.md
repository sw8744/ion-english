# 도움말

## 1. 양식 모음
[단어 양식](https://drive.google.com/file/d/1EwgE1AQhaQ5M6FbeNJPlFkN6gPKAYieE/view?usp=sharing)

[문장 양식](https://drive.google.com/file/d/1-SOdjcIQbtGFnOK9AoMYGnRpOJ6vwiSo/view?usp=sharing)
## 2. 도움말
### 2-1. 단어 암기
먼저 첨부된 단어 양식 파일을 내려받은 후, 텍스트 에디터(ex. 메모장)로 열어주세요. 파일 형식은 표준 `JSON` 형식을 따릅니다.

파일에 보면 다음과 같이 되어 있습니다.
```JSON
{
	"title1":
	[
		{"word": "apple", "meaning": ["사과", "애플"]},
		{"word": "banana", "meaning": ["바나나"]}
	],
	"title2":
	[
		{"word": "cat", "meaning": ["고양이"]},
		{"word": "dog", "meaning": ["개"]}
	]
}
```
여기서 `title1`, `title2`는 단원 별 이름으로, 사용자가 범위를 지정할 때 사용되며 자유롭게 변경이 가능합니다. 

그리고 ```{"word": "english", "meaning": ["한국어 뜻"]}``` 규격은 꼭 지켜 주셔야 합니다.

귀찮으면 GPT에 단어 입력하고 예시 파일을 올린 다음 그와 같은 방식으로 JSON 파일을 만들어줘 하면 잘 만들어줍니다. 


### 2-2. 문장 배열
먼저 첨부된 문장 양식 파일을 내려받은 후, 텍스트 에디터(ex. 메모장)로 열어주세요. 

파일에 보면 다음과 같이 되어 있습니다.

```plain
hi this is ion
hello nice to meet you
```

이것은 한 줄마다 문장을 입력하면 됩니다. 

문장 단어의 재배열은 무조건 알파벳 순이며, 가급적 모든 단어가 소문자로 시작하는 것을 추천합니다. (알파벳 순서를 무시하고 대문자가 제일 먼저 옵니다)