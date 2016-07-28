1.Spring Starter Project 생성
	
	- >>name : MosaicWeb
	- >>type : Gradle(Buildship)
	- >>packaging : war 
	- >>group : com.hybrid
	- >>package : com.hybrid
	
	- >>boot version : 1.3.6
	- >>lib 선택 : web

2.형상관리 	
	
	- remote Repository 생성  (github.com) 
	- Local Repository 생성
		>> git status
		>> git log
		>> dir /A > .gitignore 
		>> notepad .gitignore 편집 
		>> git init
		>> git add * 
		>> git commit -m "first commit"
		
		
	- Local --> Remote push(최초 동기화)

		>> git remote add origin https://github.com/hmhee12/MosaicWeb.git	
		>> git remote - v 	

		( >> git remote remove origin - 제거  )
	
		>> git push -u origin master	
		
	-개발자 2가 Clone 수행
	
		>> git clone http://github.com/hmhee12/MosaicWeb.git
		>> git clone http://github.com/hmhee12/MosaicWeb.git MosaicWebDev
		>> Eclipse Gradle Import
		
		
3.모자익웹2 만듬 
	