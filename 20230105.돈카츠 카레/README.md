# 돈카츠 카레 알고리즘

오늘은 돈카츠 카레 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

카레 하나면 3일은 버팁니다. 돈카츠 카레 만들어보겠습니다.
 
### Prerequisites

돈카츠 카레 요리를 위한 기본적인 준비물입니다.

#### 돈카츠 카레 식재료

```
돈까스용 등심
```
```
양파
```
```
당근
```
```
감자
```
```
물
```
```
카레 고형분
```
```
버터
```
```
페퍼론치노
```
```
케첩
```
```
밀가루 박력분
```
```
튀김가루
```
```
소금
```
```
후추
```

##### 조리도구

```
중화팬
```
```
냄비
```
```
칼
```
```
도마
```
```
접시
```
```
스패츌러
```
```
믹싱볼
```
```
체
```
```
포크
```
```
집게
```

#### 커트러리

```
숟가락
```
```
젓가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

튀김요리가 같이 있으니 잘 정리해주세요.
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

#### 카레 만들기

불 켜기
```
cooking.turnOnFire();
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

당근 넣기
```
tools.pan.pour(ingredients.carrot);
```

감자 넣기
```
tools.pan.pour(ingredients.potato);
```

야채 볶기
```
tools.pan.stirFry();
```

물 넣기
```
tools.pan.pour(ingredients.water);
```

카레 넣기
```
tools.pan.pour(ingredients.curryPowder);
```

버터 넣기
```
tools.pan.pour(ingredients.butter);
```

페퍼론치노 넣기
```
tools.pan.pour(ingredients.peperoncino);
```

케첩 넣기
```
tools.pan.pour(ingredients.ketchup);
```

졸이기
```
tools.pan.boilDown();
```

불 끄기
```
cooking.turnOffFire();
```

#### 튀김 반죽 만들기

밀가루 넣기
```
tools.mixingBowl.pour(ingredients.softFlour);
```

튀김가루 넣기
```
tools.mixingBowl.pour(ingredients.fryingFlour);
```

물 넣기
```
tools.mixingBowl.pour(ingredients.water);
```

섞기
```
tools.mixingBowl.mix();
```

#### 돈카츠 만들기

불 켜기
```
cooking.turnOnFire();
```

반죽에 등심 넣기
```
fryBatter.coat(ingredients.porkSirloin);
```

3분간 튀기기 
```
tools.pan.deepFry(3, "min");
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

돈카츠 카레 담기
```
tools.dish.plating(tonkatsuCurry);
```
### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

돈카츠에 물반죽은 저의 노하우 부족인지 어렵더군요. 그래도 물반죽을 익혔으니 다음엔 텐동을 만들어보겠습니다.
이제 정리해주세요.

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
