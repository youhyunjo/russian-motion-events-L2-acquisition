러시아어 이동사건 표현 습득 실험 데이터


- 이수현, 안혁, 유현조, 하주애, 정하경. (2023). 한국어 화자의 러시아어 이동사건
  표현의 어휘화 패턴 습득 양상 연구, 러시아연구 33-1,


## 데이터

- [data/subject.tsv](data/subject.tsv): 실험 참여자 정보
- [data/item.tsv](data/item.tsv): 실험 문항 정보
- [data/response.tsv](data/response.tsv): 응답 정보
- [data/response_annotation.tsv](data/response_annotation.tsv): 응답 주석
- [data/sir_wide.tsv](data/sir_wide.tsv): subject-item-response 통합 파일 (문항별)
- [data/sir_long.tsv](data/sir_long.tsv): subject-item-response 통합 파일 (요소별)

### 실험 참여자

- [data/subject.tsv](data/subject.tsv)
- 총 76명의 실험 참여자의 정보

###### 컬럼:

| No | colname    | desc                       | value                          |
|----|------------|----------------------------|--------------------------------|
| 1  | SubjectID  | 참여자 고유번호            |                                |
| 2  | Group      | 학습자 수준 집단           | `Level1`, `Level2`, `Level3`, `Native` |
| 3  | LevelTest  | 레벨 테스트 점수           | `0-35`                         |
| 4  | Age        | 나이                       |                                |
| 5  | Gender     | 성별                       | `F` (여성), `M` (남성)         |
| 6  | MonthLearn | 학습 기간 (월)             |                                |
| 7  | MonthStay  | 러시아 지역 거주 기간 (월) |                                |


###### 학습자 통계:

