# 데미글라스 소스 알고리즘

데미글라스 소스 알고리즘에 대해 알아 봅시다.

## Getting Started

만능으로 쓰이는 데미글라스 소스 입니다.
 
### Prerequisites

데미글라스 소스를 위한 기본적인 준비물입니다.

```
고기 굽고 남은 기름
```
```
양송이버섯
```
```
버터
```
```
돈까스 소스
```
```
케첩
```
```
물
```

##### 조리도구

```
후라이팬
```
```
스패츌러
```
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

버터 넣기
```
tools.pan.pour(ingredients.butter);
```

양송이 버섯 넣기
```
tools.pan.pour(ingredients.buttonMushroom);
```

케첩 넣기
```
tools.pan.pour(ingredients.ketchup);
```

돈까스 소스 넣기
```
tools.pan.pour(ingredients.porkCutletSauce);
```

물 넣기
``` 
tools.pan.pour(ingredients.water);
```

섞기
``` 
tools.pan.mix();
```

맛보기
``` 
me.tasting();
```

불 끄기
```
cooking.turnOffFire();
```

### Cleaning

맛있게 드시고 정리 잘 해주세요.

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
