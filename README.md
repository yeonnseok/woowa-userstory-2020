# woowa-userstory-2020

## 제목 :  내일은 면접왕 (가제)

면접 "질문"과 "답변"을 집단 지성을 통해 쌓아가며 공유하는 서비스"



## 배경

2019년 5월 통계청 자료에 의하면 취업 준비생은 71만명에 달합니다. 갈수록 늘어나는 취업난에 취준생들은 좋은 일자리를 얻기위해서 열심히 시험을 준비하고 또 면접을 준비합니다. 분야를 막론하고, "사람"을 뽑는 채용에서 빠질수 없는 부분이 바로 "면접"입니다. 
우리 사회에는 다른 지식적인 부분은 인터넷이나, 서적을 통해 정보를 습득하기가 비교적 수월하지만, 면접 공부나 준비를 원활하게 할 수 있는 서비스는 아직 존재하지 않습니다. 커뮤니티를 통해 면접 스터디를 구하거나, 인터넷에서 떠돌아다니는 면접질문을 겨우 찾아서 혼자 답변을 생각해보는 정도에 그칩니다. 
**면접을 준비하는 많은 사람들이 효과적으로 정보를 획득할 수 있도록 면접 질문을 공유하고, 좋은 답변을 함께 생각해 볼 수 있는 서비스에 대한 필요성을 느껴 "내일은 면접왕" 서비스를 구상하게 되었습니다.**



## 핵심기능

이 서비스의 핵심기능은 기업정보(면접 질문 출처)를 공개하지 않고, 누군가 보편적인 면접 질문을 올린다면, 다른 유저들이 해당 질문에 대해 자신이 생각한 모범 답안을 댓글로 작성합니다. 좋아요를 많이 받은 답안(댓글)순으로 답안(댓글)이 정렬되는 것이 기본적으로 제공되는 기능입니다. 

### 추가 기능 설명

- 태그를 기반으로 면접 질문의 카테고리를 분류할 수 있습니다.
  - 태그는 일반 기업 질문 부터 전공 질문 특히 개발자들의 실무 면접 분야까지 폭넓게 존재합니다.(특히 개발자 실무지식 답변은 공부하는데 많은 도움이 될 것이라 생각합니다.)
- 결제 기능을 추가한다면, 베스트 댓글을  열람할 수 있는 구독 서비스를 붙인다거나, 열람하는 댓글 수만큼 포인트를 차감하는 식도 생각해 볼 수 있을 것입니다. 
- 자신이 면접 답안을 작성한 만큼 혹은 작성한 댓글 중 좋아요를 받은 댓글의 수만큼 다른 사람의 답변을 확인할 수 있도록 만들거나 상호 참여를 유도할 수 있을 것이라 생각합니다.
- 면접을 무사히 마치고 취업에 성공한 사람들의 면접 지식은 대부분 그날로 소멸되는 것을 막을 수 도 있다점에서도 의미가 있다고 생각합니다.



> 여기서는 Persona와 유저 시나리오에 집중하여 서비스를 설명하겠습니다.



## 1순위 페르소나

이름 : 최치준 

나이 : 27세

직업 : 백엔드 취업준비생

특이사항 : 비전공자, 기업 면접을 앞두고 어떻게 준비를 해야할 지 막막한 상황

#### 시나리오

