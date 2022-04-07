# 📝 노트

❓ 뭐하는노트 인가요? 
  - 여러가지 애러들의 해결방법을 적은 코드입니다. 

***
 
🖋양식

❗️ 오류번호 
  -
 - 오류코드

📚 발생원인
  -
 - 원인

✨ 해결방법
  - 
 - 해결법

***

❗️ C4996 
  -
 - 'scanf': This function or variable may be unsafe. Consider using scanf_s instead. To disable deprecation, use _CRT_SECURE_NO_WARNINGS. See online help for details.

📚 발생원인
  -
 - Visual Stuio에 한정적으로 나타나는 오류로 scanf사용 때문에 나타나는 오류이다.

✨ 해결방법
  - 
 - 메인소스에서 우클릭후 속성클릭후 C/C++ -> 일반 SDL 검사를 "아니요"로 바꿔주면 해결된다.
