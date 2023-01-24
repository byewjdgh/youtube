# 순두부 된장찌개 알고리즘

오늘은 순두부 된장찌개 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

혈육이 순두부 된장찌개를 먹고싶어합니다. 할 줄 모르니 순두부 된장찌개 만들어보겠습니다.
 
### Prerequisites

순두부 된장찌개 요리를 위한 기본적인 준비물입니다.

#### 순두부 된장찌개 식재료

```
돼지고기 다짐육
```
```
바지락
```
```
된장
```
```
고추장
```
```
국간장
```
```
진간장
```
```
후추
```
```
식용유
```
```
대파
```
```
간마늘
```
```
고춧가루
```
```
양파
```
```
청양고추
```
```
황설탕
```
```
소금
```
```
물
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
숟가락
```
```
믹싱볼
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

재료준비가 많습니다. 잘 정리해주세요.
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

#### 바지락 해감하기

바지락 넣기
```
tools.mixingBowl.pour(ingredients.manilaClam);
```

물 넣기
```
tools.mixingBowl.pour(ingredients.water);
```

소금 넣기
```
tools.mixingBowl.pour(ingredients.salt);
```

#### 순두부 된장찌개 만들기


불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pan.pour(ingredients.cookingOil);
```

대파 넣기
```
tools.pan.pour(ingredients.greenOnion);
```

돼지고기 다짐육 넣기
```
tools.pan.pour(ingredients.porkMincedMeat);
```

된장 넣기
```
tools.pan.pour(ingredients.soyBeanPaste);
```

간마늘 넣기
```
tools.pan.pour(ingredients.groundGalric);
```

진간장 넣기
```
tools.pan.pour(ingredients.soySauce);
```

고춧가루 넣기
```
tools.pan.pour(ingredients.redPepperPowder);
```

물 넣기
```
tools.pan.pour(ingredients.water);
```

고추장 넣기
```
tools.pan.pour(ingredients.redPepperPaste);
```

바지락 넣기
```
tools.pan.pour(ingredients.manilaClam);
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

순두부 넣기
```
tools.pan.pour(ingredients.softTofu);
```

황설탕 넣기
```
tools.pan.pour(ingredients.brownSugar);
```

국간장 넣기
```
tools.pan.pour(ingredients.soupSoySauce);
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

청양고추 넣기
```
tools.pan.pour(ingredients.cheongyangPepper);
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

순두부 된장찌개 담기
```
tools.dish.plating(soybeanPasteSoup);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛있게 드셨나요? 원래는 순두부찌개를 하려 했으나 제가 순두부찌개를 해본적이 없습니다. 다음에 기회가 된다면 만들어보겠습니다.
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
