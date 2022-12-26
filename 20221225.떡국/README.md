# 떡국 알고리즘

오늘은 떡국 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

엄마가 떡국 떡을 주셨습니다. 떡국을 만들어보겠습니다.
 
### Prerequisites

떡국 요리를 위한 기본적인 준비물입니다.

#### 떡국 식재료

```
떡국 떡
```
```
식용유
```
```
참기름
```
```
국거리용 소고기
```
```
간마늘
```
```
부드러운 두부
```
```
물
```
```
국간장
```
```
계란
```
```
후추
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

정리는 필수입니다.
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

불 켜기
```
cooking.turnOnFire();
```

식용유 넣기
```
tools.pot.pour(ingredients.cookingOil);
```

참기름 넣기
```
tools.pot.pour(ingredients.sesameOil);
```

국거리용 소고기 넣기
```
tools.pot.pour(ingredients.beefForSoup);
```

간마늘 넣기
```
tools.pot.pour(ingredients.groundGalric);
```

두부 넣기
```
tools.pot.pour(ingredients.tofu);
```

진간장 넣기
```
tools.pot.pour(ingredients.soySauce);
```

국간장 넣기
```
tools.pot.pour(ingredients.soupSoySauce);
```

떡국 떡 넣기
```
tools.pot.pour(ingredients.riceCake);
```

간보고 싱겁다면 국간장 넣기
```
if(!me.feel(salty)){
    tools.pot.pour(ingredients.soupSoySauce);
}
```

계란 넣기
```
tools.pot.pour(ingredients.egg);
```

불 끄기
```
cooking.turnOffFire();
```

후추 넣기
```
tools.pot.pour(ingredients.pepper);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

생각보다 간편한 음식입니다. 새해복 많이 받으세요. 정리도 해주세요.

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
