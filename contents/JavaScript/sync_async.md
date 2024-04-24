# 📚 동기 & 비동기 그리고 블로킹 & 논블로킹


## 📖 동기 & 비동기
### 📍 동기
- 모든걸 다 호출할때까지 다른걸 처리하지 않는 것, 직렬적인 일 처리
- 

### 📍 비동기
- 요청한 작업에 대해 완료 여부를 따지지 않고 다음 작업을 수행 가능
- 요청이 들어간 순서대로 실행되는 것이 아니라, 작업순서가 지켜지지 않을 수 있음

</br>

## 📖 블로킹 & 논블로킹
### 📍 블로킹
- 직렬 수행, 파일을 다 읽을때까지 작업의 흐름을 막음
- 제어권을 넘겨 받으면 이전의 함수는 실행을 멈추고 호출된 함수가 실행

</br> 

### 📍 논블로킹
- 병렬 수행, 파일을 다 읽지 않아도 다른 작업 가능
- 제어권은 이전 함수에 그대로 두고 호출된 함수를 실행만 시킴


### 📍 비동기 & 논블로킹
- 대표적인 비동기이면서 논블로킹 함수인 setTimeout()
- setTimeout 함수는 콜백함수를 바로 실행하지 않고 호출 스택이 아닌 테스크 큐에 추가


</br> 