<table>
  <tr>
    <td rowspan="2" valign="middle">Group</td>
    <td rowspan="2" valign="middle">N</td>
    <td colspan="3">Age (Year)</td>
    <td colspan="3">Learn (Month)</td>
    <td colspan="3">Stay (Month)</td>
  </tr>
  <tr>
    <td>M</td>
    <td>mean</td>
    <td>sd</td>
    <td>M</td>
    <td>mean</td>
    <td>sd</td>
    <td>M</td>
    <td>mean</td>
    <td>sd</td>
  </tr>
  <tr bgcolor="#e6e6e6">
    <td>Level1</td>
    <td>21</td>
    <td>21.0</td>
    <td>22.9</td>
    <td>4.7</td>
    <td>20.0</td>
    <td>34.0</td>
    <td>32.9</td>
    <td>0.0</td>
    <td>3.23</td>
    <td>13.1</td>
  </tr>
  <tr>
    <td>F</td>
    <td>13</td>
    <td>20.0</td>
    <td>22.2</td>
    <td>4.2</td>
    <td>22.0</td>
    <td>31.2</td>
    <td>21.0</td>
    <td>0.0</td>
    <td>0.52</td>
    <td>1.6</td>
  </tr>
  <tr>
    <td>M</td>
    <td>8</td>
    <td>22.5</td>
    <td>24.1</td>
    <td>5.4</td>
    <td>22.5</td>
    <td>38.6</td>
    <td>48.0</td>
    <td>0.0</td>
    <td>7.62</td>
    <td>21.2</td>
  </tr>
  <tr bgcolor="#e6e6e6">
    <td>Level2</td>
    <td>23</td>
    <td>26.0</td>
    <td>26.8</td>
    <td>5.5</td>
    <td>60.0</td>
    <td>71.1</td>
    <td>53.0</td>
    <td>0.0</td>
    <td>6.30</td>
    <td>10.6</td>
  </tr>
  <tr>
    <td>F</td>
    <td>14</td>
    <td>29.0</td>
    <td>28.3</td>
    <td>5.9</td>
    <td>84.0</td>
    <td>90.0</td>
    <td>59.0</td>
    <td>6.5</td>
    <td>8.64</td>
    <td>12.6</td>
  </tr>
  <tr>
    <td>M</td>
    <td>9</td>
    <td>24.0</td>
    <td>24.6</td>
    <td>4.2</td>
    <td>36.0</td>
    <td>41.8</td>
    <td>21.8</td>
    <td>0.0</td>
    <td>2.67</td>
    <td>5.3</td>
  </tr>
  <tr bgcolor="#e6e6e6">
    <td>Level3</td>
    <td>22</td>
    <td>41.5</td>
    <td>39.8</td>
    <td>9.4</td>
    <td>155.0</td>
    <td>189.0</td>
    <td>100.1</td>
    <td>54.0</td>
    <td>55.50</td>
    <td>32.4</td>
  </tr>
  <tr>
    <td>F</td>
    <td>13</td>
    <td>44.0</td>
    <td>40.6</td>
    <td>9.9</td>
    <td>120.0</td>
    <td>187.0</td>
    <td>100.7</td>
    <td>60.0</td>
    <td>58.62</td>
    <td>32.0</td>
  </tr>
  <tr>
    <td>M</td>
    <td>9</td>
    <td>38.0</td>
    <td>38.7</td>
    <td>8.9</td>
    <td>204.0</td>
    <td>191.8</td>
    <td>105.1</td>
    <td>48.0</td>
    <td>51.00</td>
    <td>34.3</td>
  </tr>
  <tr bgcolor="#e6e6e6"><td>Total</td>
    <td>66</td>
    <td>27.5</td>
    <td>29.9</td>
    <td>9.9</td>
    <td>66.0</td>
    <td>98.6</td>
    <td>94.3</td>
    <td>3.5</td>
    <td>21.72</td>
    <td>31.8</td>
  </tr>
  <tr>
    <td>F</td>
    <td>40</td>
    <td>28.5</td>
    <td>30.3</td>
    <td>10.3</td>
    <td>78</td>
    <td>102.4</td>
    <td>92.5</td>
    <td>6.0</td>
    <td>22.24</td>
    <td>32.1</td>
  </tr>
  <tr>
    <td>M</td>
    <td>26</td>
    <td>26.5</td>
    <td>29.3</td>
    <td>9.4</td>
    <td>42</td>
    <td>92.7</td>
    <td>98.7</td>
    <td>0.5</td>
    <td>20.92</td>
    <td>31.8</td>
  </tr>
  <tr bgcolor="#e6e6e6">
    <td>Native</td>
    <td>10</td>
    <td>36.0</td>
    <td>38.4</td>
    <td>9.2</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>F</td>
    <td>7</td>
    <td>45.0</td>
    <td>40.9</td>
    <td>10.0</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>M</td>
    <td>3</td>
    <td>34.0</td>
    <td>32.7</td>
    <td>2.3</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>





### 실험 문항

- [data/item.tsv](data/item.tsv)
- 전체 47 문항. 실험 문항은 38개. 채움(filler) 문항 9개. 

###### 컬럼:

| colname        | desc          | value                                         |
|----------------|---------------|-----------------------------------------------|
| ItemID         | 문항 고유번호 | `t001`, ..., `t047`                           |
| ItemType       | 문항 유형     | `DirectionItem`, `PathItem`, `filler`         |
| Path           | 경로          | `-`, `pri`, `v`, `pod`, ...                   |
| Manner         | 양태          | `crawl`, `fly`, `ride`, `run`, `swim`, `walk` |
| Direction      | 방향          | `-`, `uni`, `multi`                           |
| Aspect         | 상            | `impf`, `pf`                                  |
| ExpectedAnswer | 정답          |                                               |
| ItemNo         | 문항 번호     |                                               |
| ItemText       | 문항 내용     |                                               |


###### 문항 유형별 개수:

- 전체 38 문항은 양태에 따라 `crawl` 1 문항, `fly` 8 문항, `ride` 5 문항,
  `run` 6 문항, `swim` 8 문항, `walk` 10 문항.
- 방향 유형(`DirectionItem`) 19 문항, 경로 유형(`PathItem`) 19 문항.
- 방향 유형 19 문항 중 일방향(`uni`, unidirectional) 12 문항, 다방향(`multi`, multidirectional) 7 문항.
- 경로 유형 중 경로 접두사 `pri`와 `v` 각 5 문항, `pod` 3 문항, `ob`, `ot`, `pere`, `pro`, `u`, `vy` 각 1 문항.

