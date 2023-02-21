# 토마토 소스 알고리즘

토마토 소스 알고리즘에 대해 알아 봅시다.

## Getting Started

피자와 스파게티에 쓰이는 토마토 소스 입니다.
 
### Prerequisites

토마토 소스를 위한 기본적인 준비물입니다.

```
바질
```
```
엑스트라 버진 오일
```
```
토마토 소스(캔)
```
```
양파
```
```
마늘
```
```
페페론치노
```
```
드라이 로즈마리
```
```
월계수 잎
```
```
소금
```
```
후추
```
```
물
```

##### 조리도구

```
중화팬
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
```
블렌더
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
result   = cooking.initResult();
```

재료 준비
```
ingredients = cooking.readyIngredients();
```

### Cooking

#### 토마토 소스 만들기

불 켜기
```
cooking.turnOnFire();
```

양파 넣기
```
tools.pan.pour(ingredients.onion);
```

마늘 넣기
```
tools.pan.pour(ingredients.galric);
```

페페론치노 넣기
```
tools.pan.pour(ingredients.peperoncino);
```

토마토 소스 넣기
```
tools.pan.pour(ingredients.tomatoSauce);
```

드라이 로즈마리 넣기
```
tools.pan.pour(ingredients.DriedRosemary);
```

월계수 잎 넣기
```
tools.pan.pour(ingredients.bayLeaves);
```

소금 넣기
```
tools.pan.pour(ingredients.salt);
```

후추 넣기
```
tools.pan.pour(ingredients.pepper);
```

월계수 잎 제거
```
tools.pan.remove(ingredients.bayLeaves);
```

40분간 끓이기
```
tools.pan.boil(40, "min");
```

불 끄기
```
cooking.turnOffFire();
```

갈기
```
tools.blender.blend(result.tomatoSauce);
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
