# 소보로 알고리즘

오늘은 소보로 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

카레용 등심이 많이 남아있습니다. 소보로 만들어보겠습니다.
 
### Prerequisites

소보로 요리를 위한 기본적인 준비물입니다.

#### 소보로 식재료

```
돼지고기 다짐육
```
```
쪽파
```
```
식용유
```
```
간마늘
```
```
혼쯔유
```
```
맛술
```
```
황설탕
```
```
계란
```

##### 조리도구

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
숟가락
```
```
스패츌러
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

간단합니다. 정리를 필수입니다.
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

#### 다짐육 익히기

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pan.pour(ingredients.cookingOil);
```

돼지고기 다짐육 넣기
```
tools.pan.pour(ingredients.porkMincedMeat);
```

간마늘 넣기
```
tools.pan.pour(ingredients.groundGalric);
```

맛술 넣기
```
tools.pan.pour(ingredients.mirim);
```

혼쯔유 넣기
```
tools.pan.pour(ingredients.tzuyu);
```

황설탕 넣기
```
tools.pan.pour(ingredients.brownSugar);
```

불 끄기
```
cooking.turnOffFire();
```

#### 게란 익히기

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pan.pour(ingredients.cookingOil);
```

계란 넣기
```
tools.pan.pour(ingredients.eggs);
```

휘젓기
```
tools.pan.stir();
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

소보로 담기
```
tools.dish.plating(soboroDon);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

싱겁지 않으신가요? 돼지고기를 볶을 때 간을 쌔게 하셔야합니다. 이제 정리해주세요.

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
