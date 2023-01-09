# 가츠동 알고리즘

오늘은 가츠동 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

카레를 하고 남은 고기가 많습니다. 가츠동 만들어보겠습니다.
 
### Prerequisites

가츠동 요리를 위한 기본적인 준비물입니다.

#### 가츠동 식재료

```
돼지고기 등심
```
```
식용유
```
```
혼쯔유
```
```
황설탕
```
```
밀가루
```
```
계란
```
```
빵가루
```

##### 조리도구

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
집게
```
```
믹싱볼
```
```
체
```
```
바트
```
```
바트망
```

#### 커트러리

```
숟가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

튀김요리이다 보니 정리 잘해주세요.
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

#### 돈카츠 만들기

밀가루 넣기
```
tools.mixingBowl.pour(ingredients.softFlour);
```

계란 넣기
```
tools.mixingBowl2.pour(ingredients.egg);
```

계란 풀기
```
tools.mixingBowl2.mix();
```

빵가루 넣기
```
tools.mixingBowl3.pour(ingredients.breadCrumbs);
```

돈카츠 튀김옷 입히기
```
ingredients.porkSirloin.dip(tools.mixingBowl);
ingredients.porkSirloin.dip(tools.mixingBowl2);
ingredients.porkSirloin.dip(tools.mixingBowl3);
```

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pot.pour(ingredients.cookingOil);
```

돈카츠 튀기기
```
tools.pot.fry(ingredients.tonkatsu);
```

불 끄기
```
cooking.turnOffFire();
```

#### 가츠동 만들기

불 켜기
```
cooking.turnOnFire();
```

혼쯔유 넣기
```
tools.pan.pour(ingredients.tzuyu);
```

황설탕 넣기
```
tools.pan.pour(ingredients.brownSugar);
```

계란 넣기
```
tools.pan.pour(ingredients.egg);
```

10초간 뜸들이기
```
tools.pan.steam(10, "second");
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

가츠동 담기
```
tools.dish.plating(katsudon);
```
### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

짜우셨나요? 혼쯔유가 많아서 그럴겁니다. 그럴땐 물을 넣어서 끓여주시면 좋습니다. 정리잘해주세요.

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
