# 크림 스파게티 알고리즘

오늘은 크림 스파게티 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

스파게티 면이 얼마 남지 않았습니다. 크림 스파게티 만들어보겠습니다.
 
### Prerequisites

크림 스파게티 요리를 위한 기본적인 준비물입니다.

#### 크림 스파게티 식재료

```
베이컨
```
```
양파
```
```
마늘
```
```
새송이 버섯
```
```
치킨스톡 분말
```
```
물
```
```
우유
```
```
생크림
```
```
소금
```
```
후추
```
```
식용유
```

##### 조리도구

```
냄비
```
```
팬
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
조리용 트위져
```

#### 커트러리

```
포크
```
```
숟가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

생각보다 쉬운 요리입니다. 그래도 정리는 하고 시작합시다.
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

#### 면 익히기

불 켜기
```
cooking.turnOnFire();
```

물 넣기
```
tools.pan.pour(ingredients.water);
```

치킨스톡 분말 넣기
```
tools.pan.pour(ingredients.chickenStockPowder);
```

면 넣기
```
tools.pan.pour(ingredients.spaghetti);
```

삶기(브랜드 마다 시간 다름)
```
tools.pan.boil();
```

불 끄기
```
cooking.turnOffFire();
```

#### 크림 스파게티 만들기

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pan.pour(ingredients.cookingOil);
```

베이컨 넣기
```
tools.pan.pour(ingredients.bacon);
```

마늘 넣기
```
tools.pan.pour(ingredients.galric);
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

새송이 버섯 넣기
```
tools.pan.pour(ingredients.kingOysterMushroom);
```

면수 넣기
```
tools.pan.pour(ingredients.cookingWater);
```

면 넣기
```
tools.pan.pour(ingredients.spaghetti);
```

졸이기
```
tools.pan.boilDown();
```

생크림 넣기
```
tools.pan.pour(ingredients.cream);
```

우유 넣기
```
tools.pan.pour(ingredients.milk);
```

졸이기
```
tools.pan.boilDown();
```

소금 넣기
```
tools.pan.pour(ingredients.salt);
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

크림 스파게티 담기
```
tools.dish.plating(creamSpaghetti);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛잇게 드셨나요? 크림 스파게티는 생각보다 쉽습니다. 이제 정리해주세요.

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
