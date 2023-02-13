# 돼지 김치찌개 알고리즘

오늘은 돼지 김치찌개 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

엄마의 김치가 맛있게 익었습니다. 돼지 김치찌개 만들어보겠습니다.
 
### Prerequisites

돼지 김치찌개 요리를 위한 기본적인 준비물입니다.

#### 돼지 김치찌개 식재료

```
돼지 목살
```
```
간마늘
```
```
청양고추
```
```
생강
```
```
대파
```
```
식용유
```
```
육수팩
```
```
김치
```
```
두부
```
```
참치액
```
```
후추
```
```
물
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
스패츌러
```
```
접시
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

한식은 준비가 많습니다. 정리해주세요.
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

#### 육수 만들기

불 켜기
```
cooking.turnOnFire();
```

물 넣기
```
tools.pot.pour(ingredients.water);
```

육수팩 넣기
```
tools.pot.pour(ingredients.stockPack);
```

5분간 끓이기
```
tools.pot.boil(5, "min");
```

불 끄기
```
cooking.turnOffFire();
```

#### 돼지 김치찌개 만들기

불 켜기
```
cooking.turnOnFire();
```

식용유
```
tools.pan.pour(ingredients.cookingOil);
```

돼지 목살 넣기
```
tools.pan.pour(ingredients.porkShoulderMeat);
```

간마늘 넣기
```
tools.pan.pour(ingredients.groundGalric);
```

생강 넣기
```
tools.pan.pour(ingredients.ginger);
```

대파 넣기
```
tools.pan.pour(ingredients.greenOnion);
```

김치 넣기
```
tools.pan.pour(ingredients.kimchi);
```

육수 넣기
```
tools.pan.pour(stock);
```

두부 넣기
```
tools.pan.pour(ingredients.tofu);
```

참치액 넣기
```
tools.pan.pour(ingredients.tunaSauce);
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

청양고추 넣기
```
tools.pan.pour(ingredients.cheongyangRedPepper);
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

돼지 김치찌개 담기
```
tools.dish.plating(kimchiStew);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛있습니다. 역시 엄마의 김치는 엄청납니다. 이제 정리해주세요.

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