```markdown
백엔드 개발직군으로 취업을 희망하는 최치준은 열심히 준비했던 기업의 코딩테스트를 통과하고 면접을 앞두고 있다. 비전공자이기에 컴퓨터 사이언스 지식이 부족한 최치준은 면접 준비를 어떻게 해야할 지 막막하기만 하다. 아는 개발자 선배들도 없고, 오로지 혼자서 이 난국을 극복해야하는 상황!
대학교 커뮤니티, 개발자 커뮤니티 등을 돌아다니며 면접 스터디를 구해보려고하지만, 면접 날짜까지 얼마 안남은 상황에서 위험을 감수하기가 썩 내키지않는다. 인터넷을 검색을 통해 면접 후기, 대표 면접 질문들을 찾아보았지만, 질문을 찾는데 걸리는 시간이 만만치 않고 질문에 대한 답변도 직접 찾아 공부해야하기 때문에 면접준비가 너무 어렵고 힘들게만 느껴진다. 

이때 마침 친구의 추천으로 "내일은 면접왕" 서비스를 알게 되었다. 
최치준은 곧바로 소셜로그인을 통해 회원가입을 진행하고, 사이트를 둘러보기 시작했다.
"#IT기업" 으로 태그 검색을 하니 본인이 준비가 필요하다고 생각한 컴퓨터 사이언스 면접 기출/예상 질문목록이 나타났다. 질문 중 "추상 클래스와 인터페이스와의 차이점은?"를 클릭하니 상세보기 페이지로 이동하면서 수많은 댓글(답안)이 보였다. 

댓글들에는 좋아요 수가 표시되어있었고, 가장 좋아요를 많이 받은 댓글 순으로 보였다.
역시 가장 좋아요를 많이 받은 댓글의 답변이 제일 깔끔하고 명확했다. 블로그에 정리된 글보다 면접답변용으로 풀어 설명할 수 있도록 작성된 점이 인상적이었고, 면접준비하는 데에도 크게 도움이 되었다. 

어떤 질문은 게시된지 얼마 안되어 질문만 있고 답변은 아직 달리지 않은 것도 있었다. 최치준은 해당 질문에 답변을 정말 알고 싶었지만 본인의 실력으로는 답을 찾기가 어려웠다. 그래서 개발자 오픈 카톡방에 링크를 공유하여 답변 참여를 유도했다. 공유링크에는 자신의 아이디를 함께 보낼 수 있었다. 오픈 카톡방에서 "내일은 면접왕"서비스에 호기심이 생긴 신규 가입자들은 회원가입 할 때, 추천인 등록을 할 수 있었고 얼떨결에 추천인 등록이 된 최치준과 신규가입자는 모두 인센티브를 획득할 수 있었다.

하루종일 질문을 검색하다보니 재미도 있었고, 얻는 것도 많았지만 최치준은 어느샌가 본인이 참고할 만한 수십 개의 링크들을 자신의 카톡방에다가 url을 복사+붙여넣기하고 있었다.
하지만 "내일은 면접왕"사이트를 조금 더 자세히 살펴보니 질문 페이지를 북마크할 수 있는 기능이 있었다. 질문 링크를 외부로 공유할 수도 있었지만 내부적으로 마이페이지에 보관할 수 있는 기능도 있었던 것이었다! 이 사실을 뒤늦게 알게 된 최치준은 다시 자신이 복사한 링크들에 들어가서 북마크 표시를 남겼다. 그리고 마이페이지에 들어가보니 본인이 북마크한 질문 목록만 따로 모아서 볼 수가 있었다.

며칠 사용하며 면접 공부를 하다보니 최치준은 어느 정도 답변하는 것에 자신감이 붙었다. 
그래서 이번에는 신규 질문에 가서 자신이 생각한 모범 답안을 적어보어보고 테스트 해보기로 했다. 답안을 작성 한 지 지나지 않아 치준이의 답안에 좋아요가 많이 눌렸고, 치준이는 자신의 답안이 어느정도 괜찮다라는 객관적인 지표를 확인할 수 있어서 자신감이 상승했다.

최치준은 "내일은 면접왕" 면접 준비기간동안 서비스를 애용했고, 그 결과 자신없고 막막하기만했던 면접을 면접당일까지 차분히 잘 준비할 수 있었다. 비록 모든 면접 질문을 서비스를 통해 준비한 내용이 100% 커버할 순 없었지만 그 동안 열심히 참고한 모범 답안들과 비슷한 맥락으로 답변할 수 있었다. 

최치준은 자신이 받은 새로운 면접 질문들에 대해 다른 사람들은 어떻게 생각하는 지 궁금했다. 그래서 면접이 끝나자마자 "내일은 면접왕" 질문 사이트에 질문을 올려보았다. 다음 날 다시 사이트에 접속하여 확인해보니, 애매하다고 생각했던 자신의 답변과 다른사람들의 모범 답안들이 비슷한 맥락임을 확인하고 안심할 수 있었다.

그리고 며칠 뒤 최치준은 자신이 원하는 IT기업에 당당히 입사할 수 있게 되었다. 🤗 
- The Happy Ending -
```



## 요구사항 도출

| 시나리오                                                     | 요구사항                                                     |
| ------------------------------------------------------------ | :----------------------------------------------------------- |
| "소셜로그인을 통해 회원가입을 진행하고,~"                    | 구글, 카카오, 네이버 등의 소셜로그인을 지원한다.             |
| "`#IT기업`으로 태그 검색을 하니~"                            | 태그 기반으로 질문을 검색할 수 있어야 한다.                  |
| 댓글들에는 좋아요 수가 표시되어있었고, 가장 좋아요를 많이 받은 댓글 순으로 보였다. | - 댓글에 좋아요를 누를 수 있어야하고, 수를 표기해야한다. (비동기)<br />- 좋아요 많이 받은 순으로 댓글을 정렬한다. |
| "오픈 카톡방에 링크를 공유하여~"                             | 외부로 링크를 공유하는 API를 추가한다.                       |
| "추천인을 등록할 수 있었고~"                                 | 추천인 제도를 두어 인센티브(포인트 등)가 적용되게 한다.      |
| "질문페이지를 북마크할 수 있는 기능이 있었다."               | 질문을 북마크처리하면 마이페이지에 등록되고 북마크 목록만 따로 볼 수 있어야 한다. |



