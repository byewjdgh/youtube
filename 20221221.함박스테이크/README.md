# 함박스테이크 알고리즘

오늘은 함박스테이크 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

혈육이 함박스테이크가 먹고싶다고합니다. 함박스테이크 만들어보겠습니다.
 
### Prerequisites

함박스테이크 요리를 위한 기본적인 준비물입니다.

#### 식재료

```
물
```
```
양파
```
```
양송이
```
```
소고기 다짐육
```
```
돼지고기 다짐육
```
```
후추
```
```
소금
```
```
식용유
```
```
샐러드
```
```
마요네즈
```
```
황설탕
```
```
간마늘
```
```
케첩
```
```
돈까스 소스
```

##### 조리도구

```
믹싱볼
```
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
집게
```
```
접시
```
#### 커트러리

```
숟가락
```
```
나이프
```
```
포크
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

오늘은 사용할 도구들이 많습니다. 잘 준비해주세요.
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

#### 함박스테이크 만들기

돼지고기, 소고기 다짐육 넣기
```
tools.mixingbowl.pour(ingredients.beefGroundMeat, ingredients.porkGroundMeat);
```

후추, 소금 넣기
```
tools.mixingbowl.pour(ingredients.pepper, ingredients.salt);
```

잘 섞기
```
me.mix(tools.mixingbowl);
```

함박스테이크 만들기
```
me.make(ingredients.hamburgSteak);
```

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pot.pour(ingredients.cookingOil);
```

함박스테이크 넣기
```
tools.pot.pour(ingredients.hamburgSteak);
```

꾹 눌러주기
```
ingredients.hamburgSteak.press();
```

5분 마다 함박스테이크 뒤집기(총 15분)
```
ingredients.hamburgSteak.flip(5, "min");
```

함박스테이크 레스팅 하기
```
ingredients.hamburgSteak.resting();
```

#### 스테이크 소스 만들기

다진 양파 및 양송이 버섯 넣기
```
tools.pot.pour(ingredients.onion, ingredients.buttonMushroom);
```

버터 넣기
```
tools.pot.pour(ingredients.butter);
```

케첩 및 돈까스 소스 넣기
```
tools.pot.pour(ingredients.ketchup, ingredients.porkCutletSauce);
```

물 넣기
```
tools.pot.pour(ingredients.water);
```

불 끄기
```
cooking.turnOffFire();
```

#### 마늘 드레싱 만들기

간마늘 및 마요네즈 넣기
```
tools.mixingbowl2.pour(ingredients.groundGalric, ingredients.mayonnaise);
```

사이다 넣기
```
tools.mixingbowl2.pour(ingredients.sprite);
```

후추 넣기
```
tools.mixingbowl2.pour(ingredients.pepper);
```

황설탕 넣기
```
tools.mixingbowl2.pour(ingredients.brownSugar);
```
### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

많이 정신 없지 않으신가요? 괜찮습니다. 하다보면 익숙해 질겁니다. 난장판인 상황을 정리합시다.

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
