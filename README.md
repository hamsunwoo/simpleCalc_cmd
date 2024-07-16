# 첫번째 팀프로젝트

## Goals
- 간단한 계산기 만들기
- calc 파일에 간단한 계산기 구현 후 pip에 배포 
- cmd파일을 만들어 calc의 패키지를 설치하고 dependencies에 추가

- 실행 

## Install

```
$ pip install simpleCalc_cmd
```

## Mechanism
`hc_simpleCalc`를 dependency로 가지고 있으며 해당 패키지의 `add`, `div`, `mul` 함수를 통해 `call_add`, `call_div`, `call_mul`을 구현하고 있습니다.

해당 함수들은 command line에서 `hc_add`, `hc_div`, `hc_mul`의 세가지 커맨드로 호출됩니다.

## Example
```
$ hc_add
더하기

$hc_div
나누기

$hc_mul
곱하기
```
