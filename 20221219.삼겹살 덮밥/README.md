# 삼겹살 덮밥 알고리즘

오늘은 삼겹살 덮밥 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

삼겹살이 조금 남아 있어서 삼겹살 덮밥과 같이 먹을 된장국을 만들어 보겠습니다.
 
### Prerequisites

삼겹살 덮밥 요리를 위한 기본적인 준비물입니다.

```
냄비
```
```
물
```
```
삼겹살
```
```
된장
```
```
마늘
```
```
간마늘
```
```
쪽파
```
```
양파
```
```
청양고추
```
```
진간장
```
```
황설탕
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
```
숟가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

두가지 요리를 함깨 할것이니 잘 준비해주세요.
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

황설탕 넣기
```
tools.pot2.pour(ingredients.brownSugar);
```

물 넣기
```
tools.pot2.pour(ingredients.water);
```

된장 넣기
```
tools.pot.pour(ingredients.soybeanPaste);
```

간마늘 넣기
```
tools.pot.pour(ingredients.groundGalric);
```

쪽파 및 청양고추 넣기
```
tools.pot.pour(ingredients.greenOnion, ingredients.redPepper);
```

진간장 넣기
```
tools.pot2.pour(ingredients.soySauce);
```

마늘 넣기
```
tools.pot2.pour(ingredients.galric);
```

삼겹살 넣기
```
tools.pot3.pour(ingredients.porkbelly);
```

소스 넣기
```
tools.pot3.pour(ingredients.sauce);
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

혹시 타지 않으셨나요? 설탕이 들어간 음식을 굽게 되면 많이 타게됩니다. 그럴때는 불조절을 해주세요.
다 드셨다면 잘 정리해주세요.

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
