# memo
my memo

https://blog.naver.com/PostView.naver?blogId=dreammorning&logNo=222494969974&categoryNo=44&parentCategoryNo=0&currentPage=1

1단계: CTRL-ALT-DEL을 사용하고 작업 관리자를 열도록 선택합니다.

2단계 : 작업 관리자 하단의 "자세히"를 선택하여 작업 관리자를 확장합니다.

3단계 : "파일"로 이동하여 "새 작업 실행"을 선택합니다.

4단계: "열기" 필드에 "cmd"를 입력합니다.

5단계: 다음을 붙여넣습니다(모두 굵게 표시).

reg delete HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\IrisService /f && shutdown -r -t 0

6단계 : Enter 키를 누르면 PC가 재부팅됩니다. 재부팅 후 모든 것이 정상으로 돌아와야 합니다.
