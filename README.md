# [다양한 레이아웃들을 활용하여 화면 구축]
***
![Untitled (1)](https://user-images.githubusercontent.com/96619472/201299280-920082ec-b2f0-4009-8bbb-347f8b6c6f83.png)
### ConstraintLayout을 활용하여 전체 레이아웃을 구성
- 해상도 별 위치를 대응하기 위해서는 ConstraintLayout을 활용하는 것입니다.
#### 하지만 완벽한 위치를 원한다면 ConstraintLayout만 사용하기에는 문제점이 있다.
- dpi별로 value값 설정하는 방법이 있다.
- GuildLine 사용하는 방법이 있다.

### RelativeLayout을 이용하여 toolbar를 구성
![Untitled (2)](https://user-images.githubusercontent.com/96619472/201299804-b0892ae4-c76e-453c-bdc2-61d0187dae69.png)

### ScrollView를 활용하여 스크롤이 가능하도록 구성하고 LinearLayout vertical을 사용하고 ConstraintLayout으로 하나씩 구조를 쌓아 넣음
![Untitled (3)](https://user-images.githubusercontent.com/96619472/201300783-fba5da86-b493-400a-8145-8b50debc1342.png)

### BottomNavigation을 사용해야 하지만 가장 비슷해 보이는 tablelayout과 girdlayout중 사용하기 편리했던 girdlayout를 사용하였음
![Untitled (4)](https://user-images.githubusercontent.com/96619472/201299821-a747e01a-1841-4218-8994-7f74748f0625.png)

### tablelayout을 활용하고 싶어 카카오톡 더보기창을 구현
#### ConstraintLayout과 tablelayout만 활용하여 구현
![Untitled (5)](https://user-images.githubusercontent.com/96619472/201300796-2e580247-aef1-4703-aaa3-c1b51dbddeac.png)
### 문제점
#### tablelayout을 활용하여 imagebutton과 textview 중심을 맞추기 어려움을 느낌
#### scaleType과 gravity로 중심은 맞춘거 같으나 어색함

