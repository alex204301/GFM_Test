# GFM Extended Syntax

## Tables
- `파이프( | )`를 사용하여 열을 표현하고 `( - )`을 사용해 줄을 표현하여 테이블을 만들 수 있다.
  
  ```
  | First Header | Second Header |
  | ------------ | ------------- |
  | content 1 | content 2 |
  | content 3 | content 4 |
  ```
  | First Header | Second Header |
  | ------------ | ------------- |
  | content 1 | content 2 |
  | content 3 | content 4 |

- 첫번째 줄에 ( - )는 길이를 맞출 필요는 없지만 맞추는게 읽기에 좋다.
- `| - |`의 개수와 한 줄에 있는 **content**의 개수는 위의 헤더와 같아야 한다. 

<br>

---

## Task Lists
- 아래와 같이 사용해 Task Lists를 표시할 수 있다.

  ```
  - [x] This is complete Task.
    - [ ] Nested Task.
  - [ ] This is incomplete Task.
  ```
  > - [x] This is complete Task.
  >   - [ ] Nested Task.
  > - [ ] This is incomplete Task.
  
<br>

---

## StrikeThrough
- `~~ + 단어 + ~~`를 사용하면 단어에 취소선을 표현할 수 있다.
  
  ```
  ~~StrikeThrough~~
  ```
  > ~~StrikeThrough~~

<br>

---

## Auto Links
- 어떤 URL이든 자동적으로 클릭가능한 링크로 만들어준다.

  ```
  https://www.naver.com/
  ```
  > https://www.naver.com/
  
<br>

---
