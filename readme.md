# Game of Life (콘웨이의 생명 게임)

> 주어진 n x m matrix 가 있습니다. 각 cell 에는 세포가 있습니다(총 n * m 개의 cell 이 있습니다).
>
> 각 세포는 죽거나 살아있는 상태입니다. 한 주기마다 세포는 다음과 같은 규칙에 따라 상태가 바뀌게됩니다.
>
> - 죽은 세포의 이웃 중 정확히 3개 세포가 살아있으면 그 죽은 세포는 살아나게 됩니다.
>
> - 살아있는 세포의 이웃 중 2개나 3개가 살아있으면 그 세포는 계속 살아있는 상태를 유지합니다.
>
> - 이외의 상황에서는 그 세포는 죽게됩니다.
>
> 이 프로그램은 초기 세포 matrix가 표준 입력으로 주어졌을 때 t 주기 후 세포 matrix 를 화면에 출력합니다.


## How to Compile
```
$ make
```

