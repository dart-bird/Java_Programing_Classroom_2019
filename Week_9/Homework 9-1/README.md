문자열을 str 을 입력으로 받아서, str의 길이가 20을 초과할 경우 
문자열 "More than 20 words" 을 품은 RuntimeException 을 발생시키고 
str이 null 일 경우 문자열 "null"을 품은RuntimeException 을 발생시키며 
두 경우 다 해당되지 않을경우 받은 문자열을 그대로 돌려주는 len_check 함수를 작성하라. 

출력 예시.
System.out.println(len_check("abcdefghijklmnopqrs"));
abcdefghijklmnopqrs


System.out.println(len_check("abcdefghijklmnopqrsuvw"));
Exception in thread "main" java.lang.RuntimeException: More than 20 words
	at ...

System.out.println(len_check(null));

Exception in thread "main" java.lang.RuntimeException: null
	at ...