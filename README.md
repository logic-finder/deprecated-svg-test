## SVG 성능 테스트
이 테스트는 아래 중 어느 것이 더욱 빠른지를 시험하기 위함입니다.
- (1) svg 요소 내에서 5000개의 rect 요소를 setAttribute(x)를 사용하여 제어
- (2) svg 요소 내에서 5000개의 rect 요소를 translate(x)를 사용하여 제어
- (3) div 요소 내에서 rect 요소를 포함하고 있는 svg 요소 5000개를 style.left를 사용하여 제어

결과: (1) > (2) > (3)

## SVG Performance Test
This test is for checking which one of the below is faster.
- (1) in a svg element, controlling 5000 rect elements using setAttribute(x)
- (2) in a svg element, controlling 5000 rect elements using translate(x)
- (3) in a div element, controlling 5000 svg elements containing a rect element using style.left

Result: (1) > (2) > (3)