#32
좋아하는 숫자 10개를 5개씩 나눠 두 개의 set 생성
두 set의 합집합
교집합 출력

#33
위와 동일하게 두 개의 set 생성
차집합
대칭차집합 출력

#34
좋아하는 숫자 5개로 set 생성
update method 사용해서 각 숫자에 100을 더한 값으로 업데이트 후 출력

#35
a = {100, 200, 300, 400, 500}
b = {400, 500, 600, 700, 800}
intersection_update method
difference_update method
symmetric_difference_update method
수행 후 결과 확인

#36
두 set이 있을 때
a가 b의 상위집합 → “상위”
a가 b의 부분집합 → “부분”
둘 다 해당 → “동시” 출력

#37
좋아하는 숫자 5개로 set 생성
add(1000)으로 값 추가
마지막 값 하나 삭제 후 출력

#38
1~100 사이에서
3과 5의 공배수만 set comprehension으로 생성
multiples = {x for x in range(1, 101) if x % 3 == 0 and x % 5 == 0}
print(multiples)
결과 {75, 45, 15, 90, 60, 30}
