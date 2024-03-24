# Cartooner
사진을 만화풍의 그림으로 재탄생시켜보세요!
파이썬 파일과 사진파일을 같은 경로에 저장한 후 프로그램을 실행시키면 원본과 바뀐 사진이 좌우로 출력됩니다


![good](https://github.com/ajbuwidnnfjwj/Cartooner/assets/68640265/84859013-2015-48ca-b992-2b0d70ddef98)
이미지의 경계가 명확해 상이 잘 구분된다면, 바뀐 사진에서도 edge detection이 잘 수행되고 전체적인 이미지의 느낌도 만화처럼 잘 변환된 것을 알 수 있습니다


![bad](https://github.com/ajbuwidnnfjwj/Cartooner/assets/68640265/ae6f1253-5e66-4a81-ac86-de5e74f71c8e)
이미지의 경계가 명확하지 않거나 초점이 제대로 맞지 않는다면, edge detection이 잘 수행되지 않아 이미지가 흐릿해지기만 하는 느낌을 받습니다.

전체적으로 edge detection을 더 잘 수행하기 위해 thresholding 알고리즘을 개선하거나 이미지 변환 알고리즘을 수정해 흐릿한 느낌을 덜 내도록 보정할 수 있습니다.
