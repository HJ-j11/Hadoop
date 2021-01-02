# Hadoop
hadoop, kafka, spark

환경설정 준비
--
- virtual box 설치
 새로운 가상머신 만들어서 ubuntu 서버 띄우기
 - openjdk-11-jdk 설치
 $ sudo apt update
 $ sudo apt install openjdk-11-jdk
 
 - .bashrc 파일에 환경변수 설정하기
  export JAVA_HOME = /usr/lib/jvm/java-11-openjdk-amd64
  export PATH = $JAVA_HOME/bin
  export CLASSPATH = $JAVA_HOME/lib/*:.
  
 -  ctrl+X추가 한 후 exit (ctrl+O)
  $source .bashrc로 반영
 
 - 반영
  $echo [환경변수 이름]으로 확인
 
