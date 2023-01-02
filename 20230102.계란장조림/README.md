# 계란장조림 알고리즘

오늘은 계란장조림 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

냉장고에 꽈리고추와 계란이 많이 남아있습니다. 계란장조림 만들어보겠습니다.
 
### Prerequisites

계란장조림 요리를 위한 기본적인 준비물입니다.

#### 계란장조림 식재료

```
계란
```
```
소금
```
```
식초
```
```
진간장
```
```
꽈리고추
```
```
물
```
```
황설탕
```
```
마늘
```
```
표고버섯
```
```
꿀
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
숟가락
```
```
포크
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

조리도구를 매우 많이 사용합니다. 정리를 잘해주세요.
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

#### 계란 삶기

물 넣기
```
tools.pot.pour(ingredients.butter);
```

불 켜기
```
cooking.turnOnFire();
```

소금 넣기
```
tools.pot.pour(ingredients.salt);
```

식초 넣기
```
tools.pot.pour(ingredients.vinegar);
```

계란 넣기
```
tools.pot.pour(ingredients.egg);
```

7분간 삶기
```
tools.pot.boil(ingredients.egg, 7, "min");
```

불 끄기
```
cooking.turnOffFire();
```

#### 계란 장조림 만들기

물 넣기
```
tools.pot.pour(ingredients.butter);
```

불 켜기
```
cooking.turnOnFire();
```

진간장 넣기
```
tools.pot.pour(ingredients.soySauce);
```

황설탕 넣기
```
tools.pot.pour(ingredients.brownSugar);
```

표고버섯 넣기
```
tools.pot.pour(ingredients.shiitakeMushroom);
```

삶은계란 넣기
```
tools.pot.pour(ingredients.boiledEgg);
```

마늘 넣기
```
tools.pot.pour(ingredients.galric);
```

꽈리고추 넣기
```
tools.pot.pour(ingredients.shishitoPeppers);
```

졸이기
```
tools.pot.boilDown();
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

계란장조림 담기
```
tools.dish.plating(soySauceBraisedEgg);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

오랜만에 힘든 요리를 했습니다. 잘따라하셨나요? 실패해도 괜찮습니다. 다음에 또 하시면 되니까요.
정리 잘해주세요.

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
