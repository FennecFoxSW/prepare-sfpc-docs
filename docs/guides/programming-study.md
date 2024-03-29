---
outline: [2, 3]
---

# 프로그래밍 공부 방법

이 페이지를 펼치셨다는 것은 여러분이 이제 막 프로그래밍 공부를 시작하셨거나 프로그래밍 공부를 하고 싶으시다는 의미일겁니다. 아니면 학교 정보 시간에 이미 C언어나 파이썬을 공부하고 계실 수도 있습니다. 좋습니다, 벌써 반이나 하셨네요! 여러분은 학생이지만 대학생 때 전공 수업에서, 혹은 비전공자 였다가 뒤늦게 학원이나 부트캠프 등을 통해 프로그래밍을 처음 접하는 사람들이 생각보다 많습니다. 여러분은 상대적으로 유리한 시작점과 더 많은 시간을 가지게 되는 겁니다, 스스로를 자랑스러워해도 되지 않을까요?

::: warning
이 페이지는 알고리즘, PS가 아니라 순수하게 프로그래밍 공부 방법에 대해 다룹니다. 이 페이지와 알고리즘/PS를 공부하는 방법을 다루고 있는 페이지를 같이 읽어주세요.
:::

::: danger 이 문서의 내용에만 의존하지 마세요!
이 문서의 내용도 정확하지 않을 수도 있습니다. 아래 적힌 모든 내용은 전부 정답이 아닙니다. 사실 정답이 없는 것 같습니다. 그렇기에 공부하는 입장에서 최대한 많은 자료와 책을 접해보는 것이 가장 좋습니다. 자신만의 방법, 생각 등을 확립해 나가세요.
:::

이 페이지에서는 여러분이 어떤 흐름을 가지고 공부하면 좋을지, 어떤 책이나 자료를 가지고 공부하면 좋을지 등 공부 방법을 포괄적으로 다룹니다.

## 어떤 언어를 사용해야 하나요?

