# bootstrap_2 : 반응형 실습
Created with CodeSandbox

- 반응형


![image](https://user-images.githubusercontent.com/37132897/158329298-83d0883c-d419-4057-9dd8-8926e9007230.png)

- col-md-6 col-sm-6 b
- col-md-3 col-sm-6
- col-md-3 col-sm-12 b
- 이거는 처음에 md(미디엄)일때는 12개의 컬럼을, 1줄로 6(hello1) 3(hello2) 3(hello3) 으로 쓰다가, 

![image](https://user-images.githubusercontent.com/37132897/158329339-2786fc27-742c-4a8b-b70c-1f1e0268a08f.png)

- px이 줄어들어서 768이하(sm(스몰))일때는 6(hello1) 6(hello2) 으로 12컬럼(1줄), 12(hello3) 컬럼으로 1줄, 총 2줄을 차지하겠다는 소리.

![image](https://user-images.githubusercontent.com/37132897/158329382-e8ccb4bf-07b9-4e18-961e-86470185418f.png)

- px이 더 줄어서 스몰보다 낮아진, 576이하가되면 하나의 블록으로만 되는것을 알 수 있다.

- 다른 hello 4,5,6은 col-md-4 b, col-md-4 b, col-md-4 b 로 미디움사이즈일때 각각 4컬럼씩, 총 12컬럼 1줄을 차지하고,

- hello 7은 col-md-4 offset-md-4 b, hello8이 col-md-4 로 8컬럼 4컬럼, 총 12컬럼을 차지하는데, offset이 4컬럼으로 젤 앞에꺼가 안보인다.  

- Layout - Grid : 홈페이지 전체가 12개의 컬럼으로 구성되어있다는 것이 기본 개념.

- row에 12개 배정이 넘어가면, 자동으로 다음 row 에 표시가 된다.

- 제일 앞칸을 비우고싶으면, offset-md-4 를 주면 4개의 블록을 비우게 된다.

- container-fluid 하면 앞에 여백을 없애준다.


