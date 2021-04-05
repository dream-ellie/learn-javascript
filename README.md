# 드림코딩 자바스크립트 입문편 강의 노트

## 드림코딩 아카데미

**아카데미 로드맵**: [로드맵 보러가기](https://academy.dream-coding.com/pages/912e50)

**아카데미에서 공부하기**: [아카데미 강의 보러 가기](https://academy.dream-coding.com/)

## 노트 설명

**자바스크립트 재생 리스트 영상을 보시려면 아래 링크를 클릭하세요** ↙

[자바스크립트 기초 강의 (ES5+) 영상 목록 리스트](https://www.youtube.com/playlist?list=PLv2d7VI9OotTVOL4QmPfvJWPJvkmv6h-2)

각 영상마다 어떤 파일을 쓰는지 안내해 드렸어요.
노트만 보시는것 보다는 꼭 한번은 강의를 보시고 직접 손으로 코딩해보시는걸 추천해 드려요 📒

---

## 자주 받는 질문

#### 1. 엘리의 비쥬얼 스튜디오 셋팅이 궁금해요

[비쥬얼 스튜디오 설치 & 익스텐션](https://youtu.be/bS9yTI2fC0w)

[Emmet 영상 제일 마지막에 익스텐션 하나더](https://youtu.be/m7wsrVQsVjI)

[주석 코드 색상 엘리와 똑같이 바꾸기](https://youtu.be/2UaKfAz-eEI)

#### 2. 왜 저는 모든 문자열이 다 출력 되나요?

```js
console.log('${variable}');
```

위와 같이 그냥 싱글 따옴표로 작성하시면 안되요.
Template String을 사용하기 위해서는 키보드 물결 모양에 있는 백틱 기호를 쓰셔야 해요.

```js
// '이게 아니라 `이거예요
console.log(`${variable}`);
```

#### 3. 저도 이모티콘 쓰고 싶어요!

이모지는 유니코드중 하나로 어느 운영체제에서 쓰실 수 있어요.
맥북: control + command + space
윈도우에서는 키보드 윈도우 + ; 누르면 만들수 있어요.
만약 쓰시는 운영체제에서 단축키가 없다면 여기에서 복사해서 쓰실 수 있어요 https://getemoji.com/

#### 4. VS Code에서 폰트 뭐예요?

제 VS Code 설정에 설정된 폰트는 아래와 같아요:

```
Menlo, Monaco, 'Curier New', monospace
```
