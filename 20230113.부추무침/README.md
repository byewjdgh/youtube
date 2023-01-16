# 부추무침 알고리즘

오늘은 부추무침 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

부추무침 만들어보겠습니다.
 
### Prerequisites

부추무침 요리를 위한 기본적인 준비물입니다.

#### 부추무침 식재료

```
부추
```
```
양파
```
```
고춧가루
```
```
진간장
```
```
국간장
```
```
참기름
```
```
간마늘
```
```
통깨
```
```
식초
```

##### 조리도구

```
믹싱볼
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

#### 커트러리

```
젓가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

간단하지만 정리는 해주세요.
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

#### 부추무침 만들기


부추 넣기
```
tools.mixingBowl.pour(ingredients.chive);
```

양파 넣기
```
tools.mixingBowl.pour(ingredients.onion);
```

고춧가루 넣기
```
tools.mixingBowl.pour(ingredients.redPepperPowder);
```

간마늘 넣기
```
tools.mixingBowl.pour(ingredients.groundGalric);
```

진간장 넣기
```
tools.mixingBowl.pour(ingredients.soySauce);
```

국간장 넣기
```
tools.mixingBowl.pour(ingredients.soupSoySauce);
```

참기름 넣기
```
tools.mixingBowl.pour(ingredients.sesameOil);
```

꺠 넣기
```
tools.mixingBowl.pour(ingredients.sesami);
```

식초 넣기
```
tools.mixingBowl.pour(ingredients.vinegar);
```

섞기
```
tools.mixingBowl.mix();
```

### Plating

부추무침 담기
```
tools.dish.plating(chiveMixWithSeasoning);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛있게 드셨다면 정리해주세요.

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
