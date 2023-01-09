# 간짜장밥 알고리즘

오늘은 간짜장밥 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

간짜장밥 만들어보겠습니다.
 
### Prerequisites

간짜장밥 요리를 위한 기본적인 준비물입니다.

#### 간짜장밥 식재료

```
돼지고기
```
```
양파
```
```
대파
```
```
애호박
```
```
감자
```
```
생강
```
```
식용유
```
```
춘장
```
```
후추
```
```
간마늘
```
```
치킨스톡분말
```
```
황설탕
```
```
굴소스
```

##### 조리도구

```
중화팬
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

#### 커트러리

```
숟가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

간단하지만 재료 손질이 많습니다. 정리 잘해주세요.
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

#### 춘장 볶기

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pan.pour(ingredients.cookingOil);
```

춘장 넣기
```
tools.pan.pour(ingredients.blackSoybeanPaste);
```

1분간 볶기
```
tools.pan.stirFry(1, "min");
```

불 끄기
```
cooking.turnOffFire();
```

#### 간짜장 만들기

불 켜기
```
cooking.turnOnFire();
```

춘장 볶은 기름 넣기
```
tools.pan.pour(ingredients.cookingOil);
```

돼지고기 넣기
```
tools.pan.pour(ingredients.porkMeat);
```

대파 넣기
```
tools.pan.pour(ingredients.greenOnion);
```

생강 넣기
```
tools.pan.pour(ingredients.ginger);
```

간마늘 넣기
```
tools.pan.pour(ingredients.groundGalric);
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

애호박 넣기
```
tools.pan.pour(ingredients.zucchini);
```

감자 넣기
```
tools.pan.pour(ingredients.potato);
```

볶은 춘장 넣기
```
tools.pan.pour(ingredients.stirFriedBlackSoybeanPaste);
```

치킨스톡분말 넣기
```
tools.pan.pour(ingredients.chickenStockPowder);
```

황설탕 넣기
```
tools.pan.pour(ingredients.brownSugar);
```

굴소스 넣기
```
tools.pan.pour(ingredients.oysterSauce);
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

볶기
```
tools.pan.stirFry();
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

간짜장밥 담기
```
tools.dish.plating(ganjajangRice);
```
### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

생강향이 많이 나진 않으신가요? 기름에 돼지고기 보다 먼저 생강과 대파를 넣고 볶았어야했습니다. 참고해주세요.
이제 정리하시면됩니다.

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
