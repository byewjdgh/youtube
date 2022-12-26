# 살치살 스테이크 알고리즘

오늘은 살치살 스테이크 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

크리스마스 기념 살치살 스테이크 만들어보겠습니다.
 
### Prerequisites

살치살 스테이크 요리를 위한 기본적인 준비물입니다.

#### 살치살 스테이크 식재료

```
소고기 살치살
```
```
올리브 오일
```
```
소금
```
```
후추
```
```
버터
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
포크
```
```
나이프
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

고기 넣기
```
tools.pan.pour(ingredients.chuckFlap);
```

30초 마다 뒤집기
```
ingredients.chuckFlap.flip(30, "sec");
```

버터 넣기
```
tools.pan.pour(ingredients.butter);
```

베이스팅
```
ingredients.chuckFlap.basting();
```

불 끄기
```
cooking.turnOffFire();
```

레스팅
```
ingredients.chuckFlap.resting();
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

익힘 정도를 판별하기 어려우시다면 컷팅해서 시어링 해주시면됩니다. 기름이 많이 튀었으니 정리도 잘 해주세요.

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
