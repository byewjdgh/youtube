# 오리불고기 알고리즘

오늘은 오리불고기 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

냉장고에 야채들을 정리해야겠습니다. 오리불고기 만들어보겠습니다.
 
### Prerequisites

오리불고기 요리를 위한 기본적인 준비물입니다.

#### 오리불고기 식재료

```
오리고기
```
```
마늘
```
```
고춧가루
```
```
후추
```
```
황설탕
```
```
진간장
```
```
꿀
```
```
고추장
```
```
된장
```
```
양파
```
```
깻잎
```
```
양배추
```
```
청양고추
```
```
꺠
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
집게
```
```
믹싱볼
```
```
숟가락
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

정리를 하고 요리 해주세요.
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

#### 오리고기 양념 만들기


오리고기 넣기
```
tools.mixingBowl.pour(ingredients.duckMeat);
```

마늘 넣기
```
tools.mixingBowl.pour(ingredients.galric);
```

고춧가루 넣기
```
tools.mixingBowl.pour(ingredients.redPepperPowder);
```

후추 넣기
```
tools.mixingBowl.pour(ingredients.pepper);
```

황설탕 넣기
```
tools.mixingBowl.pour(ingredients.brownSugar);
```

진간장 넣기
```
tools.mixingBowl.pour(ingredients.soySauce);
```

꿀 넣기
```
tools.mixingBowl.pour(ingredients.honey);
```

고추장 넣기
```
tools.mixingBowl.pour(ingredients.redPepperPaste);
```

된장 넣기
```
tools.mixingBowl.pour(ingredients.soyBeanPaste);
```

버무리기
```
tools.mixingBowl.mix();
```

#### 오리불고기 만들기

불 켜기
```
cooking.turnOnFire();
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

양배추 넣기
```
tools.pan.pour(ingredients.cabbage);
```

양념된 오리고기 넣기
```
tools.pan.pour(ingredients.seasonedDuckMeat);
```

볶기
```
tools.pan.stirFry();
```

꺳잎 넣기
```
tools.pan.pour(ingredients.perillaLeaf);
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

오리불고기 담기
```
tools.dish.plating(duckBulgogi);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

영상에선 팽이버섯을 넣었는데 추천드리지 않습니다. 이제 정리해주세요.

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
