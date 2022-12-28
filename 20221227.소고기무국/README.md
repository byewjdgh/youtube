# 소고기무국 알고리즘

오늘은 소고기무국 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

날도 춥고 그래서 뜨끈한 소고기무국 만들어보겠습니다.
 
### Prerequisites

소고기무국 요리를 위한 기본적인 준비물입니다.

#### 소고기무국 식재료

```
국거리용 소고기
```
```
콩나물
```
```
대파
```
```
청양고추
```
```
무
```
```
참기름
```
```
간마늘
```
```
물
```
```
육수팩
```
```
진간장
```
```
국간장
```
```
고춧가루
```

##### 조리도구
```
볶음팬
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
국자
```
```
집게
```
```
접시
```
```
숟가락
```

#### 커트러리

```
숟가락
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

소고기무국은 재료 준비가 많습니다. 잘 정리해주세요.
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
tools.pan.pour(ingredients.water);
```

육수팩 넣기
```
tools.pan.pour(ingredients.stockPack);
```

5분뒤 육수팩 건져내기
```
tool.pan.remove(ingredients.stockPack, 5, "min");
```

불 끄기
```
cooking.turnOffFire();
```

#### 소고기무국 만들기

불 켜기
```
cooking.turnOnFire();
```

참기름 넣기
```
tools.pan.pour(ingredients.sesamiOil);
```

소고기 넣기
```
tools.pan.pour(ingredients.beefMeat);
```

간마늘 넣기
```
tools.pan.pour(ingredients.groundGalric);
```

무 넣기
```
tools.pan.pour(ingredients.radish);
```

진간장 넣기
```
tools.pan.pour(ingredients.soySauce);
```

육수 넣기
```
tools.pan.pour(ingredients.stock);
```

콩나물 넣기
```
tools.pan.pour(ingredients.beanSprouts);
```

고춧가루 넣기
```
tools.pan.pour(ingredients.redPepperPowder);
```

대파 넣기
```
tools.pan.pour(ingredients.greenOnion);
```

청양고추 넣기
```
tools.pan.pour(ingredients.CheongyangRedPepper);
```

간보고 싱거우면 국간장 넣기
```
if(me.feel(bland)){
    tools.pan.pour(ingredients.soupSoySauce);
}
```

불 끄기
```
cooking.turnOffFire();
```

### Plating

국 담기
```
tools.bowl.pour(ingredients.beefRadishSoup);
```
### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

맛있게 드셨나요? 제가 대구사람이라 이렇게 먹습니다. 다른 지방에서 만드는 소고기무국은 하얗더라구요.
대구에선 그걸 탕국이라 부릅니다. 명절 제사상에서 볼수 있죠. 시간될때 만들어보겠습니다.
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
