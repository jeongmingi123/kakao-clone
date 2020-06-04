#### html 이론

- meta 태그

1. meta 태그는 브라우저의 설명글을 말한다.
   ex) <meta name="description" content="Welcome to my Kakao Clone" />

- semantic, non-semantic이란?

1. semantic은 뜻, 의미가 있는 태그를 말한다
   ex) <h1>, <h2> 와 같은 태그를 말한다.

2. non-semantic는 뜻이 없는 태그를 말한다.
   ex) <div>, <span> 와 같은 태그를 말한다. 섹션을 의미한다.

- <div>는 박스와 같은 태그, 박스안에 내용물을 넣을 때 사용한다.
- <span> 텍스트를 위한 컨테이너이며, <p> or <title>와 같은 경우는 아니다.

- ID, Class란 무엇인가?

1. ID란?

- 쉽게 얘기하자면 여권번호와 같다. 즉, 자기만의 고유한 번호라고 생각하면 된다.
- 고유한 element를 사용할 때 ID를 적용한다.
  ex) header 또는 nav 같은 곳에 주로 사용되어진다.

2. Class란?

- 쉽게 얘기하자면 국적과 같다. 여러개 존재할 수 있으며, 동일한 속성의 Class를 가질 수 있다.
- 고유하지 않은 반복되는 element의 경우 class를 사용한다.
  ex)

#### CSS 이론

- ID, Class, 태그 css 사용 방법

1. ID

- ID 이름을 이용하여 CSS 사용 방법은 앞에 #을 이용한다.
  ex) ID 이름을 abcd라고 가정한다면 다음과 같다.

#abcd {

property-name: value;
property-name: value;

}

2. Class

- Clsss 이름을 이용하여 CSS 사용 방법은 앞에 .을 이용한다.
  ex) Class 이름을 aba라고 가정한다면 다음과 같다.

.aba {

property-name: value;
property-name: value;

}

3. 태그

- 태그를 이용하여 CSS 사용 방법은

h1 {

property-name: value;
property-name: value;

}

4. 태그 + (Class or ID)를 합쳐서 사용 방법

- 밑의 예시와 같이 사용하면 된다.
  ex)

- h1. name{

  property-name: value;

}

- html 파일안에 css 적용 방법

1. html 파일 안에 css 적용 방법 예시

- html 파일 안에 css 적용하는 방법은 다음과 같다.

<style>

   body {
   
      property-name: value;
      property-name: value;

   }

</style>

- Block, inline Block의 차이

1. Block

- 그냥 Block은 <div> 블록이 2개 있다고 가정하면, 옆에 가로로 2개가 있을 수 없다. 블록이 세로형태로 있음.

2. inline Block

- inline Block은 CSS인데, display: inline; 와 같이 설정해주면 가로로 블록이 2개 설정가능
