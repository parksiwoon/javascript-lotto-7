# javascript-lotto-precourse

# Lotto Game

## 프로젝트 개요

이 프로젝트는 사용자로부터 로또 구입 금액을 입력받고, 입력된 금액에 맞춰 로또를 발행하는 간단한 로또 발매기입니다. 사용자는 로또 당첨 번호를 입력하고, 구매한 로또의 당첨 여부와 수익률을 확인할 수 있습니다.

## 기능 목록

### 1. 사용자 입력 기능

- **구입 금액 입력**: 사용자가 로또 구입 금액을 입력받고 유효성 검사를 수행합니다.
- **당첨 번호 입력**: 사용자로부터 6개의 당첨 번호를 입력받고, 각 번호의 유효성을 확인합니다.
- **보너스 번호 입력**: 보너스 번호를 입력받고 당첨 번호와 중복되지 않는지 확인합니다.

### 2. 로또 생성 기능

- **로또 번호 발행**: 구입 금액에 맞춰 로또 개수를 계산하고, 각 로또마다 중복되지 않는 6개의 번호를 생성합니다.
- **번호 정렬**: 발행된 로또 번호는 오름차순으로 정렬되어 출력됩니다.

### 3. 당첨 결과 계산 기능

- **번호 일치 개수 확인**: 사용자 구매 로또와 당첨 번호를 비교하여 일치하는 번호 개수를 확인합니다.
- **보너스 번호 확인**: 일치하는 번호가 5개인 경우 보너스 번호와 일치하는지 확인하여 2등 여부를 판단합니다.
- **당첨 결과 집계**: 각 등수별 당첨 개수를 집계하여 저장합니다.

### 4. 결과 출력 기능

- **로또 번호 출력**: 구매한 로또 개수와 각각의 번호를 출력합니다.
- **당첨 내역 출력**: 3등부터 1등까지 각 등수별 당첨 개수와 상금을 출력합니다.
- **수익률 계산 및 출력**: 총 수익률을 계산하여 소수점 둘째 자리에서 반올림하여 출력합니다.

### 5. 예외 처리 기능

- **구입 금액 유효성 검사**: 1,000원 단위가 아닌 금액을 입력할 경우 오류 메시지를 출력합니다.
- **로또 번호 유효성 검사**: 입력된 로또 번호가 1~45 범위에 있는지 확인하고, 중복된 번호가 없는지 검사합니다.
- **에러 메시지 출력**: 모든 오류는 "[ERROR]"로 시작하는 메시지를 통해 사용자에게 안내합니다.