| Manner | Direciton           ||| Path                                         |||||||||| Sum |
|--------|-----------|-----|-----|------|----|------|-----|-----|-----|---|---|----|-----|-----|
|        | multi     | uni | Sum | ob   | ot | pere | pod | pri | pro | u | v | vy | Sum |     |
| crawl  |           | 1   | 1   |      |    |      |     |     |     |   |   |    |     | 1   |
| fly    | 2         | 3   | 5   |      |    |      | 1   | 1   |     |   | 1 |    | 3   | 8   |
| ride   | 1         | 2   | 3   |      |    |      |     | 1   |     |   | 1 |    | 2   | 5   |
| run    | 1         | 2   | 3   |      |    |      | 1   | 1   |     |   | 1 |    | 3   | 6   |
| swim   | 2         | 3   | 5   |      |    |      | 1   | 1   |     |   | 1 |    | 3   | 8   |
| walk   | 1         | 1   | 2   | 1    | 1  | 1    |     | 1   | 1   | 1 | 1 | 1  | 8   | 10  |
| Sum    | 7         | 12  | 19  | 1    | 1  | 1    | 3   | 5   | 1   | 1 | 5 | 1  | 19  | 38  |


### 응답

- [data/response.tsv](data/response.tsv)
- 총 3572건의 응답 정보. 실험 참여자 76명 ✕ 전체 문항 47개.

###### 컬럼:

| colname      | desc             | value                          |
|--------------|------------------|--------------------------------|
| No           | 일련번호         |                               |
| Group        | 학습자 수준 집단 | `Level1`, `Level2`, `Level3`, `Native` |
| SubjectID    | 참여자 고유번호  |                                |
| ItemID       | 문항 고유번호    |                                |
| ResponseText | 응답 내용        | 실험 참여자가 응답으로 입력한 텍스트    |
| ItemNo       | 문항 번호        |                                |
| ItemText     | 문항 내용        |                                |


### 응답 주석

- [data/response_annotation.tsv](data/response_annotation.tsv)
- 643가지 응답 유형을 분류하고 주석

###### 컬럼:

| colname        | desc      | value                                                 |
|----------------|-----------|-------------------------------------------------------|
| freq           | 빈도      | 0-200                                                      |
| ResponseText   | 응답 내용 | 실험 참여자가 응답으로 입력한 텍스트                  |
| ErrorType      | 오류 유형 | `SpellError`, `Error`                                 |
| ResponseStatus | 응답 상태 | `MotionVerb`, `OtherVerb`, `Invalid`, `Empty`         |
| POS            | 품사      | `-`, `NOUN`, `VERB`                                   |
| Normalized     | 정규화    | 응답을 사전 표제어형으로 정규화                       |
| PrefixRu       | 접두사    | при, в, под, по, про, ...                             |
| RootRu         | 어근      | идит, ходить, ехать, лететь, бежать, ...              |
| Path           | 경로      | `-`, `X`, `-pri`, `v`, `pod`, `pod`, `po`, `pro`, ... |
| Manner         | 양태      | `x`, `walk`, `ride`, `fly`, `swim`, `run`, `crawl`    |
| Direction      | 방향      | `-`, `x`, `uni`, `multi`                              |
| Aspect         | 상        | `x`, `impf`, `pf`                                     |
| Tense          | 시제      | `x`, `pres`, `past`, `futr`, `inf`                    |


### 통합 파일 (문항별)

- [data/sir_wide.tsv](data/sir_wide.tsv)
- 참여자-문항-응답(subject-item-response) 통합 데이터.
- 총 3572건. 실험 참여자 76명의 47개 문항에 대한 응답.




###### 컬럼:


