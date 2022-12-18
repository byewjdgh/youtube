# 삼겹살 수육 알고리즘

오늘은 삼겹살 수육 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

단백질 섭취를 해야겠습니다. 삼겹살 수육 만들어 봅시다.
 
### Prerequisites

삼겹살 수육 요리를 위한 기본적인 준비물입니다.

```
냄비
```
```
물
```
```
치킨스톡
```
```
수육용 삼겹살
```
```
된장
```
```
마늘
```
```
대파
```
```
양파
```
```
월계수잎
```
```
후추
```
```
커피가루
```
```
칼
```
```
집게
```
```
젓가락
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

치킨스톡 넣기
```
tools.pot.pour(ingredients.chickenStock);
```

잡내 제거를 위한 재료 넣기
```
tools.pot.pour(ingredients);
```

된장 넣기
```
tools.pot.pour(ingredients.soybeanPaste);
```

커피 가루 넣기
```
tools.pot.pour(ingredients.coffeePowder);
```

삼겹살 넣기
```
tools.pot.pour(ingredients.porkBelly);
```

후추 넣기
```
tools.pot.pour(ingredients.pepper);
```

5분 마다 삼겹살 뒤집기
```
ingredients.porkBelly.flip(5, "min");
```

삼겹살 익었는지 확인하기
```
me.check(ingredients.porkBelly.isCooked());
```

다 익었다면 자르기
```
if(ingredients.porkBelly.isCooked()){
    ingredients.porkBelly.cut();
}
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

덜 익은 부분도 있지 않으셨나요? 괜찮습니다. 저 처럼 다시 넣고 익히면 됩니다.<br>
실패는 언제나 할 수 있습니다. 이제는 뒷정리를 해야겠죠? 기름이 매우 많으니 깨끗이 정리해주세요.

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
