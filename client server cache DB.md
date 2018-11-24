# 클라이언트, 서버, 캐시, DB 정리

  * 클라이언트 서버 정리
  ![alt text](https://postfiles.pstatic.net/MjAxODExMjRfMTQ4/MDAxNTQzMDYwMDgzODM5.KGJOWSrvkKiSbpiFxA4CEnvHSIL4ORRJfaCqRxTvtUIg.4heuhE9TOKkBep_37uri3hbgFWBVN1uK9fajPnd8hQIg.JPEG.iju1633/%EA%B0%9C%EC%9D%B8%EA%B3%BC%EC%A0%9C2.jpg?type=w773)
  
  * 캐시, DB 정리
  ![alt text](https://postfiles.pstatic.net/MjAxODExMjRfMjYy/MDAxNTQzMDYwMDgzNjgx.Hz9xSQgmESxGZH6gJHcn0MqXloD6cvOllb8GraoUPrsg.OGVcIKPeXu6CNZVDNIRAcQhgwiU8bmWmj6zs6HnShfwg.JPEG.iju1633/%EA%B0%9C%EC%9D%B8%EA%B3%BC%EC%A0%9C1.jpg?type=w773)
  
  * 선택한 클라이언트 : 하이브리드(Hybrid) 클라이언트
    * 이유
      * 본인에게 가장 익숙한 visual studio와 Java 사용가능
      * 펫 클라이언트와 씬 클라이언트의 장점을 고루 이용할 수 있음
      
  * 선택한 서버 : 리슨(Listen) 서버(게임 서버)
    * 이유
       * 다수의 사용자가 즐길 수 있여야 하는 게임
       * 별도의 고성능 네트워크 상에 있는 전용 컴퓨터에서 실행되면 한계가 있기 때문
       
  * 선택한 캐시 : CPU 캐시
    * 이유
      * 대용량의 메인 메모리 접근을 빠르게 하는 것이 가능
        * 만들고자하는 게임에서는 많은 NPC가 존재함
        * CPU 내에는 많게는 5개에서 6개까지의 서로 다른 기능을 가진 CPU캐시가 존재
      * 하드웨어를 통해 관리할 수 있다는 이점이 있음
      
  * 선택한 DB : RDB의 Maria DB
    * 이유
      * MySQL의 대체재이며 호환이 거의 완벽하게 가능하다
        * 오라클이 오픈 소스에 호의적이지 않음
      * 게임 속 다양한 이벤트와 원격 connection이 가능
