# 오므라이스 알고리즘

오늘은 오므라이스 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

구독자님께서 오므라이스를 부탁하셨습니다. 오므라이스 만들어보겠습니다.
 
### Prerequisites

오므라이스 요리를 위한 기본적인 준비물입니다.

#### 오므라이스 식재료

```
돼지고기 다짐육
```
```
대파
```
```
간마늘
```
```
밥
```
```
진간장
```
```
참기름
```
```
후추
```
```
치킨스톡 분말
```
```
계란
```
```
버터
```
```
소금
```
#### 소스 식재료
```
간마늘
```
```
양파
```
```
양송이 버섯
```
```
버터
```
```
케첩
```
```
돈까스 소스
```
```
물
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

오므라이스는 생각보다 손이 많이 가는 음식입니다. 그러니 정리는 필수입니다.
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

#### 오므라이스 소스 만들기

불 켜기
```
cooking.turnOnFire();
```

버터 넣기
```
tools.pot.pour(ingredients.butter);
```

양파 넣기
```
tools.pot.pour(ingredients.onion);
```

양송이 버섯 넣기
```
tools.pot.pour(ingredients.buttonMushroom);
```

간마늘 넣기
```
tools.pot.pour(ingredients.groundGalric);
```

케첩 넣기
```
tools.pot.pour(ingredients.ketchup);
```

돈까스 소스 넣기
```
tools.pot.pour(ingredients.porkCutletSauce);
```

물 넣기
``` 
tools.pot.pour(ingredients.water);
```

불 끄기
```
cooking.turnOffFire();
```

#### 오므라이스용 밥 만들기

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pot2.pour(ingredients.cookingOil);
```

돼지고기 다짐육 넣기
```
tools.pot2.pour(ingredients.porkGroundMeat);
```

간마늘 넣기
```
tools.pot2.pour(ingredients.groundGalric);
```

파 넣기
```
tools.pot2.pour(ingredients.greenOnion);
```

밥 넣기
```
tools.pot2.pour(ingredients.boiledRice);
```

진간장 넣기
```
tools.pot2.pour(ingredients.soySauce);
```

참기름 넣기
```
tools.pot2.pour(ingredients.sesameOil);
```

후추 넣기
```
tools.pot2.pour(ingredients.pepper);
```

간보고 싱거우면 간장 더 넣기
```
if(!me.feel(salty)){
    tools.pot2.pour(ingredients.soySauce);
}
```

#### 오므라이스 지단 만들기

불 켜기
```
cooking.turnOnFire();
```

버터 넣기
```
tools.pot3.pour(ingredients.butter);
```

계란물 넣기
```
tools.pot3.pour(ingredients.egg);
```

오므라이스용 밥 넣기
```
tools.pot3.pour(ingredients.FriedRice);
```

불 끄기
```
cooking.turnOffFire();
```

### Eating

그릇에 담기
```
tools.bowl.pour(ingredients.omurice);
```

소스 넣기
```
tools.bowl.pour(ingredients.omuriceSauce);
```

맛있게 먹기
```
me.eat();
```

### Cleaning

이번엔 제가 실패한 요리입니다. 하지만 실패는 누구나 할 수 있죠. 맛있게 드시고 정리 잘 해주세요.

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
