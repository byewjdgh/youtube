# 소고기 미역국 알고리즘

오늘은 소고기 미역국 만들기 알고리즘에 대해 알아 봅시다.

## Getting Started

날도 추워지고하니 뜨끈한 미역국이 땡기더라구요. 오늘은 배달말고 건강한 미역국 만들어봅시다.
 
### Prerequisites

소고기 미역국 요리를 위한 기본적인 준비물입니다.

```
냄비
```
```
물
```
```
자른미역
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
육수팩
```
```
숟가락
```
```
젓가락
```
```
진간장
```
```
국간장
```
```
소금
```
```
후추
```
```
비엔나 소세지(optional)
```

이 과정까지 오셨다면 요리를 위한 준비는 완료되었습니다.

## Cooking

요리를 시작하겠습니다.

### Initializing

요리의 기본은 정리부터 시작입니다. 씽크대가 더럽다던가 준비가 덜된 느낌이라면 정리부터 해주세요.
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

모든 변수가 초기화 되었으니 요리를 시작하시면됩니다.

불 켜기
```
cooking.turnOnFire();
```

참기름 넣기
```
tools.pot.pour(sesameOil);
```

국거리용 소고기 넣기
```
tools.pot.pour(beef);
```

간마늘 넣기
```
tools.pot.pour(groundGalric);
```

고기가 어느정도 익을때 까지 볶기
```
while(!ingredients.beef.isCooked){
    me.stirFry();
}
```
 
미역 넣기
```
tools.pot.pour(seaweed);
```
 
진간장 넣기
```
tools.pot.pour(soysouce);
```

육수팩 넣기
```
tools.pot2.pour(stockPack);
```

육수 넣기
```
tools.pot.pour(stock);
```

후추 넣기
```
tools.pot.pour(pepper);
```

간보고 싱겁다면 소금 넣기(optional)
```
if(me.feel(bland)){
    tools.pot.pour(salt);
}
```

불 끄기
```
cooking.turnOffFire();
```

### Eating

맛있게 먹기
```
me.eat();
```

### Cleaning

든든하신가요? 맛있게 드셨다면 바로바로 치웁시다!

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
