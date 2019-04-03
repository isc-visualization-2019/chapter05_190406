5주차 강의 내용
---

Content
---

  - 정부와 언론 속 정크차트란 무엇인가?
  - `plot`으로 base graphics 만들어보기
  - Visual Encoding이란? 차원과 시각적 요소의 관계
  - (과제 05) : [Data Visualization in R](https://www.datacamp.com/courses/data-visualization-in-r)



How to
---

실습은 작업환경을 통일하기 위해서 RStudio에서 실습파일을 바탕화면에 다운로드 가능하도록 준비했습니다.  
별도 `project`폴더를 만들 필요 없이 각 chapter마다 url을 아래 방법처럼 `console`에 입력하면 자동 설치됩니다.

콘솔창에 질문이 나오면 대답은 번호만 입력해주면 됩니다
- Is it OK to write this file here? (answer : For sure)  
- Shall we delete the ZIP file '/Users/Benjamin/Desktop/chapter3-intro-master.zip'? (answer : Yup)

```
# 최초 한번만 설치
install.packages("usethis")  

# 방법1
library(usethis) 
use_course("https://github.com/isc-visualization-2019/chapter05_190406/archive/master.zip")

# 방법2
usethis::use_course("https://github.com/isc-visualization-2019/chapter05_190406/archive/master.zip")
```
