# 까르보나라 알고리즘

오늘은 까르보나라 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

관찰레없이 간단하게 까르보나라를 만들어보겠습니다.
 
### Prerequisites

까르보나라 요리를 위한 기본적인 준비물입니다.

#### 까르보나라 식재료

```
바질
```
```
파르지아노 레지아노 치즈
```
```
후추
```
```
노른자
```
```
스파게티니
```
```
물
```
```
치킨스톡 분말
```

##### 조리도구

```
냄비
```
```
칼
```
```
집게
```
```
접시
```
#### 커트러리

```
숟가락
```
```
포크
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

정리는 필수입니다.
```
me      = Person.getInstance().cleanMind();
cooking = Cooking.getInstance().cleanSinkAndTool();
tools   = cooking.getTool();
```

재료 준비
```
ingredients = cooking.readyIngredients();
```

### Cooking

#### 까르보나라 소스 만들기


치즈 넣기
```
tools.mixingBowl.pour(ingredients.cheese);
```

후추 넣기
```
tools.mixingBowl.pour(ingredients.pepper);
```

바질 넣기
```
tools.mixingBowl.pour(ingredients.basil);
```

노른자 넣기
```
tools.mixingBowl.pour(ingredients.eggYolk);
```

섞기
```
tools.mixingBowl.mix();
```

#### 까르보나라 만들기

물 넣기
```
tools.pot.pour(ingredients.water);
```

불 켜기
```
cooking.turnOnFire();
```

치킨스톡 넣기
```
tools.pot.pour(ingredients.chickenStock);
```

면 넣기
```
tools.pot.pour(ingredients.spaghetti);
```

다 익을때 까지 기다리기
```
while(!ingredients.spaghetti.isCooked()){
    me.wait();
}
```

간과 익힘 정도 확인
```
me.check(ingredients.spaghetti);
```

불 끄기
```
cooking.turnOffFire();
```

면 넣기
```
tools.mixingBowl.pour(ingredients.spaghetti);
```

섞기
```
tools.mixingBowl.mix();
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

잘못하면 스크램블 에그가 될 수 있습니다. 맛있게 드셨다면 정리해주세요.

```
cooking.cleanSinkAndTool();
```


## Built With

* 집 - 촬영 장소
* [유튜브](https://www.youtube.com/@wjdgh) - 업로드 사이트
* [고프로, 쇼티](https://gopro.com/ko/kr/) - 촬영장비

## Contributing

* [쩜식당](https://www.youtube.com/@wjdgh) - 구독 부탁드립니다.

## Authors

* **Jeongho Choi**
