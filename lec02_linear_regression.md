# Linear Regression
 regression model을 학습 시키면서, model이 linear한 경우에 사용
 data에 맞는 linear한 선을 결정하는 방식
 
## hypothesis (가설)
 어떤 식이 가장 좋은 값인지 확인
 > ![equation](http://latex.codecogs.com/gif.latex?H%28x%29%20%3D%20Wx%20&plus;%20b)
 
## cost function
 가설과 실제 data가 얼마나 다른지 확인
 > ![equation](http://latex.codecogs.com/gif.latex?%28H%28x%29%20-%20y%29%5E2)

 실제 data값과 가설 값의 차이(cost)를 통해 cost가 가장 적은 가설로 수정 할 수 있다.
 > ![equation](http://latex.codecogs.com/gif.latex?cost%28W%2C%20b%29%20%3D%20%5Cfrac%7B1%7D%7Bm%7D%5Csum_%7Bi%3D1%7D%5E%7Bm%7D%28H%28x%5Ei%29%20-%20y%5Ei%29%5E2)
 
 
 cost function을 가장 작게 하는 W, b를 구하는 것이 학습의 목표
