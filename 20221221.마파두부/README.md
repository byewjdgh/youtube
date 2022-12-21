# 마파두부 알고리즘

오늘은 마파두부 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

두부 1+1 하더라구요. 마파두부 만들어보겠습니다.
 
### Prerequisites

마파두부 요리를 위한 기본적인 준비물입니다.

#### 식재료

```
물
```
```
부드러운 두부
```
```
마늘
```
```
식용유
```
```
생강
```
```
대파 또는 쪽파
```
```
고춧가루
```
```
두반장
```
```
굴소스
```
```
진간장
```
```
참기름
```
```
돼지고기 다짐육
```
```
계란(optional)
```
```
페퍼론치노(optional)
```
##### 조리도구

```
냄비
```
```
칼
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

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

요리전에는 깨끗하게 준비해주시고 시작해주세요.
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

요리 시작하겠습니다.

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pot.pour(ingredients.cookingOil);
```

마늘 및 생강 넣기
```
tools.pot.pour(ingredients.galric, ingredients.ginger);
```

고춧가루 넣기
```
tools.pot.pour(ingredients.redPepperPowder);
```

돼지고기 다짐육 넣기
```
tools.pot.pour(ingredients.groundPorkMeat);
```

진간장 넣기
```
tools.pot.pour(ingredients.soySauce);
```

쪽파 넣기
```
tools.pot.pour(ingredients.greenOnion);
```

두반장 및 굴소스 넣기
```
tools.pot.pour(ingredients.chiliBeanSauce, ingredients.oysterSauce);
```

두부 넣기
```
tools.pot.pour(ingredients.tofu);
```

물 넣기
```
tools.pot.pour(ingredients.water);
```

간보고 싱거우면 두반장 조금 더 넣기
```
if(!me.feel(good)){
    tools.pot.pour(ingredients.chiliBeanSauce);
}
```

참기름 넣기
```
tools.pot.pour(ingredients.sesameOil);
```

페퍼론치노 넣기(optional)
```
tools.pot.pour(ingredients.peperoncino);
```

불 끄기
```
cooking.turnOffFire();
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

생각보다 괜찮지 않나요? 완전 중국식은 산초가루 같은것이 필요합니다. 나중에 기회가 되신다면 만들어보세요.
이제 정리하겠습니다.

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
