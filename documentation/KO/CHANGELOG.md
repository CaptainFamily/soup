## v1.1

### 추가된 점

- 쿠키는 `Cookies` map 또는 `Cookie()` 함수를 통해 HTTP 요청에 쿠키를 추가할 수 있습니다.
- `GetWithClient()` 함수는 사용자 지정 HTTP 클라이언트와 함께 요청을 보낼 수 있는 기능 제공합니다.
- `FindStrict()` 함수는 제공된 속성의 정확한 일치 값을 가진 언급된 태그의 첫 번째 인스턴스 찾습니다. (이전의 `Find()`)
- `FindAllStrict()` 함수는 속성의 정확한 일치 값을 가진 언급된 태그의 모든 인스턴스 찾습니다. (이전의 `FindAll()`)

## 변경된 점

- `Find()` 함수는 이제 제공된 속성의 일치하는 값을 가진 언급된 태그의 첫 번째 인스턴스를 찾습니다.
- `FindAll()` 함수는 이제 제공된 속성의 일치하는 값을 가진 언급된 태그의 모든 인스턴스를 찾습니다.

---