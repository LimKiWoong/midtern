정상동작
=======
임기웅
------



#파이어베이스 서비스의 종류 및 특징

 >   파이어베이스에는 RealtimeDatabase와 Firestore 두가지 종류가 있습니다.
 >   RealtimeDatabase는 구형 데이터베이스입니다. *(1)Push Driven을 위해서 만들어진
 >   데이터베이스다보니 검색 쿼리가 굉장히 빈약합니다. 이것을 보완하기 위해
 >   Firestore라는 새로운 데이터베이스가 만들어 졌습니다. 
 >   RealtimeDatabase를 보완하는 것이 아닌 완전히 대체하는 개념입니다.

1. *(1)Push Driven 방식의 데이터베이스는 데이터베이스의 내용이 수정될 경우 UI가 변경되는 것을 말합니다. Push Driven 방식은 RxAndroid나 RxSwift 등에서 많이 얘기하고 있습니다.