| colname           | desc                      | value                                                 |
|-------------------|---------------------------|-------------------------------------------------------|
| No                | 일련번호                  |                                                       |
| Group             | 학습자 수준 그룹          | `Level1`, `Level2`, `Level3`, `Native`                |
| SubjectID         | 참여자 고유번호           |                                                       |
| LevelTest         | 레벨 테스트 점수          | `0-35`                                                |
| Age               | 나이                      |                                                       |
| Gender            | 성별                      | `F` (여성), `M` (남성)                                |
| MonthLearn        | 학습기간 (월)             |                                                       |
| MonthStay         | 러시아 지역 거주기간 (월) |                                                       |
| ItemID            | 문항 고유번호             |                                                       |
| ExpectedAnswer    | 정답                      |                                                       |
| ItemType          | 문항 유형                 | `DirectionItem`, `PathItem`, `filler`                 |
| ExpectedPath      | 정답 경로                 | `-`, `pri`, `v`, `pod`, ...                           |
| ExpectedManner    | 정답 양태                 | `crawl`, `fly`, `ride`, `run`, `swim`, `walk`         |
| ExpectedDirection | 정답 방향                 | `-`, `uni`, `multi`                                   |
| ExpectedAspect    | 정답 상                   | `impf`, `pf`                                          |
| ResponseText      | 응답 내용                 | 실험 참여자가 응답으로 입력한 텍스트                  |
| ResponseStatus    | 응답 상태                 | `MotionVerb`, `OtherVerb`, `Invalid`, `Empty`         |
| ResponsePath      | 경로                      | `-`, `X`, `-pri`, `v`, `pod`, `pod`, `po`, `pro`, ... |
| ResponseManner    | 양태                      | `x`, `walk`, `ride`, `fly`, `swim`, `run`, `crawl`    |
| ResponseDirection | 방향                      | `-`, `x`, `uni`, `multi`                              |
| ResponseAspect    | 상                        | `x`, `impf`, `pf`                                     |
| PathY             | 경로 점수                 | `0` (오답), `1` (정답)                                |
| MannerY           | 양태 점수                 | `0` (오답), `1` (정답)                                |
| DirectionY        | 방향 점수                 | `0` (오답), `1` (정답)                                |
| AspectY           | 상 점수                   | `0` (오답), `1` (정답)                                |




### 통합 파일 (요소별)

- [data/sir_long.tsv](data/sir_long.tsv)
- 참여자-문항-응답(subject-item-response) 통합 데이터.
- 총 14288건. 한 문항에 대한 응답을 양태, 방향, 경로, 상 요소별로 분리한 데이터.

###### 컬럼:

| colname           | desc                      | value                                         |
|-------------------|---------------------------|-----------------------------------------------|
| No                | 일련번호                  |                                               |
| Group             | 학습자 수준 그룹          | `Level1`, `Level2`, `Level3`, `Native`        |
| SubjectID         | 참여자 고유번호           |                                               |
| LevelTest         | 레벨 테스트 점수          | `0-35`                                        |
| Age               | 나이                      |                                               |
| Gender            | 성별                      | `F` (여성), `M` (남성)                        |
| MonthLearn        | 학습기간 (월)             |                                               |
| MonthStay         | 러시아 지역 거주기간 (월) |                                               |
| ItemID            | 문항 고유번호             |                                               |
| ExpectedAnswer    | 정답                      |                                               |
| ItemType          | 문항 유형                 | `DirectionItem`, `PathItem`, `filler`         |
| ExpectedPath      | 정답 경로                 | `-`, `pri`, `v`, `pod`, ...                   |
| ExpectedManner    | 정답 양태                 | `crawl`, `fly`, `ride`, `run`, `swim`, `walk` |
| ExpectedDirection | 정답 방향                 | `-`, `uni`, `multi`                           |
| ExpectedAspect    | 정답 상                   | `impf`, `pf`                                  |
| ResponseText      | 응답 내용                 | 실험 참여자가 응답으로 입력한 텍스트          |
| Element           | 의미 요소                 | `manner`, `direction`, `path`, `aspect`       |
| ResponseVal       | 응답 값                   | 응답 양태, 방향, 경로, 상                     |
| Y                 | 점수                      | `0` (오답), `1` (정답)                        |

