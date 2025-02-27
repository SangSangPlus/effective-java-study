# effective-java-study

![image](https://github.com/uhanuu/effective-java/assets/110734817/b3de0805-d28d-44f7-af6a-8cf644e8ee80)


<br>

<br>

## 😎 Member
| <img src="https://github.com/user-attachments/assets/2d485895-6658-4cca-b9be-4525d1bdb2c7" width="130" height="130"> | <img src="https://github.com/user-attachments/assets/df57aa0e-185c-4dde-a7b6-688fa4010590" width="130" height="130"> | <img src="https://github.com/user-attachments/assets/2ebbedef-85ee-4f6c-b7b7-0b7b216054dd" width="130" height="130"> | <img src="https://github.com/user-attachments/assets/504cf9f8-3437-498d-95d6-6e6635a594ac" width="130" height="130"> |
|:--------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|
|                                          [강철원](https://github.com/Ryan-Dia)                                          |                                        [김명지](https://github.com/Starlight258)                                        |                                         [김진수](https://github.com/plan11plan)                                         |                                          [박형균](https://github.com/phk1128)                                           |

## 목차
<details>
  <summary><a href="https://github.com/SangSangPlus/effective-java-study/tree/main/Chapter_02">Chapter 02 : 객체 생성과 파괴</a></summary>

  - [Item 01 : 생성자 대신 정적 팩토리 메서드를 고려하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C%5Ditem_01_%EC%83%9D%EC%84%B1%EC%9E%90%20%EB%8C%80%EC%8B%A0%20%EC%A0%95%EC%A0%81%20%ED%8C%A9%ED%84%B0%EB%A6%AC%20%EB%A9%94%EC%84%9C%EB%93%9C%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC(%EB%B0%95%ED%98%95%EA%B7%A0).md)
  - [Item 02 : 생성자에 매개변수가 많다면 빌더를 고려하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C%5Ditem_02_%EC%83%9D%EC%84%B1%EC%9E%90%EC%97%90%20%EB%A7%A4%EA%B0%9C%EB%B3%80%EC%88%98%EA%B0%80%20%EB%A7%8E%EB%8B%A4%EB%A9%B4%20%EB%B9%8C%EB%8D%94%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC(%EB%B0%95%ED%98%95%EA%B7%A0).md)
  - [Item 03 : private 생성자나 열거 타입으로 싱글톤임을 보증하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_03_private_%E1%84%89%E1%85%A2%E1%86%BC%E1%84%89%E1%85%A5%E1%86%BC%E1%84%8C%E1%85%A1%E1%84%82%E1%85%A1_%E1%84%8B%E1%85%A7%E1%86%AF%E1%84%80%E1%85%A5_%E1%84%90%E1%85%A1%E1%84%8B%E1%85%B5%E1%86%B8%E1%84%8B%E1%85%B3%E1%84%85%E1%85%A9_%E1%84%89%E1%85%B5%E1%86%BC%E1%84%80%E1%85%B3%E1%86%AF%E1%84%90%E1%85%A5%E1%86%AB%E1%84%8B%E1%85%B5%E1%86%B7%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%87%E1%85%A9%E1%84%8C%E1%85%A1%E1%86%BC%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%86%E1%85%A7%E1%86%BC%E1%84%8C%E1%85%B5).pdf)
  - [Item 04 : 인스턴스화를 막으려거든 private 생성자를 사용하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_04_%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%89%E1%85%B3%E1%84%90%E1%85%A5%E1%86%AB%E1%84%89%E1%85%B3%E1%84%92%E1%85%AA%E1%84%85%E1%85%B3%E1%86%AF_%E1%84%86%E1%85%A1%E1%86%A8%E1%84%8B%E1%85%B3%E1%84%85%E1%85%A7%E1%84%80%E1%85%A5%E1%84%83%E1%85%B3%E1%86%AB_private_%E1%84%89%E1%85%A2%E1%86%BC%E1%84%89%E1%85%A5%E1%86%BC%E1%84%8C%E1%85%A1%E1%84%85%E1%85%B3%E1%86%AF_%E1%84%89%E1%85%A1%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%86%E1%85%A7%E1%86%BC%E1%84%8C%E1%85%B5).pdf)
  - [Item 05 : 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_05_%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%AF%E1%86%AB%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%8C%E1%85%B5%E1%86%A8%E1%84%8C%E1%85%A5%E1%86%B8_%E1%84%86%E1%85%A7%E1%86%BC%E1%84%89%E1%85%B5%E1%84%92%E1%85%A1%E1%84%8C%E1%85%B5_%E1%84%86%E1%85%A1%E1%86%AF%E1%84%80%E1%85%A9_%E1%84%8B%E1%85%B4%E1%84%8C%E1%85%A9%E1%86%AB_%E1%84%80%E1%85%A2%E1%86%A8%E1%84%8E%E1%85%A6_%E1%84%8C%E1%85%AE%E1%84%8B%E1%85%B5%E1%86%B8%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%89%E1%85%A1%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%A1%E1%86%BC%E1%84%8E%E1%85%A5%E1%86%AF%E1%84%8B%E1%85%AF%E1%86%AB).pdf)
  - [Item 06 : 불필요한 객체 생성을 피하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_06_%E1%84%87%E1%85%AE%E1%86%AF%E1%84%91%E1%85%B5%E1%86%AF%E1%84%8B%E1%85%AD%E1%84%92%E1%85%A1%E1%86%AB_%E1%84%80%E1%85%A2%E1%86%A8%E1%84%8E%E1%85%A6_%E1%84%89%E1%85%A2%E1%86%BC%E1%84%89%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%91%E1%85%B5%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%8C%E1%85%B5%E1%86%AB%E1%84%89%E1%85%AE).pdf)
  - [Item 07 : 다 쓴 객체 참조를 해제하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_07_%E1%84%83%E1%85%A1%20%E1%84%8A%E1%85%B3%E1%86%AB%20%E1%84%80%E1%85%A2%E1%86%A8%E1%84%8E%E1%85%A6%20%E1%84%8E%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%A9%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%A2%E1%84%8C%E1%85%A6%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1.(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%8C%E1%85%B5%E1%86%AB%E1%84%89%E1%85%AE).pdf)
  - [Item 08 : finalizer와 cleaner 사용을 피하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_08_finalizer%E1%84%8B%E1%85%AA_cleaner_%E1%84%89%E1%85%A1%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%91%E1%85%B5%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%A1%E1%86%BC%E1%84%8E%E1%85%A5%E1%86%AF%E1%84%8B%E1%85%AF%E1%86%AB).pdf)
  - [Item 09 : try-finally보다는 try-with-resources를 사용하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_09_try-finally%E1%84%87%E1%85%A9%E1%84%83%E1%85%A1%E1%84%82%E1%85%B3%E1%86%AB%20try-with-resources%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%89%E1%85%A1%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%87%E1%85%A1%E1%86%A8%E1%84%92%E1%85%A7%E1%86%BC%E1%84%80%E1%85%B2%E1%86%AB).pdf)

