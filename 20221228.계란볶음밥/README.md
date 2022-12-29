# 계란볶음밥 알고리즘

오늘은 계란볶음밥 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

냉장고에 계란이 많이 남아있습니다. 계란볶음밥 만들어보겠습니다.
 
### Prerequisites

계란볶음밥 요리를 위한 기본적인 준비물입니다.

#### 계란볶음밥 식재료

```
계란
```
```
밥
```
```
대파
```
```
치킨스톡 분말
```
```
식용유
```
```
간마늘
```
```
진간장
```
```
후추
```
```
소금
```

##### 조리도구
```
볶음팬
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
믹싱볼
```
```
포크
```
```
접시
```
```
숟가락
```

#### 커트러리

```
숟가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

간단한 계란볶음밥입니다. 그래도 정리는 해주세요.
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

#### 계란밥 만들기

계란 넣기
```
tools.mixingBowl.pour(ingredients.egg);
```

계란 풀기
```
tools.mixingBowl.mix();
```

치킨스톡 분말 넣기
```
tools.mixingBowl.pour(ingredients.chickenStockPowder);
```

밥 넣기
```
tools.mixingBowl.pour(ingredients.boiledRice);
```

섞기
```
tools.mixingBowl.mix();
```

#### 계란볶음밥 만들기

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

간마늘 넣기
```
tools.pan.pour(ingredients.groundGalric);
```

계란밥 넣기
```
tools.pan.pour(ingredients.eggRice);
```

볶기
```
tools.pan.stirFry();
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

진간장 넣기
```
tools.pan.pour(ingredients.soySauce);
```

간보고 싱거우면 소금 넣기
```
if(me.feel(bland)){
    tools.pan.pour(ingredients.salt);
}
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

계란볶음밥 담기
```
tools.bowl.pour(ingredients.EggFriedRice);
```
### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

간단하지 않습니까? 같이 곁들어 먹을 국도 있었다 더 좋습니다. 정리 잘해주세요.

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
