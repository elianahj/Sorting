# Sorting_201902954한현진
## 정렬 알고리즘 종류 
### 버블정렬
> 이웃하는 숫자를 비교하여 작은 수를 앞쪽으로 이동하는 과정을 반복하여 정렬   

> 시간복잡도 = **O(n^2)**   

![1](https://user-images.githubusercontent.com/80517119/166942093-30ed662e-dd8e-4b92-ad5a-c7d3231ed18e.JPG)

<img src = "https://user-images.githubusercontent.com/80517119/166620862-80ce91ef-d8cf-492b-bfdf-4db5759a4fd1.png" width="70%"></img>


### 선택정렬
> 입력 배열 전체에서 최솟값을 선택하여 배열의 0번 원소와 자리를 바꾸고, 그 다음엔 0번 원소를 제외한 나머   지 원소에서 최솟값을 선택하여 배열의 1번 원소와 자리를 바꿈   
  
> => 이러한 방식으로 마지막에 2개의 원소 중 최솟값을 선택하여 자리를 바꿈으로써 오름차순의 정렬을 마침   

> 시간복잡도 = **O(n^2)**   

![2](https://user-images.githubusercontent.com/80517119/166945206-f6737560-35fe-478e-87ee-2964f2fae21d.JPG)

<img src = "https://user-images.githubusercontent.com/80517119/166620896-6146e952-4727-467f-bb84-982397360cf7.png" width="70%"></img>
### 삽입정렬
> 배열을 정렬된 부분(앞부분)과 정렬 안 된 부분(뒷부분)으로 나누고, 정렬 안 된 부분의 가장 왼쪽 원소를 정렬된 부분의 적절한 위치에 삽입하여 정렬되도록 하는 과정을 반복    

> **평균** 시간복잡도 = **O(n^2)**   

> **최선** = 이미 정렬되어 있을 경우 시간복잡도 = **O(n)**    

![3](https://user-images.githubusercontent.com/80517119/166945336-93313d09-0ef6-4312-affe-a5a3f8108d75.JPG)

<img src = "https://user-images.githubusercontent.com/80517119/166620887-998528a1-ebd3-486f-b740-022381f3f802.png" width="70%"></img>


### 퀵정렬
> 퀵정렬은 3주차 과제로 제출했던 소스코드를 사용했습니다.

https://elianahj.github.io/QuickSort/   

> 시간복잡도 = **O(nlogn)**   

<img src = "https://user-images.githubusercontent.com/80517119/166620902-a65925e0-50bc-454d-ab95-8cbf81b54bdc.png" width="70%"></img>

#### 대체로 정렬 알고리즘은 정렬된 데이터 > 랜덤 데이터 > 역 정렬 데이터 순으로 성능이 좋습니다
> 특히 역 정렬 데이터를 정렬할 때, 정렬 데이터와 랜덤 데이터를 정렬하는데 걸리는 시간의 약 2~4배의 시간이 걸립니다. 

## 데이터 종류 별로 정렬 알고리즘 비교
### 정렬 데이터


<img src = "https://user-images.githubusercontent.com/80517119/166620926-1992a68e-f2f3-4dbc-a4ef-8f0e3f429fef.png" width="70%"></img>
> 데이터의 수가 적어서 큰 차이는 나지 않으나, 퀵정렬과 삽입정렬의 성능이 다른 정렬 알고리즘보다 성능이 좋은 것을 볼 수 있습니다.
### 랜덤 데이터

<img src = "https://user-images.githubusercontent.com/80517119/166620941-38fac4a3-135d-492a-8aea-ec8b6f42cd69.png" width="70%"></img>
> 정렬 데이터와 비슷한 결과를 보입니다. 퀵 > 삽입 > 선택 > 버블 정렬 순으로 성능이 좋습니다.
### 역 정렬 데이터

<img src = "https://user-images.githubusercontent.com/80517119/166620952-e12834dd-3790-4c2f-be30-da9219b622ed.png" width="70%"></img>
> 버블정렬과 선택정렬의 소요시간이 크게 늘어났습니다. 역시 퀵 > 삽입 > 선택 > 버블 정렬 순으로 성능이 좋습니다.
