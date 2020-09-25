문자열 배열을 선언할 때 주로 사용하는 방법인
String[] S = new String[5];
이때 각 요소들은 null로 초기화되므로 접근 시 NullpointerException이 발생함
만약 초기 값을 지정하고 싶을 때
Arrays.fill(S, ""); 을 사용한다면
배열 S의 모든 요소가 갖고있는 값은 ""이 된다.
