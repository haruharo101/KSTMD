# KSTMD
Korean-Spam-Text-Message-Dataset

본 데이터셋은 주식, 로또 등과 같은 분야의 스팸 문자 데이터와 더불어 일반적인 문자 메세지를 모아둔 데이터셋으로, 자유롭게 사용하시기 바랍니다.

## 데이터셋 구성

### key
해당 데이터셋은 스팸 문자와 스팸 문자가 아닌 문자들이 데이터화 되어 있습니다. 참고 바랍니다.
- `Message` : 한국어, 영어, 특수기호 등으로 구성된 raw 메세지입니다.
- `Target` : 그 메세지가 속한 분류입니다. `1`은 주식, 코인 관련 문자, `2`는 로또 관련 문자를 `3`은 도박, `4`는 부업, `5`는 메세지 내용만으로는 분류를 알 수 없는 스팸 문자를 의미합니다. `6`은 스팸 문자가 아님을 의미합니다.

### 특수값
- `[LINK]` : 외부사이트로 연결되는 링크를 대체하여 표현한 값입니다.
- `[PHONE]` : 전화번호를 대체하여 표현한 값입니다.
