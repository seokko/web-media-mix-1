# web-media-mix metadata 개발
웹툰, 웹소설, 웹드라마 등 웹 기반 컨텐츠의 시장이 전세계적으로 증가하고 있다. 그럼에도 불구하고, 이들을 효과적으로 검색/질의/구독하기 위한 정보 데이터 모델은 부재하다. 물론, 각각의 컨텐츠를 위한 정보모델은 기존에도 존재하였다, 예를들면, Comic Book ontology는 만화책을 위한 정보모델을 제공한다. 하지만, 기존의 컨텐츠들이 다른 영역으로 활발하게 재창조되면서 그들의 관계 및 필요한 속성에 대한 정보는 공유/개방가능한 형태로 모델링 되지 않았다. 예로, 드라마의 웹툰화는 드라마의 기본적인 스토리와 관련된 요소(인물, 배경)을 따르지만, 웹툰의 제약적인 조건(프레임, 말풍선 등) 따를 것을요구한다.

# 미디어 믹스란?
웹툰을 포함한 웹 드라마, 웹소설 등 웹에서 일어나는 문화적인 컨텐츠 모두를 일컫는 용어. 미디어 믹스 메타데이터는 웹툰, 웹드라마, 웹소설 등의 인스턴스 뿐만아니라 개념적인 관계등을 구성하고자 함.

# 현재 단계 및 향후 방향
웹툰 미디어 믹스의 대략적인 구조 설계가 되어있으나, 이것은 어떠한 특정 프로그래밍 언어로 표현되지 않았기 때문에 프로그램적으로 사용하기가 어려움. 주어진 자료를 Human- and machine- readable 하며 공유가능한 포맷으로 변환하는 작업을 수행. 
메타데이터 그래프 옆에 요약된 표도 같이 만들어두기

# 사용 도구
RDFLib을 사용하여 개념/인스턴스/관계를 모델링하고, networkx/graphviz 등을 이용하여 모델된 데이터를 시각화한다.
rdflib (https://github.com/RDFLib)
networkx (https://github.com/networkx/networkx)
graphviz (https://gitlab.com/graphviz/graphviz)

# 참고
현재 아이디어은 성소정, 최소원로부터 시작되었습니다.

미디어믹스를 활용한 웹툰 캐릭터 마케팅 (https://www.koreascience.or.kr/article/JAKO201029848353485.pdf)
