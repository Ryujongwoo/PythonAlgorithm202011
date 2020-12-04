# PythonAlgorithm202011
코리아IT아카데미 2020년 11월 파이썬 Algorithm 수업 내용입니다.

쥬피터 노트북 초기화
까만 화면에서 jupyter notebook --generate-config를 실행한다.

헤더 정보 문제로 웹 사이트의 데이터를 읽어오지 못할 경우 아래와 같이 헤더 정보를 설정한 후 읽어야 한다.  
헤더 정보 사이트 => https://developers.whatismybrowser.com/useragents/explore/layout_engine_name/trident/  
Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; rv:11.0) like Gecko  

folium 지도에서 popup 속성으로 지정한 한글이 깨지면 까만창에서 아래의 코드를 실행한다.  
pip install git+https://github.com/python-visualization/branca.git@master
