# 김치볶음밥 알고리즘

오늘은 김치볶음밥 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

엄마가 김치주고 갔습니다. 김치볶음밥 만들어봅시다.
 
### Prerequisites

김치볶음밥 요리를 위한 기본적인 준비물입니다.

```
냄비
```
```
돼지 앞다리살
```
```
김치
```
```
된장
```
```
간마늘
```
```
쪽파
```
```
진간장
```
```
황설탕
```
```
식용유
```
```
참기름
```
```
후추
```
```
밥
```
```
칼
```
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

앞다리살 넣기
```
tools.pot.pour(ingredients.picnicShoulder);
```

간마늘 넣기
```
tools.pot.pour(ingredients.groundGalric);
```

된장 넣기
```
tools.pot.pour(ingredients.soybeanPaste);
```

김치 넣기
```
tools.pot.pour(ingredients.kimchi);
```

황설탕 넣기
```
tools.pot.pour(ingredients.brownSugar);
```

후추 넣기
```
tools.pot.pour(ingredients.pepper);
```

밥 넣기
```
tools.pot.pour(ingredients.boiledRice);
```

참기름 넣기
```
tools.pot.pour(ingredients.sesameOil);
```

진간장 넣기
```
tools.pot.pour(ingredients.soySauce);
```

쪽파 넣기
```
tools.pot.pour(ingredients.greenOnion);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛은 괜찮으셨나요? 김치 볶음밥은 김치를 잘 볶아야 확실히 맛이 있더라구요. 너무 쌘불에서 볶으면 고추가루들이 타니 조심해주세요. 이제 정리해주세요.

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
