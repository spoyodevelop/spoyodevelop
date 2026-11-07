## 김재영

React · TypeScript로 프론트엔드를 합니다.
만든 걸 배포해두고 계속 고치는 쪽을 좋아해요. 아래 둘은 지금도 돌아가고 있습니다.

<br/>

### 만든 것

<table>
<tr>
<td width="50%" valign="top">

<a href="https://estime.today">
  <img src="assets/estime.gif" width="100%" alt="아인슈타임 히트맵 화면" />
</a>

#### 🗓 [아인슈타임](https://estime.today)
`2025.07 ~` · 우아한테크코스 팀 (FE 4 · BE 4)

여러 사람이 각자 가능한 시간을 입력하면, 가장 많은 사람이 모일 수 있는 시간대를 히트맵으로 보여주는 약속 조율 서비스입니다.

8차례의 사용자 테스트를 진행하며 발견한 불편함을 하나씩 개선했습니다. 드래그할 때 버벅이는 화면은 렌더링 방식을 바꿔 개선했고, 다른 참여자의 투표도 바로 확인하고 싶다는 의견에는 SSE를 활용한 실시간 갱신으로 대응했습니다. 입력할 때 화면 전체가 불필요하게 갱신되는 문제는 상태 관리 구조를 개선해 해결했습니다.

</td>
<td width="50%" valign="top">

<a href="https://v2.umbrella.site">
  <img src="assets/umbrella.png" width="100%" alt="아 맞다 우산 예보-실측 비교 화면" />
</a>

#### ☂️ [아 맞다 우산](https://v2.umbrella.site)
`2024.03 ~` · 개인 프로젝트

기상청이 강수확률 30%라고 한 날, 실제로 비는 얼마나 왔을까요. 그게 궁금해서 매시간 예보와 실제 강수 관측을 모아 비교하는 서비스를 2년 반째 운영하고 있습니다.

처음엔 전국 17개 대표 지역뿐이라 같은 서울의 마포구와 강남구를 구분할 수 없었습니다. 252개 시군구 단위로 다시 만들어, 이제는 자기 동네를 골라서 볼 수 있습니다.

</td>
</tr>
</table>

<br/>

### 쓴 글

**[One Battle After Another: 드래그 성능 개선기](https://medium.com/tecoble/one-battle-after-another-%EB%93%9C%EB%9E%98%EA%B7%B8-%EC%84%B1%EB%8A%A5-%EA%B0%9C%EC%84%A0%EA%B8%B0-e66cec90d100)` Tecoble `
리렌더링을 줄이는 것만으로는 끝이 안 나서, 결국 DOM을 직접 건드리는 데까지 간 기록.

**[고주사율 환경에서 발생한 CSS 렌더링 문제 해결](https://frontend-fundamentals.com/debug/pages/contribute/css/css_backspace_opacity.html)**` Frontend Fundamentals `
특정 모니터에서만 깜빡이는 버그. 고치는 것보다 원인 찾는 데 시간을 다 썼습니다.

**[비동기 프로그래밍은 어쩌다 자바스크립트의 복지가 되었을까?](https://velog.io/@spoyocode/%EB%B9%84%EB%8F%99%EA%B8%B0-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D%EC%9D%80-%EC%96%B4%EC%A9%8C%EB%8B%A4-%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%9D%98-%EB%B3%B5%EC%A7%80%EA%B0%80-%EB%90%98%EC%97%88%EC%9D%84%EA%B9%8C)**` velog `
콜백에서 Promise까지, 왜 지금 이 모양이 됐는지 순서대로.

<br/>

[velog](https://velog.io/@spoyocode)
