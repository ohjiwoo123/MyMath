# MyMath (System Programming 동적라이브러리 추가, DLL LIB Header)

dll 정리  

프로젝트 만들기  
c++ windows 라이브러리  

MFC 동적 연결 라이브러리 선택  
DLL형식 -> MFC확장 DLL 선택  

내용 적은 다음  
dllmain 에는  
extern "C" dllexport  
헤더에는  
extern "C" dllimport  
그다음 f5 눌러서 컴파일 하면 dll,lib 파일 나온다  
그럼 dll lib 파일 복사해서 main 프로젝트 파일에 넣고  
헤더도 넣는다. 그다음  
헤더 인클루드 하고 , #pragma  하면 된다.  
이상.  
