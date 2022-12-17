# 된장찌개 알고리즘

오늘은 된장찌개 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

아는 맛이 젤 무섭습니다. 맛있는 된장찌개를 만들어봅시다.
 
### Prerequisites

된장찌개 요리를 위한 기본적인 준비물입니다.

```
냄비
```
```
물
```
```
말린 표고버섯(optional)
```
```
부드러운 찌개 두부
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
육수팩
```
```
대파
```
```
양파
```
```
청양고추
```
```
숟가락
```
```
젓가락
```
```
계란(optional)
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

요리는 기본에 충실해야합니다. 씽크대 및 도구들을 정리해주세요.
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

모든 변수가 초기화 되었으니 요리를 시작하시면됩니다.

불 켜기
```
cooking.turnOnFire();
```

육수팩 넣기
```
tools.pot.pour(ingredients.stockPack);
```

말린표고버섯 넣기(optional)
```
tools.pot.pour(ingredients.dryShiitake);
```

5분뒤 육수팩 건져내기
```
tool.pot.remove(ingredients.stockPack, 5, "min");
```

표고 버섯 자르기
```
ingredients.dryShiitake.cut();
```

고추장 넣기
```
tools.pot.pour(ingredients.redPepperPaste);
```

된장 넣기
```
tools.pot.pour(ingredients.soybeanPaste);
```

간마늘 넣기
```
tools.pot.pour(ingredients.groundGalric);
```

간보고 싱겁다면 된장 더 넣기
```
if(!me.feel(salty)){
    tools.pot.pour(ingredients.soybeanPaste);
}
```

대파와 양파 넣기
```
tools.pot.pour(ingredients.greenOnion, ingredients.onion);
```

청양고추 넣기
```
tools.pot.pour(ingredients.redPepper);
```

두부 넣기
```
tools.pot.pour(ingredients.tofu);
```

간보고 싱겁다면 된장 더 넣기
```
if(!me.feel(salty)){
    tools.pot.pour(ingredients.soybeanPaste);
}
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

든든하신가요? 맛있게 드셨다면 바로바로 치웁시다!

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
