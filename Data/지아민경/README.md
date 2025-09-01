# DATA DESCRIPTION

## 1. Statlog (Australian Credit Approval)
- **목적**: 개인의 신용카드나 대출 신청을 금융기관이 승인할지 거절할지 예측하는 문제  
- **Features**: 나이, 고용 상태, 주택 소유 여부, 은행 잔고, 직업, 성별 등 총 14개 (숫자형+범주형 혼합)  
- **y 값**: `1`은 승인, `0`은 거절  

## 2. Haberman's Survival
- **목적**: 유방암 수술 환자가 수술 후 5년 이상 생존했는지를 예측  
- **Features**: 나이, 수술 연도, 림프절 수 (총 3개)  
- **y 값**: `1`은 5년 이상 생존, `2`는 5년 미만 생존  

## 3. Ionosphere
- **목적**: 전자기파를 쏴서 대기에서 수신된 데이터를 분석해 유의미한 반사체 여부를 예측  
- **Features**: 전파 신호의 세기 및 위상 정보 총 34개 (숫자형)  
- **y 값**: `'g'`는 유의미한 반사, `'b'`는 무의미  

## 4. Sonar (Mines vs. Rocks)
- **목적**: 소나 신호를 기반으로 해당 물체가 지뢰인지 암석인지 분류  
- **Features**: 60개 주파수 대역의 반사 에너지 값 (실수형)  
- **y 값**: `'R'`은 암석(Rock), `'M'`은 지뢰(Mine)  

## 5. Breast Cancer Wisconsin (Diagnostic)
- **목적**: 세포 핵의 특성을 기반으로 유방암이 악성인지 양성인지 분류  
- **Features**: 세포의 크기, 모양, 질감, 경계 등 총 30개  
- **y 값**: `'M'`은 악성, `'B'`는 양성  

## 6. Glass Identification
- **목적**: 유리의 화학 성분을 분석하여 유리의 용도/종류를 식별  
- **Features**: Na, Mg, Al, Si, K, Ca 등 총 9개 화학 성분 농도  
- **y 값**: `1` ~ `7`의 정수 클래스 (유리 종류)  

## 7. Iris
- **목적**: 붓꽃의 측정값을 통해 종(species)을 분류  
- **Features**: 꽃잎 길이/너비, 꽃받침 길이/너비 (총 4개)  
- **y 값**: `Setosa`, `Versicolor`, `Virginica`  

## 8. Heart Disease
- **목적**: 환자의 임상 데이터를 기반으로 심장질환 여부 예측  
- **Features**: 나이, 성별, 흉통 유형, 혈압, 혈당, 심전도, 심박수 등 총 13개  
- **y 값**: `0`은 질병 없음, `1~4`는 심장병 존재 (위험 단계)  

## 9. BUPA Liver Disorders
- **목적**: 환자의 간 질환 여부를 예측  
- **Features**: 혈액 검사 수치, 간 수치, 음주량 등 총 6개  
- **y 값**: `1`은 간 질환 있음, `2`는 없음  

## 10. Vehicle
- **목적**: 차량의 이미지를 기반으로 차량 종류 분류  
- **Features**: 차량 외형의 기하학적 특성 (컴퓨터 비전 추출값) 총 18개  
- **y 값**: 4가지 차량 클래스 (버스, 승용차, 밴, 사륜구동 등)  

## 11. Balance Scale
- **목적**: 저울 양쪽의 무게와 거리를 기반으로 저울 상태 예측  
- **Features**: 좌측 무게, 좌측 거리, 우측 무게, 우측 거리 (총 4개)  
- **y 값**: `L`(왼쪽 기움), `R`(오른쪽 기움), `B`(균형)  

## 12. Diabetes (Pima Indians Diabetes)
- **목적**: 임신부의 건강 지표를 기반으로 당뇨병 발병 여부 예측  
- **Features**: 임신 횟수, 혈당, 혈압, 피부 두께, 인슐린 수치, BMI, 나이 등 총 8개  
- **y 값**: `1`은 당뇨병 있음, `0`은 없음

## 코드 링크
파일 별로 코드 구성이 조금씩 다르고, 개인이 테스트 해본 코드도 많으므로 필요한 코드만 재구성하여 사용하시면 좋을 거 같습니다. 

**M추정기 SVM 코드**: https://drive.google.com/drive/folders/1WqAg7BMoC2KAwOTbSpLMcQACiDU2RjeG?usp=sharing
**Fuzzy membership SVM 코드**: https://drive.google.com/drive/folders/163t73PZTa-Nj3SgrztEqhI6ePJghW-RI?usp=sharing
