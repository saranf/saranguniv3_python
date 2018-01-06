1일차 
=======================================

ubuntu 기반으로 진행됩니다.

###파이썬 2,3의 차이 

###아나콘다의 설치 (터미널이 실행되어 있다는 전제하에)
	1.https://github.com/saranf/saranguniv3_python.git (python2.7)
	1-1.wget https://repo.continuum.io/archive/Anaconda3-4.3.1-Linux-x86_64.sh (python3)

	2.bash Anaconda2-4.3.1-Linux-x86_64.sh (python2.7)
	2-1  bash Anaconda3-4.3.0-Linux-x86_64.sh (python3)

	3.메뉴얼에 따라서 엔터를 눌러줍니다.
		Please,press ENTEr to continue 메세지 출력 후 스페이스바를 누르고 있으면 다음 화면으로 넘어감.
		
		Do you approve the license terms? [yes|no] yes 입력후 엔터
	
		"[anaconda경로]>>>"에서 엔터

		"Do you wish the installer ..PATH in your /home/ubuntu/.bashrc? [yes|no]>>>" 'yes'입력후 엔터

		설치가 다 되었다면 python눌러서 실행되는지 테스트  
		
###아나콘다 가상환경 만들기
	1.가상환경 만들기		
		conda create -n myPython python=2.7 anaconda(python2.7)
		conda create --name myPython python=3.5 aaconda(python3)
	
	2.가상환경 활성화하기
		source active myPython

	3.가상환경 해제하기
		source deactive myPython

	4.주피터 노트북 실행
		- source active myPython
		- jupyter notebook