</details>

<details>
  <summary><a href="https://github.com/SangSangPlus/effective-java-study/tree/main/Chapter_03">Chapter 03 : 모든 객체의 공통 메서드</a></summary>

  - [Item 10 : equals는 일반 규약을 지켜 재정의하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_03/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_10_equals()%E1%84%82%E1%85%B3%E1%86%AB_%E1%84%8B%E1%85%B5%E1%86%AF%E1%84%87%E1%85%A1%E1%86%AB_%E1%84%80%E1%85%B2%E1%84%8B%E1%85%A3%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%8C%E1%85%B5%E1%84%8F%E1%85%A7_%E1%84%8C%E1%85%A2%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B4%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%86%E1%85%A7%E1%86%BC%E1%84%8C%E1%85%B5).pdf)
  - [Item 11 : equals를 재정의하려거든 hashCode도 재정의하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_03/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_11_equals%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8C%E1%85%A2%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B4%E1%84%92%E1%85%A1%E1%84%85%E1%85%A7%E1%84%80%E1%85%A5%E1%84%83%E1%85%B3%E1%86%AB%20hashCode%E1%84%83%E1%85%A9%20%E1%84%8C%E1%85%A2%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B4%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%87%E1%85%A1%E1%86%A8%E1%84%92%E1%85%A7%E1%86%BC%E1%84%80%E1%85%B2%E1%86%AB).pdf)
  - [Item 12 : toString을 항상 재정의하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_03/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_12_%20toString%E1%84%8B%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%A1%E1%86%BC%E1%84%89%E1%85%A1%E1%86%BC%20%E1%84%8C%E1%85%A2%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B4%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1.(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%8C%E1%85%B5%E1%86%AB%E1%84%89%E1%85%AE).pdf)
  - [Item 13 : clone 재정의는 주의해서 진행하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_03/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_13_clone_%E1%84%8C%E1%85%A2%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B4%E1%84%82%E1%85%B3%E1%86%AB_%E1%84%8C%E1%85%AE%E1%84%8B%E1%85%B4%E1%84%92%E1%85%A2%E1%84%89%E1%85%A5_%E1%84%8C%E1%85%B5%E1%86%AB%E1%84%92%E1%85%A2%E1%86%BC%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%A1%E1%86%BC%E1%84%8E%E1%85%A5%E1%86%AF%E1%84%8B%E1%85%AF%E1%86%AB).pdf)
  - [Item 14 : Comparable을 구현할지 고려하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_03/%5B%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C%5Ditem_14_Comparable%EC%9D%84_%EA%B5%AC%ED%98%84%ED%95%A0%EC%A7%80_%EA%B3%A0%EB%A0%A4%ED%95%98%EC%9E%90(%EA%B9%80%EB%AA%85%EC%A7%80).pdf)

