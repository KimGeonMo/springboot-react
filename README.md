## springboot + react protect

### dependency list
> spring web
> 
> spring web service
> 
> jdbc api
> 
> postgresql
> 
> mybatis
 
### Init
react install
> terminal
> 
> cd src/main
> 
> npx create-react-app reactfront
> 
> cd reactfront
> 
> npm start(test)
 
proxy Init

> src/main/reactfront/package.json
>
> script 위에 내용 추가
>
> "proxy" : "http://localhost:8080",

> build.gradle에 추가 설정 있음.
>
> // react proxy 설정 시작 ~ // react proxy 설정 종료
