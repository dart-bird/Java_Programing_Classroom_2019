다음 MyArray 인터페이스를 상속받는 문자열 배열 StringArray 클래스를 구현하라.

interface MyArray {
   int length(); // 현재 배열에 저장된 개수 리턴
   int capacity(); // 배열의 전체 저장 가능한 개수 리턴
   String get_remove(int index); // index에 해당하는 값 반환후, 배열에서 해당 값 없애기.  
   boolean set(String val, int index); // index에 해당하는 값으로 val 저장
}

배열은 항상 빈칸이 없도록 유지되어야 한다. 
get_remove 함수는 index를 인덱스로 갖는 값을 반환하고, 그 값을 배열에서 없앤다. 
index 보다 큰 수를 인덱스로 갖는 값들을 한칸씩 앞으로 당겨야 한다. 