</details>

<details>
  <summary><a href="https://github.com/SangSangPlus/effective-java-study/tree/main/Chapter_04">Chapter 04 : 클래스와 인터페이스</a></summary>

  - [Item 15 : 클래스와 멤버의 접근 권한을 최소화하라]()

  - [Item 16 : public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_04/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_16_public_%E1%84%8F%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A2%E1%84%89%E1%85%B3%E1%84%8B%E1%85%A6%E1%84%89%E1%85%A5%E1%84%82%E1%85%B3%E1%86%AB_public_%E1%84%91%E1%85%B5%E1%86%AF%E1%84%83%E1%85%B3%E1%84%80%E1%85%A1_%E1%84%8B%E1%85%A1%E1%84%82%E1%85%B5%E1%86%AB_%E1%84%8C%E1%85%A5%E1%86%B8%E1%84%80%E1%85%B3%E1%86%AB%E1%84%8C%E1%85%A1_%E1%84%86%E1%85%A6%E1%84%89%E1%85%A5%E1%84%83%E1%85%B3%E1%84%85%E1%85%B3%E1%86%AF_%E1%84%89%E1%85%A1%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%A1%E1%86%BC%E1%84%8E%E1%85%A5%E1%86%AF%E1%84%8B%E1%85%AF%E1%86%AB).pdf)
  - [Item 17 : 변경 가능성을 최소화하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_04/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_17_%E1%84%87%E1%85%A7%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC_%E1%84%80%E1%85%A1%E1%84%82%E1%85%B3%E1%86%BC%E1%84%89%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%8E%E1%85%AC%E1%84%89%E1%85%A9%E1%84%92%E1%85%AA%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%86%E1%85%A7%E1%86%BC%E1%84%8C%E1%85%B5).pdf)
  - [Item 18 : 상속보다는 컴포지션을 사용하라](https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_04/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_18_%20%E1%84%89%E1%85%A1%E1%86%BC%E1%84%89%E1%85%A9%E1%86%A8%E1%84%87%E1%85%A9%E1%84%83%E1%85%A1%E1%84%82%E1%85%B3%E1%86%AB_%E1%84%8F%E1%85%A5%E1%86%B7%E1%84%91%E1%85%A9%E1%84%8C%E1%85%B5%E1%84%89%E1%85%A7%E1%86%AB%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%89%E1%85%A1%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%8C%E1%85%B5%E1%86%AB%E1%84%89%E1%85%AE).pdf)

