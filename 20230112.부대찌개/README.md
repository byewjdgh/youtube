# 부대찌개 알고리즘

오늘은 부대찌개 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

스팸이 집에 남아있습니다. 부대찌개 만들어보겠습니다.
 
### Prerequisites

부대찌개 요리를 위한 기본적인 준비물입니다.

#### 부대찌개 식재료

```
스팸
```
```
소세지
```
```
베이컨
```
```
베이크드빈
```
```
청양고추
```
```
양파
```
```
육수팩
```
```
김치
```
```
대파
```
```
간마늘
```
```
후추
```
```
된장
```
```
고추장
```
```
간마늘
```
```
고춧가루
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
접시
```
```
집게
```
```
국자
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

재료 준비가 많습니다. 정리 잘해주세요.
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

#### 부대찌개 만들기

불 켜기
```
cooking.turnOnFire();
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

김치 넣기
```
tools.pan.pour(ingredients.kimchi);
```

베이크드빈 넣기
```
tools.pan.pour(ingredients.bakedBean);
```

소세지 넣기
```
tools.pan.pour(ingredients.sausage);
```

베이컨 넣기
```
tools.pan.pour(ingredients.bacon);
```

스팸 넣기
```
tools.pan.pour(ingredients.spam);
```

고춧가루 넣기
```
tools.pan.pour(ingredients.redPepperPowder);
```

간마늘 넣기
```
tools.pan.pour(ingredients.groundGalric);
```

된장 넣기
```
tools.pan.pour(ingredients.soyBeanPaste);
```

고추장 넣기
```
tools.pan.pour(ingredients.redPepperPaste);
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

대파 넣기
```
tools.pan.pour(ingredients.greenOnion);
```

청양고추 넣기
```
tools.pan.pour(ingredients.cheongyangRedPepper);
```

육수 넣기
```
tools.pan.pour(ingredients.stock);
```

5분간 끓이기
```
tools.pan.boil(5, "min");
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

부대찌개 담기
```
tools.dish.plating(armyBaseStew);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛잇게 드셨나요? 다른 재료도 들어가도 되지만, 전 이정도가 좋습니다. 이제 정리해주세요.

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
