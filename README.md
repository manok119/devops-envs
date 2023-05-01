# devops-envs
docker&amp;kubernetes install shell scripts

## OS에 맞게 설치를 해주시면 됩니다.
sh파일의 스크립트를 수동으로 하나씩 설치 하셔도 되고 터미널에서 ./{파일명}.sh 를 실행시키셔도 됩니다. 

- 본 파일들은 클라우드 컴퓨팅 자동화를 위해 최적화된 파일 입니다. 

## 순서(필요한 파일을 먼저 컴퓨팅리소스에 가지고 오는 거 잊지 마세요)
1. 파일에 실행권한 주기
```shell
chmod u+x <파일이름>
```
2. 파일 실행하기: sh 파일이므로 바로 파일명을 입력하면 실행이 됩니다.
```shell
#예
~$ ./install-minikube.sh
```