</details>


## **1주차** ( 01/06 (월) )       

> | Item 1 | Item 2 | Item 3 |Item 4 | Item 5 |Item 6 |
> | :-:| :-: | :-: | :-: | :-: | :-: |
> | 박형균 | 박형균 | 김명지 | 김명지 | 강철원 | 김진수 | 

## **2주차** ( 01/15 (수) )

> | Item 7 | Item 8 | Item 9 | Item 10 |
> |:------:|:------:|:------:|:-------:|
> |  김진수   |  강철원   |  박형균   |   김명지   | 

## **3주차** ( 01/22 (수) )

> | Item 11 | Item 12 | Item 13 | Item 14 |
> |:-------:|:-------:|:-------:|:-------:|
> |   박형균   |   김진수   |   강철원   |   김명지   |


## **4주차** ( 02/03 (월) )

> | Item 15 | Item 16 | Item 17 | Item 18 |
> |:-------:|:-------:|:-------:|:-------:|
> |   박형균   |   강철원   |   김명지   |   김진수   |
   
### 💎 발표자료

<img width="500px" alt="item 1 썸네일" src="https://github.com/user-attachments/assets/bff7910d-77ec-4618-bade-93a94d411173"> | <img width="500px" alt="item 2 썸네일" src="https://github.com/user-attachments/assets/97f68b70-82de-45d2-88fb-2cae2f0f93dd"> 
| :---: | :---: |
|[📚 Item 1 생성자 대신 정적 팩터리 메서드를 고려하라] <br> [🎥 Item 1 발표 영상] |  [📚 Item 2 생성자에 매개변수가 많다면 빌더를 고려하라] <br> [🎥 Item 2 발표 영상] |
<img width="500px" alt="Item 3 썸네일" src="https://github.com/user-attachments/assets/5ef0b964-171f-4177-b9b7-a0718a7d4553"> | <img width="500px" alt="Item 4 썸네일" src="https://github.com/user-attachments/assets/ca07f6a1-fba1-4965-861b-bae4a5a19294"> 
|[📚 Item 3 생성자나 열거 타입으로 싱글턴임을 보증하라] <br> [🎥 Item 3 발표 영상] | [📚 Item 4 인스턴스화를 막으려거든 private 생성자를 사용하라] <br> [🎥 Item 4 발표 영상] |
<img width="500px" alt="Item 5 썸네일" src="https://github.com/user-attachments/assets/e9647d46-bb07-41ce-a6db-daac73238329"> | <img width="500px" alt="Item 6 썸네일" src="https://github.com/user-attachments/assets/580ee12a-3c17-45a8-9955-2b0c9eb1f417"> 
|[📚 Item 5 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라] <br> [🎥 Item 5 발표 영상] | [📚 Item 6 불필요한 객체 생성을 피하라] <br> [🎥 Item 6 발표 영상] |
<img width="500px" alt="Item 7 썸네일" src="https://github.com/user-attachments/assets/483426d5-5b23-4333-a256-253495f2d649"> | <img width="500px" alt="Item 8 썸네일" src="https://github.com/user-attachments/assets/193c2f7c-124d-438c-9226-8f9a19088f29"> 
|[📚 Item 7 다 쓴 객체 참조를 해제하라] <br> [🎥 Item 7 발표 영상] | [📚 Item 8 finalizer와 cleaner 사용을 피하라] <br> [🎥 Item 8 발표 영상] |
<img width="500px" alt="Item 9 썸네일" src="https://github.com/user-attachments/assets/a9d26f54-939e-4472-ac34-bf4172e52803"> | <img width="500px" alt="Item 10 썸네일" src="https://github.com/user-attachments/assets/3726721a-065d-4f17-a4ad-19244dab0f2d">
|[📚 Item 9 try-finally보다는 try-with-resources를 사용하라] <br> [🎥 Item 9 발표 영상] | [📚 Item 10 equals는 일반 규약을 지켜 재정의하라] <br> [🎥 Item 10 발표 영상] |
<img width="500px" alt="Item 11 썸네일" src="https://github.com/user-attachments/assets/1e7f1010-7c8b-4ca0-b817-4f721ef14d43"> | <img width="500px" alt="Item 12 썸네일" src="https://github.com/user-attachments/assets/f6cb069a-3e9f-4b5f-8993-7a10aae66e27">
|[📚 Item 11 equals를 재정의하려거든 hashCode도 재정의하라] <br> [🎥 Item 11 발표 영상] | [📚 Item 12 toString을 항상 재정의하라] <br> [🎥 Item 12 발표 영상] |
<img width="500px" alt="Item 13 썸네일" src="https://github.com/user-attachments/assets/445dd57a-0ff1-4087-82b3-28b014f84313"> | <img width="500px" alt="Item 14 썸네일" src="https://github.com/user-attachments/assets/70c859f5-d4b9-458d-bece-53304b4b7c26">
|[📚 Item 13 clone 재정의는 주의해서 진행하라] <br> [🎥 Item 13 발표 영상] | [📚 Item 14 Comparable을 구현할지 고려하라] <br> [🎥 Item 14 발표 영상] |


