# 소고기필라프 알고리즘

오늘은 소고기필라프 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

소고기필라프 만들어보겠습니다.
 
### Prerequisites

소고기필라프 요리를 위한 기본적인 준비물입니다.

#### 소고기필라프 식재료

```
한우 설도
```
```
식용유
```
```
마늘
```
```
파프리카
```
```
양파
```
```
소금
```
```
후추
```
```
파프리카 파우더
```
```
소불고기소스
```
```
굴소스
```
```
버터
```
```
계란
```
```
마요네즈
```
```
파르지아노 레지아노 치즈
```

##### 조리도구

```
중화팬
```
```
프라이팬
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

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

필라프는 재료준비가 반 입니다. 정리부터 해주세요.
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

#### 소고기 필라프 만들기

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pan.pour(ingredients.cookingOil);
```

마늘 넣기
```
tools.pan.pour(ingredients.galric);
```

설도 넣기
```
tools.pan.pour(ingredients.bottomRoundMeat);
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

파프리카 넣기
```
tools.pan.pour(ingredients.paprika);
```

소금 넣기
```
tools.pan.pour(ingredients.salt);
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

파프리카 파우더 넣기
```
tools.pan.pour(ingredients.paprikaPowder);
```

밥 넣기
```
tools.pan.pour(ingredients.boiledRice);
```

굴소스 넣기
```
tools.pan.pour(ingredients.oysterSauce);
```

소불고기 소스 넣기
```
tools.pan.pour(ingredients.bulgogiSauce);
```

버터 넣기
```
tools.pan.pour(ingredients.butter);
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

소고기필라프 담기
```
tools.dish.add(beefPilaf);
```

계란프라이 담기
```
tools.dish.add(friedEgg);
```

파르지아노 레지아노 뿌리기
```
tools.dish.add(ingredients.parmigianoReggianoCheese);
```

마요네즈 뿌리기
```
tools.dish.add(ingredients.mayonnaise);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛있게 드셨습니까? 굴소스와 소불고기 소스의 비율은 1.25:1 정도입니다. 이제 정리해주세요.

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
