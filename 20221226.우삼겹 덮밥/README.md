# 우삼겹 덮밥 알고리즘

오늘은 우삼겹 덮밥 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

크리스마스 기념 우삼겹 덮밥 만들어보겠습니다.
 
### Prerequisites

우삼겹 덮밥 요리를 위한 기본적인 준비물입니다.

#### 우삼겹 덮밥 식재료

```
냉동 우삼겹
```
```
소금
```
```
후추
```
```
밥
```
```
양파
```
```
계란
```
```
타레소스
```

##### 조리도구

```
프라이팬
```
```
칼
```
```
도마
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

소스까지 만드려면 여러 도구가 필요하니 정리를 잘해주세요.
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

우삼겹 넣기
```
tools.pan.pour(ingredients.shortPlate);
```

소금 넣기
```
tools.pan.pour(ingredients.salt);
```

불 끄기
```
cooking.turnOffFire();
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

### Plating

밥 담기
```
tools.bowl.pour(ingredients.boiledRice);
```

양파 담기
```
tools.bowl.pour(ingredients.onion);
```

우삼겹 담기
```
tools.bowl.pour(ingredients.shortPlate);
```

타레소스 담기
```
tools.bowl.pour(ingredients.tareSauce);
```

계란 노른자 담기
```
tools.bowl.pour(ingredients.eggYolk);
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

우삼겹도 기름이 많습니다. 정리를 잘해주세요.

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