갑론을박이 오갈 수 있는 질문이지만, 제 생각엔 이 질문에 대한 답은 **없습니다.** 정보 시간에 배우고 있는 언어(아마 C언어나 파이썬 둘 중 하나일겁니다.), 아무 [인기 있는 언어](https://survey.stackoverflow.co/2023/#section-most-popular-technologies-programming-scripting-and-markup-languages), 여러분이 미래에 하고 다루고 싶은 분야와 관련된 언어, 어디서 봤는데 한번 해보고 싶은 언어 뭐든 상관 없습니다.

누구는 이 질문에 C언어 혹은 C++ 혹은 자바로 시작하라고 합니다. 글쎄요, 여러분이 알고 계신 대부분의 언어는 [C-family 언어](https://en.wikipedia.org/wiki/List_of_C-family_programming_languages)라고 해서 비슷한 문법이나 형태 등을 공유합니다. 파이썬은 C-family 언어가 아니니 가장 먼저(아니면 가장 나중에) 배워야 할까요? 아뇨, 결국 본질은 똑같습니다.

프로그래밍은 문제를 코드로 해결하는 것을 말합니다. '언어'는 프로그래밍에 사용할 수 있는 여러 종류의 도구 카테고리 중 하나일 뿐이고, 'C언어'는 '언어'라는 도구 카테고리에 속한 수많은 도구 중 하나일 뿐입니다. 건축가는 기본적인 이론부터 시작해서 결국 '건축하는 방법'을 배우지 망치로 박는 방법, 도끼로 찍는 방법 뭘 배워야 하는지 고민하지 않습니다.

### ...진짜요?

그렇지만 어느 정도 틀을 알려드릴 순 있습니다. 아래 3개는 취업하는 관점에서 배워두면 좋은 언어입니다.

- C++: 가장 효율적입니다.
- 자바: 현업에서 가장 많이 사용됩니다.
- 파이썬: 입문하기 쉬운 문법을 가지고 있으며 현업에서 종종 사용됩니다.
- 자바스크립트/타입스크립트: 여러분이 웹(특히 프론트엔드)을 다루게 된다면 거의 일상처럼 다루게 될 언어입니다.

아래는 알고리즘을 공부하는 관점에서 사용되는 언어입니다.

- 코드업: C, C++, 파이썬, 자바
- SFPC: C, C++, 파이썬, 자바, 자바스크립트, R, 러스트
- 백준: C, C++, 파이썬, 자바, 루비, 코틀린(JVM), 스위프트, C#, 자바스크립트, Go, D, Rust 등

혹은 [roadmap.sh](https://roadmap.sh/)에서 각 분야별로 어떤 언어를 배워야 하는지 확인해보실 수 있습니다.

다시 말씀드리지만, 이 언어에만 국한해서 배워야 한다는 것은 절대 아닙니다. 언어는 그저 도구입니다.

::: info
그렇지만 SFPC를 나가고 싶다면 위의 언어 중 하나는 알고 계셔야겠죠. 너무 깊이는 말고, 코드업이나 백준 등에 올라와 있는 문제를 풀 수 있을 정도로 배우시면 됩니다.
:::

## 어떻게 공부해야 하나요?

이 글을 읽고 계실 거의 모든 분께 적합한 방법은 아마 '독학'일겁니다.

'학원'을 간다는 선택지도 있지만 학원은 복불복입니다. 괜찮은, 좋은 학원이 있는 반면 이상하게 가르치는 학원도 있고 가서 스트레스만 잔뜩 받아오는 학원도 있습니다. (TMI: 저는 좋은 학원 2군데와 별로인 학원 2군데를 다녀봤습니다. 결론은 독학이었습니다.)

독학을 하는 대신, 여러 개발자와 온오프라인으로 만나보는 것을 추천드리고 싶습니다. 궁금한 것이 있을 때 물어볼 수도 있고, 대화하면서 안목을 키울 수도 있습니다. 독학의 단점이 있다면 이해가 되지 않는 부분을 상상하고 넘어갈 수도 있으나 여러 개발자와 만다고 질문하다 보면 그런 부분을 확실하게 이해할 수도 있습니다.

## 어떤 책이나 자료를 통해 배워야 하나요?

::: info 자유롭게 기여해주세요!
만약 여러분이 이 부분에 추가하고 싶은 책이나 자료가 있다면 언제든지 추가해주세요! 맨 아래 `GitHub에서 이 페이지 수정하기` 버튼을 통해 이 페이지를 수정하실 수 있습니다. 수정 후 풀 리퀘스트를 남겨주세요.
:::

::: tip 자신에게 맞는 책 찾는 법
아래 있는 책이 아니더라도 서점에 가서 몇 권을 골라 읽어보면서 자신에게 가장 잘 맞는 책을 찾으시는 것을 추천드립니다. 꼭 프로그래밍 언어 입문서가 아니더라도, 컴퓨터 관련 서적에서 흥미가 있는 책이 있으면 구매해보시는 것을 추천드립니다.
:::

### C언어

#### KNK (C Programming: A Modern Approach, 2nd Edition)

- [교보문고](https://product.kyobobook.co.kr/detail/S000002500381) [yes24](https://www.yes24.com/Product/Goods/573769)

K&R과 더불어서 C언어 표준에 대해 잘 설명하고 있는, 전세계의 고수들에 의해 검증이 된 C언어의 정석적인 입문서입니다. 쉽지만 깊이 있게 쓰여있습니다. 또한, Q&A가 상당히 도움이 되는 내용들로 구성되어 있습니다.

이 책은 공식 번역서는 없지만 위키독스에 한 분이 이 책을 어느정도 번역하셨습니다.

https://wikidocs.net/book/2494

번역이 상당히 좋지만 전부 번역되어 있지는 않습니다(작성 시점 기준으로 16단원의 2번째 소단원까지 번역되어 있습니다.). 따라서 원서를 읽어보기 전에 미리 이걸로 어떤 책인지 먼저 읽어보시는 것을 추천드립니다.

#### K&R (The C Programming Language, 2nd Edition)

- [교보문고](https://product.kyobobook.co.kr/detail/S000002266874) [yes24](https://www.yes24.com/Product/Goods/234925)

제가 읽어보진 못했지만, KNK와 마찬가지로 검증된, C언어의 창시자인 데니스 리치와 브라이언 커니핸이 작성한 책입니다. 비록 ANSI C라는 매우 구버전의 C언어 표준에 맞게 쓰여있지만 C언어의 초기 철학을 알 수 있습니다.

#### C 기초 플러스 6판

- [교보문고](https://product.kyobobook.co.kr/detail/S000000559824) [yes24](https://www.yes24.com/Product/Goods/57614028)

KNK에 이어 상당히 괜찮은 입문서입니다. 이 책은 번역서가 있어 위의 KNK 혹은 K&R를 구하기 어렵거나 원서가 너무 비싸거나 한국어로 된 책을 읽고 싶다면 추천드립니다. 이 책도 C언어 표준에 대해 잘 설명하고 있으며 C11의 내용도 일부 포함하고 있습니다.

### 파이썬

#### 파이썬 자습서

- https://docs.python.org/ko/3/tutorial/index.html

파이썬에서 공식으로 제공하는 튜토리얼 문서입니다. 제 생각엔 파이썬 자습서만큼 최신 파이썬의 문법을 정확히 담고 있고, 파이썬에 대해 체계적으로 다루고 있는 자료는 없을 것 같습니다. 아래 설명한 책을 보더라도, 파이썬 자습서만큼은 꼭 읽어보시는 것을 추천드립니다. 전 처음에 파이썬에 대해 아무것도 모를 때 파이썬 자습서를 보고 파이썬을 배웠습니다.

#### 점프 투 파이썬

- [위키독스](https://wikidocs.net/book/1) [교보문고](https://product.kyobobook.co.kr/detail/S000202532365) [yes24](https://www.yes24.com/Product/Goods/119293186)

'파이썬 책 추천해주세요'라는 질문에 무조건 있는 답변과도 같은 책으로, 위키독스에 거의 모든 챕터가 무료로 공개되어 있습니다.

#### 데이터 분석을 위한 파이썬 철저 입문

- [교보문고](http://www.kyobobook.co.kr/product/detailViewKor.laf?barcode=9791158391522) [yes24](http://www.yes24.com/Product/Goods/72133792)

제가 인공지능과 관련된 동아리에서 활동할 때 받았던 책입니다. 만약 인공지능이나 데이터 과학에 관심이 있는데 파이썬을 공부해야 한다면 이 책으로 공부하시는 것도 나쁘지 않습니다. 넘파이, 판다스, 맷플롯립의 사용법과 데이터 분석 예제도 포함하고 있습니다. 이 책과 수학책이면 데이터 과학 또는 인공지능을 공부할 준비가 끝납니다.

### 자바

#### 그림으로 배우는 Java Programming Basic

- [교보문고](https://product.kyobobook.co.kr/detail/S000202671998) [yes24](https://www.yes24.com/Product/goods/119608710)

제가 공부했던 책입니다. 자바를 맨 처음 입문하기 나쁘지 않은 책이라고 생각합니다.

#### 자바의 신

- 자바의 신 Vol 1: 기초 문법편 - [교보문고](https://product.kyobobook.co.kr/detail/S000210144588) [yes24](https://www.yes24.com/Product/Goods/122886212)
- 자바의 신 Vol 2: 주요 API 응용편 - [교보문고](https://product.kyobobook.co.kr/detail/S000210144131) [yes24](https://www.yes24.com/Product/Goods/122886692)

자바의 정석과 함께 괜찮은 책이라고 평가받는 책입니다. 자바의 정석은 지루하다는 평이 있어 대신 가져왔습니다. 책 중간중간 '제임스' 아저씨가 나와서 만화로 설명해주는 부분도 있어 지루하지는 않을 것 같습니다.

## 그래서 구체적으로 '어떻게' 공부해야 하나요?

::: danger 다시 강조하지만, 정답이 아닙니다.
여러분의 공부 방법을 찾으시는 것이 가장 좋습니다. 아래 내용은 제 경험을 기반으로 합니다.
:::

위의 '독학'이라는 고작 한 단어 가지고 공부 방법에 대한 여러분의 궁금증이 해소되진 않을겁니다.

우선 위의 책이나 자료로 흐름을 먼저 잡아봅시다. 여러분은 시간이 많으므로 꾸준히 공부하시되, 보통 책 맨 앞에 있는 계획표/진도표에 따라가려는 집착은 하지 않으셔도 됩니다. 계획표/진도표를 참고하고 싶다면 먼저 그대로 해본 다음 집중력이 떨어지고 흥미가 없어질 때 책을 덮으세요. 이걸 기준으로 하루(혹은 일주일 등)에 얼만큼 공부할지 기준을 세우시면 됩니다.

일단 프로그래밍은 뭘 만들기 위해 있는 겁니다. 매 단원이 끝날 때마다, 뭔가 새롭고 신기한 것을 배울 때마다, 갑자기 영감이 떠오를 때마다, 할게 없을 때마다 무언가를 꼭 만들어보세요. 정말로 간단한 프로그램도 좋습니다. 만든 것을 주변 사람이나 멘토, 정보 선생님과 같은 분들께 자랑하셔도 좋습니다. 점점 작품의 수준이 높아지고, 여러분이 책의 마지막 페이지를 덮을 때 만들고 싶은 것이 떠오를 겁니다. 메모하고, 공부하세요.

작품을 만들어볼 때 여러분이 꼭 지켜야 하는 것이 하나 있습니다. 작품에 대한 아이디어가 떠올랐다고 바로 키보드를 잡지 마시고 종이와 펜을 잡으세요. 백지에 여러분의 작품에 대한 설계를 조금이라도 해보시기 바랍니다. 여러분의 프로그램은 어떤 구조로 이루어져 있나요? 어떤 함수가 정의되고 어디서 사용되나요? 어떤 변수가 사용되나요? 실행 흐름이 어디서 어떻게 바뀌나요? 이 모든 것의 대한 답을 종이 1장 혹은 몇 장에 여러분만의 도식으로 그려내세요. '순서도'를 알면 좋지만, 순서도와 같이 형식에 얽메일 필요는 아직 없습니다. 당장 이게 필요한가 생각하실 수도 있지만, 여러분이 더 큰 규모의 작품을 만드실 때 이러한 습관이 분명히 어떻게든 도움이 되리라 장담합니다.

프로그래밍을 공부하면서 어느 정도 실력이 쌓였다고 생각하신다면 프로그래밍의 여러 응용 분야에 대해 적어도 작동하는 작품은 만들 수 있을 만큼, 너무 깊지는 않게 공부 및 체험해보세요. 취업할 때는 한 분야에 대해 스페셜리스트가 되는 것이 좋지만, 아직 그러지 않아도 되며, 굳이 여러 분야로 진출할 수도 있는 미래의 여러분을 가두지 않아도 됩니다. 어머니 뱃속에 있을 때 확인할 수 있는 배아 줄기 세포는 거의 모든 신체 세포로 분화가 가능합니다. 이 분화 가능성을 좁히지 마세요.

알고리즘/자료구조 공부도 병행하시는 것을 추천드립니다. 왜 그래야 하는지는 해당 페이지를 참고해주세요.
