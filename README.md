# CNN을 활용하여 큰 이미지 속 조그만 월리를 찾기

<문제점>
1. 현저히 부족한 training dataset을 어떻게 해결할까?
2. 편향된 타겟 값을 어떻게 해결할까?

<해결방안>
1. 데이터를 무작위로 자르고 변환하여 이미지 배치를 생성
2. 각각 0과 1로 채운 class weight 사용
