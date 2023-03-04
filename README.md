# springboot + react protect

## dependency list
> spring web
> 
> spring web service
> 
> jdbc api
> 
> postgresql
> 
> mybatis
 
## Init
### react install
> terminal
> 
> cd src/main
> 
> npx create-react-app reactfront
> 
> cd reactfront
> 
> npm start(test)
 
### proxy Init
#### 1
> src/main/reactfront/package.json
>
> script 위에 내용 추가
>
> "proxy" : "http://localhost:8080",
#### 2
> build.gradle에 추가 설정 있음.
>
> // react proxy 설정 시작 ~ // react proxy 설정 종료

## 내용 정리
### 프로젝트 구조
#### build
> 빌드 시 생성되는 디렉토리
#### node_modules
> 리엑트 실행에 필요한 모듈 디렉토리
#### public
> 정적 파일 디렉토리
#### src
> 프로젝트 source 디렉토리