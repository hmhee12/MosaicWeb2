1.Spring Starter Project 생성
	
	- name : MosaicWeb
	- type : Gradle(Buildship)
	- packaging : war 
	- group : com.hybrid
	- package : com.hybrid
	
	- boot version : 1.3.6
	- lib 선택 : web

2.형상관리 	
	
	- remote Repository 생성  (github.com) 
	- Local Repository 생성
		>> dir /A > .gitignore 
		>> notepad .gitignore 편집 
		>> git init
		>> git add * 
		>> git commit -m "first commit"
	- Local --> Remote push(최초 동기화)
		>> git remote add origin https://github.com/hmhee12/MosaicWeb.git		
	