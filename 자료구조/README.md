# 자료구조

## 스택
* LIFO(Last in first out) 마지막에 삽입된 원소가 먼저 삭제됨  
* push 
* pop

## 큐
* FIFO(First in first out) 먼저 삽입된 원소가 먼저 삭제됨
* front에서 삽입 rear에서 삭제
* add
* delete
* ArrayQueue의 문제점 - 삽입시 rear증가 삭제시 front 증가 -> queue가 full이 될 경우 전체를 이동하여 front/rear를 조정해야 함 -> 원형큐사용

### 원형큐
* front가 맨앞 rear가 맨 뒤
* % (Modular)연산을 이용   
rear=(rear+1)% Max_size  
front=(front+1)% Max_size
* front가 있는자리는 비워두고 front=rear라면 empty rear+1=front라면 full

## 트리

## 그래프