# 수육 알고리즘

오늘은 수육 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

든든한 한끼가 필요합니다.. 수육 만들어보겠습니다.
 
### Prerequisites

수육 요리를 위한 기본적인 준비물입니다.

#### 수육 식재료

```
수육용 삼겹살
```
```
대파
```
```
양파
```
```
마늘
```
```
월계수 잎
```
```
후추
```
```
치킨스톡
```
```
커피 가루
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

준비는 간단하지만 정리는 해주세요.
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

#### 수육 만들기

불 켜기
```
cooking.turnOnFire();
```

물
```
tools.pan.pour(ingredients.water);
```

대파 넣기
```
tools.pan.pour(ingredients.greenOnion);
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

마늘 넣기
```
tools.pan.pour(ingredients.galric);
```

치킨스톡 분말 넣기
```
tools.pan.pour(ingredients.chickenStockPowder);
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

월계수 잎 넣기
```
tools.pan.pour(ingredients.bayLeaves);
```

면수 넣기
```
tools.pan.pour(ingredients.cookingWater);
```

수육용 삼겹살 넣기
```
tools.pan.pour(ingredients.porkBelly);
```

커피 가루 넣기
```
tools.pan.pour(ingredients.coffeePowder);
```

40분간 삶기
```
tools.pan.boil(40, "min");
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

수육 담기
```
tools.dish.plating(boiledPork);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛은 괜찮으신가요? 같이 곁들여 먹을 알배추랑 먹으면 더 맛있습니다. 정리해주세요.

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
