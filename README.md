# 생활코딩 자바스크립트(17~18):조건문 활용, 리팩토링 중복 제거


# 1). 조건문 활용:

  - id 값을 입력할때 = '# '

  - .value = 태그의 값을 가져온다


  - 해당 코드에서 if문 두문장만으로는 반복을 할 수 없기 때문에 바로 밑에 다른 값으로 value를 바꿔준다.


# 2). 리팩토링 중복 제거:

  - 리펙토링: 코드의 기능은 그대로 두고, 코드 전체만 깔끔하게 정리하는 작업 
                 ex). this = id에 해당하는 코드를 간편하게 바꿈

  - 코딩을 잘 하는법: 중복을 최대한 없애라

  - 중복 제거 -> 태그에 변수를 부여하고 해당 변수로 통일 시켜 중복 제거 


```학습후기: 코딩의 핵심은 중복을 최대한 없애는 것이라는 것을 처음 알게 되었다. 복잡한 코드는 작업을 하는데 불편함을 주기 때문에 이를 this를 이용하거나 태그에 변수를 부여하여 간편화 한다고 한다. 
아직 이에 대해 제대로 공감하기는 힘들지만, 평상시 연습을 할때 이를 숙지하는 습관을 들여야 할 듯 하다.```