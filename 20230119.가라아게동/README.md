# 가라아게동 알고리즘

오늘은 가라아게동 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

남은 닭다리살이 있습니다. 가라아게동 만들어보겠습니다.
 
### Prerequisites

가라아게동 요리를 위한 기본적인 준비물입니다.

#### 가라아게동 식재료

```
닭다리살
```
```
밀가루
```
```
빵가루
```
```
갈릭 파우더
```
```
파프리카 파우더
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
```
혼쯔유
```
```
계란
```
```
황설탕
```
```
맛술
```
```
치킨스톡 분말
```
```
물
```
```
대파
```

##### 조리도구

```
돈부리팬
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
숟가락
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

튀김요리는 준비가 철저해야합니다. 정리해주세요.
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

#### 가라아게 만들기

밀가루 넣기
```
tools.mixingBowl.pour(ingredients.softFlour);
```

파프리카 파우더 넣기
```
tools.mixingBowl.pour(ingredients.paprikaPowder);
```

갈릭 파우더 넣기
```
tools.mixingBowl.pour(ingredients.galricPowder);
```

후추 넣기
```
tools.mixingBowl.pour(ingredients.pepper);
```

소금 넣기
```
tools.mixingBowl.pour(ingredients.salt);
```

섞기
```
tools.mixingBowl.mix();
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

가라아게 튀김옷 입히기
```
ingredients.chickenThigh.dip(tools.mixingBowl);
ingredients.chickenThigh.dip(tools.mixingBowl2);
ingredients.chickenThigh.dip(tools.mixingBowl3);
```

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pan.fry(ingredients.cookingOil);
```

가라아게 튀기기
```
tools.pan.fry(ingredients.karaage);
```

불 끄기
```
cooking.turnOffFire();
```

#### 가라아게동 만들기


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

계란 넣기
```
tools.pan.pour(ingredients.egg);
```

가라아게 넣기
```
tools.pan.pour(karaage);
```

끓이기
```
tools.pan.boil();
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

가라아게동 담기
```
tools.dish.plating(karaagedon);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛있게 드셨나요? 영상이 마음에 들지 않습니다. 더 좋은 영상으로 찾아오겠습니다. 정리해주세요.

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
