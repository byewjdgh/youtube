# 소불고기 알고리즘

오늘은 소불고기 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

소불고기가 먹고 싶어졌습니다. 소불고기 만들어보겠습니다.
 
### Prerequisites

소불고기 요리를 위한 기본적인 준비물입니다.

#### 소불고기 식재료

```
불고기용 소고기
```
```
참기름
```
```
후추
```
```
진간장
```
```
국간장
```
```
간마늘
```
```
갈아만든 배 사이다
```
```
새송이버섯
```
```
팽이버섯
```
```
대파
```
```
청양고추
```
```
통깨
```

##### 조리도구
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
장갑
```
```
믹싱볼
```

#### 커트러리

```
젓가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

간단한 요리지만 정리는 해주세요.
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

#### 소불고기 양념 만들기

불고기용 소고기 넣기
```
tools.mixingBowl.pour(ingredients.ribeye);
```

진간장 넣기
```
tools.mixingBowl.pour(ingredients.soySauce);
```

국간장 넣기
```
tools.mixingBowl.pour(ingredients.soupSoySauce);
```

갈아만든 배 사이다 넣기
```
tools.mixingBowl.pour(ingredients.sprite);
```

후추 넣기
```
tools.mixingBowl.pour(ingredients.pepper);
```

간마늘 넣기
```
tools.mixingBowl.pour(ingredients.groundGalric);
```

간마늘 넣기
```
tools.mixingBowl.pour(ingredients.sesameOil);
```

섞기
```
tools.mixingBowl.mix();
```

#### 소불고기 만들기

불 켜기
```
cooking.turnOnFire();
```

소불고기 넣기
```
tools.pot.pour(ingredients.bulgogi);
```

양파 넣기
```
tools.pot.pour(ingredients.onion);
```

팽이버섯 넣기
```
tools.pot.pour(ingredients.enokMushroom);
```

새송이버섯 넣기
```
tools.pot.pour(ingredients.kingOysterMushroom);
```

대파 넣기
```
tools.pot.pour(ingredients.greenOnion);
```

청양고추 넣기
```
tools.pot.pour(ingredients.cheongyangRedPepper);
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

소불고기 담기
```
tools.dish.plating(soySauceBraisedEgg);
```

통깨 뿌리기
```
tools.dish.plating(sesameSeeds);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛있게 드셨나요? 정리해주세요.

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