[📚 Item 1 생성자 대신 정적 팩터리 메서드를 고려하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C%5Ditem_01_%EC%83%9D%EC%84%B1%EC%9E%90%20%EB%8C%80%EC%8B%A0%20%EC%A0%95%EC%A0%81%20%ED%8C%A9%ED%84%B0%EB%A6%AC%20%EB%A9%94%EC%84%9C%EB%93%9C%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC(%EB%B0%95%ED%98%95%EA%B7%A0).md
[🎥 Item 1 발표 영상]: https://www.youtube.com/watch?v=SPslEAu3DxM

[📚 Item 2 생성자에 매개변수가 많다면 빌더를 고려하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C%5Ditem_02_%EC%83%9D%EC%84%B1%EC%9E%90%EC%97%90%20%EB%A7%A4%EA%B0%9C%EB%B3%80%EC%88%98%EA%B0%80%20%EB%A7%8E%EB%8B%A4%EB%A9%B4%20%EB%B9%8C%EB%8D%94%EB%A5%BC%20%EA%B3%A0%EB%A0%A4%ED%95%98%EB%9D%BC(%EB%B0%95%ED%98%95%EA%B7%A0).md
[🎥 Item 2 발표 영상]: https://www.youtube.com/watch?v=UxoV5QmXF2w

[📚 Item 3 생성자나 열거 타입으로 싱글턴임을 보증하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_03_private_%E1%84%89%E1%85%A2%E1%86%BC%E1%84%89%E1%85%A5%E1%86%BC%E1%84%8C%E1%85%A1%E1%84%82%E1%85%A1_%E1%84%8B%E1%85%A7%E1%86%AF%E1%84%80%E1%85%A5_%E1%84%90%E1%85%A1%E1%84%8B%E1%85%B5%E1%86%B8%E1%84%8B%E1%85%B3%E1%84%85%E1%85%A9_%E1%84%89%E1%85%B5%E1%86%BC%E1%84%80%E1%85%B3%E1%86%AF%E1%84%90%E1%85%A5%E1%86%AB%E1%84%8B%E1%85%B5%E1%86%B7%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%87%E1%85%A9%E1%84%8C%E1%85%A1%E1%86%BC%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%86%E1%85%A7%E1%86%BC%E1%84%8C%E1%85%B5).pdf
[🎥 Item 3 발표 영상]: https://www.youtube.com/watch?v=B2irvGasOHU

[📚 Item 4 인스턴스화를 막으려거든 private 생성자를 사용하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_04_%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%89%E1%85%B3%E1%84%90%E1%85%A5%E1%86%AB%E1%84%89%E1%85%B3%E1%84%92%E1%85%AA%E1%84%85%E1%85%B3%E1%86%AF_%E1%84%86%E1%85%A1%E1%86%A8%E1%84%8B%E1%85%B3%E1%84%85%E1%85%A7%E1%84%80%E1%85%A5%E1%84%83%E1%85%B3%E1%86%AB_private_%E1%84%89%E1%85%A2%E1%86%BC%E1%84%89%E1%85%A5%E1%86%BC%E1%84%8C%E1%85%A1%E1%84%85%E1%85%B3%E1%86%AF_%E1%84%89%E1%85%A1%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%86%E1%85%A7%E1%86%BC%E1%84%8C%E1%85%B5).pdf
[🎥 Item 4 발표 영상]: https://www.youtube.com/watch?v=xp8S9OzByB8

[📚 Item 5 자원을 직접 명시하지 말고 의존 객체 주입을 사용하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_05_%E1%84%8C%E1%85%A1%E1%84%8B%E1%85%AF%E1%86%AB%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%8C%E1%85%B5%E1%86%A8%E1%84%8C%E1%85%A5%E1%86%B8_%E1%84%86%E1%85%A7%E1%86%BC%E1%84%89%E1%85%B5%E1%84%92%E1%85%A1%E1%84%8C%E1%85%B5_%E1%84%86%E1%85%A1%E1%86%AF%E1%84%80%E1%85%A9_%E1%84%8B%E1%85%B4%E1%84%8C%E1%85%A9%E1%86%AB_%E1%84%80%E1%85%A2%E1%86%A8%E1%84%8E%E1%85%A6_%E1%84%8C%E1%85%AE%E1%84%8B%E1%85%B5%E1%86%B8%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%89%E1%85%A1%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%A1%E1%86%BC%E1%84%8E%E1%85%A5%E1%86%AF%E1%84%8B%E1%85%AF%E1%86%AB).pdf
[🎥 Item 5 발표 영상]: https://www.youtube.com/watch?v=E54SmKMXSBg

[📚 Item 6 불필요한 객체 생성을 피하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_06_%E1%84%87%E1%85%AE%E1%86%AF%E1%84%91%E1%85%B5%E1%86%AF%E1%84%8B%E1%85%AD%E1%84%92%E1%85%A1%E1%86%AB_%E1%84%80%E1%85%A2%E1%86%A8%E1%84%8E%E1%85%A6_%E1%84%89%E1%85%A2%E1%86%BC%E1%84%89%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%91%E1%85%B5%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%8C%E1%85%B5%E1%86%AB%E1%84%89%E1%85%AE).pdf
[🎥 Item 6 발표 영상]: https://www.youtube.com/watch?v=GmmxGeFH4iQ&t=64s

[📚 Item 7 다 쓴 객체 참조를 해제하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_07_%E1%84%83%E1%85%A1%20%E1%84%8A%E1%85%B3%E1%86%AB%20%E1%84%80%E1%85%A2%E1%86%A8%E1%84%8E%E1%85%A6%20%E1%84%8E%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%A9%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%A2%E1%84%8C%E1%85%A6%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1.(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%8C%E1%85%B5%E1%86%AB%E1%84%89%E1%85%AE).pdf
[🎥 Item 7 발표 영상]: https://www.youtube.com/watch?v=PnmiypnSwaU

[📚 Item 8 finalizer와 cleaner 사용을 피하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_08_finalizer%E1%84%8B%E1%85%AA_cleaner_%E1%84%89%E1%85%A1%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%91%E1%85%B5%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%A1%E1%86%BC%E1%84%8E%E1%85%A5%E1%86%AF%E1%84%8B%E1%85%AF%E1%86%AB).pdf
[🎥 Item 8 발표 영상]: https://www.youtube.com/watch?v=kwHFWFIG0dU

[📚 Item 9 try-finally보다는 try-with-resources를 사용하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_02/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_09_try-finally%E1%84%87%E1%85%A9%E1%84%83%E1%85%A1%E1%84%82%E1%85%B3%E1%86%AB%20try-with-resources%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%89%E1%85%A1%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%87%E1%85%A1%E1%86%A8%E1%84%92%E1%85%A7%E1%86%BC%E1%84%80%E1%85%B2%E1%86%AB).pdf
[🎥 Item 9 발표 영상]: https://www.youtube.com/watch?v=FKPjhNO9EQ0

[📚 Item 10 equals는 일반 규약을 지켜 재정의하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_03/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_10_equals()%E1%84%82%E1%85%B3%E1%86%AB_%E1%84%8B%E1%85%B5%E1%86%AF%E1%84%87%E1%85%A1%E1%86%AB_%E1%84%80%E1%85%B2%E1%84%8B%E1%85%A3%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF_%E1%84%8C%E1%85%B5%E1%84%8F%E1%85%A7_%E1%84%8C%E1%85%A2%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B4%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%86%E1%85%A7%E1%86%BC%E1%84%8C%E1%85%B5).pdf
[🎥 Item 10 발표 영상]: https://www.youtube.com/watch?v=p3t42XsbdZY

[📚 Item 11 equals를 재정의하려거든 hashCode도 재정의하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_03/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_11_equals%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%8C%E1%85%A2%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B4%E1%84%92%E1%85%A1%E1%84%85%E1%85%A7%E1%84%80%E1%85%A5%E1%84%83%E1%85%B3%E1%86%AB%20hashCode%E1%84%83%E1%85%A9%20%E1%84%8C%E1%85%A2%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B4%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%87%E1%85%A1%E1%86%A8%E1%84%92%E1%85%A7%E1%86%BC%E1%84%80%E1%85%B2%E1%86%AB).pdf
[🎥 Item 11 발표 영상]: https://www.youtube.com/watch?v=6QwmPnnXdsc

[📚 Item 12 toString을 항상 재정의하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_03/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_12_%20toString%E1%84%8B%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%A1%E1%86%BC%E1%84%89%E1%85%A1%E1%86%BC%20%E1%84%8C%E1%85%A2%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B4%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1.(%E1%84%80%E1%85%B5%E1%86%B7%E1%84%8C%E1%85%B5%E1%86%AB%E1%84%89%E1%85%AE).pdf
[🎥 Item 12 발표 영상]: https://www.youtube.com/watch?v=dmM513xhu1E

[📚 Item 13 clone 재정의는 주의해서 진행하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_03/%5B%E1%84%87%E1%85%A1%E1%86%AF%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A1%E1%84%85%E1%85%AD%5Ditem_13_clone_%E1%84%8C%E1%85%A2%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8B%E1%85%B4%E1%84%82%E1%85%B3%E1%86%AB_%E1%84%8C%E1%85%AE%E1%84%8B%E1%85%B4%E1%84%92%E1%85%A2%E1%84%89%E1%85%A5_%E1%84%8C%E1%85%B5%E1%86%AB%E1%84%92%E1%85%A2%E1%86%BC%E1%84%92%E1%85%A1%E1%84%85%E1%85%A1(%E1%84%80%E1%85%A1%E1%86%BC%E1%84%8E%E1%85%A5%E1%86%AF%E1%84%8B%E1%85%AF%E1%86%AB).pdf
[🎥 Item 13 발표 영상]: https://www.youtube.com/watch?v=VJGzz2OKP2Y

[📚 Item 14 Comparable을 구현할지 고려하라]: https://github.com/SangSangPlus/effective-java-study/blob/main/Chapter_03/%5B%EB%B0%9C%ED%91%9C%EC%9E%90%EB%A3%8C%5Ditem_14_Comparable%EC%9D%84_%EA%B5%AC%ED%98%84%ED%95%A0%EC%A7%80_%EA%B3%A0%EB%A0%A4%ED%95%98%EC%9E%90(%EA%B9%80%EB%AA%85%EC%A7%80).pdf
[🎥 Item 14 발표 영상]: https://www.youtube.com/watch?v=1plqvDAf-hg




---
<br>
