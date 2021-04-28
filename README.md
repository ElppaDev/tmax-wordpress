# HyperCloud에서 wordpress 설치를 위한 기본 yaml 양식

본 문서에는 아래의 yaml들의 기본 양식이 있습니다.
아래의 순서는 실제로 Wordpress 설치를 위해 진행하는 순서입니다.

1.mysql-service.yaml : 3306 포트로 통신을 위한 mysql의 서비스를 생성합니다
2.mysql-pvc.yaml : mysql이 사용할 볼륨을 생성합니다
3.mysql-deployment.yaml : mysql 컨테이너를 띄울 디플로이먼트를 생성합니다
4.wordpress-service.yaml : 클러스터 외부에서 wordpress에 접속이 가능하도록 서비스를 생성합니다.
5.wordpress-pvc.yaml : wordpress가 사용할 볼륨을 생성합니다
6.wordpress-deployment.yaml : wordpress 컨테이너를 띄울 디플로이먼트를 생성합니다
