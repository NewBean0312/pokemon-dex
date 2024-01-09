## 포켓몬 도감 v1.0

### 총 900마리의 포켓몬 도감

[포켓몬 도감 바로가기](https://newbean0312.github.io/pokemon-dex/)




### 개발 기록
 - 포켓몬 JSON 적용
   - PokeApi를 사용함
 - 페이지 분리 및 PokemonList 컴포넌트 작업
 - PokemonList 디자인 작업
   - card section 처럼 나오게 디자인
 - DetailPage를 위한 Router 적용
   - Router 오류 발생
   - 버전 오류인줄 알았으나, import를 BrowserRouter로 감쌈 ▶오류 해결
 - 상세 페이지 UI 디자인
   - 특정 포켓몬은 나오지 않는 오류 발생
   - 기술 목록을 한글로 변경 시, 오류가 발생함
   - 아쉽지만, 기술 목록 기능은 제거 ▶ 오류 해결
 - 상세 페이지 포켓몬 색상 및 아이콘 적용
   - 폰트어썸을 사용하여 아이콘을 적용하였음
 - 메인 페이지 속성 표시 및 아이콘 적용
   - types가 null로 표시되어 오류 발생
   - null인 부분은 useState(0)으로 하고, 0은 배경을 흰색으로 적용함 ▶ 오류 해결