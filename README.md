# gaussian-process-seminar
2026 Winter seminar on ["Bayesian Optimization Book" by Roman Garnett](https://bayesoptbook.com/)

## 일정표

방학중엔 매주 목요일 저녁 5시에 진행됩니다.

| 일자       | 내용                                                     | 담당자 |
| -------- | ------------------------------------------------------ | --- |
| 1/22 | Ch2. Gaussian Process (~ 2.4)                  | 박성우 |
| 1/29 | Ch2. Gaussian Process (2.5 ~)        | 최윤서 |
| 2/5 | Ch3. Modeling with Gaussian Process                | 고명금 |
| 2/12 | Ch4. Model assessment, Selection, and Averaging | 고경태 |
| 2/19 | Ch5. Decision Theory for optimization    | 김지광 |
| 2/26 | Ch6. Utility functions for optimization + Ch7. Common Bayesian Optimiation Policies (~ 7.5) | 윤다연 |
| 3/5 | Ch7. Common Bayesian Optimiation Policies (7.6 ~ )   | 이혜림 |

> 추후 진도 사항에 따라 일정이 변경될 수 있습니다.

## 세미나 규칙

- (필수) **매주 내용 읽기**
- (필수) **세미나 주차 화요일까지** 주차 [Discussion](https://github.com/snuuq/gaussian-process-seminar/discussions)에 질문 한개 이상 작성
- 주기적으로 Discussion 에서 토의하기
- 해당 주차 담당자의 경우 **요약 발표 자료 작성**

## 사용법

### 1. Repository Clone

```bash
git clone https://github.com/snuuq/gaussian-process-seminar.git
cd gaussian-process-seminar
```

### 2. 해당 챕터 폴더 생성

```bash
mkdir ch02
```

챕터 폴더 포멧: `chXX` (XX는 챕터 번호)

### 3. 발표자료 작성 후 업로드

```bash
# 1. 작업 시작 전에 최신 상태로 업데이트
git pull origin main

# 2. 파일 생성 및 자료 작성
touch ch02/main.tex
# OR
code .

# 3. 커밋 & 푸시
git add .
git commit -m "feat: ch02 presentation upload"
git push origin main
```

> 어렵다면 [Github Desktop](https://github.com/apps/desktop?locale=ko-KR)을 이용하거나 Github Web의 'Add file' 기능을 이용하세요.

## 참가자
- [김지광](https://github.com/wlrhkd1230)
- [고명금]()
- [고경태]()
- [박성우](https://github.com/cos18)
- [변희준](https://github.com/ryanb01)
- [윤다연](https://github.com/Dayeon-Yoon)
- [이혜림](https://github.com/2hyerim)
- [조건우]()
- [최윤서](https://github.com/cys0220)

