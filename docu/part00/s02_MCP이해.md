# S02. MCP 이해하기

### 비개발자 관점에서 MCP
- MCP라 말하는 것은 MCP 서버를 의미
- 엄밀히 MCP는 프로토콜이지, MCP 서버를 의미하지는 않지만 편의상 MCP라고 부른다.
- MCP를 이해하기 위해, 가장 적절한 비유중 하나는 브라우저의 `확장 프로그램`이다.

### MCP 설치 준비하기
> Desktop COmmander MCP 설치, 다음은 설치조건을 갖춰야 한다.
- 스미더리 개인 API 설정하기 : [서미더리](https://smithery.ai/)
- Node.js 설치하기
- MCP 설치 명령어 복사하여 `명령 프롬프트`에 붙여넣기
- 클로드 개발자 모드 ON

![smithery.ai 접속](./img/s02_smithery_ai_접속.png)

<br/>

❶ 서미더리 사이트 접속
- 서비더리는 클로드에 설치할 수 있는 수많은 MCP 마켓플레이스 이다. 
<br/>

❷  회원가입 후 로그인
<br/>

❸ ①[프로필 사진] ➡︎ ②[Profiles & API Keys] 를 클릭해 MCP 설치 전에 개인 API를 셋팅한다. 
  - 클로드에 MCP를 설치하여 사용하려면 반드시 이 과정을 수행해야 한다.
  - 왼쪽메뉴에서 ③[API Keys]를 선택한 후 ④[+Create API KEY]를 눌러 개인 API를 활성화 한다.
  - 혹시라도 유출되었다 생각되면 [휴지통]을 눌러 지워라. 
  - 아무튼 이 세팅이 끝나면 MCP를 설치할 수 있게 된다. 
<br/>

❹ 다시 Desktop Commander로 돌아간다. 
  - 로그인하라고 표시가 나왔던 부분에 'Installation' 이라는 안내가 보이고 [Auto]탭에 [Claude Desktop]이 선택되어 있을것이다.
  - 만약 선택되어 있지 않다면, 설치명령어를 [copy]를 눌러 복사한다. 
  - 바로 이 명령어를 실행하기 위해 Node.js를 설치한다. 
<br/>

❺ 이제 Node.js를 설치한다.
  - Node.js: [nodejs.org/ko](https://nodejs.org/ko)
<br/>

❻ Node.js 설치를 완료하면 MCP 설치 명령어를 수행할 수 있다. 
  - 과정❹에서 복사한 설치 명령어를 실행하려면 윈도우 검색에서 `명령 프롬프트` 를 검색하여 실행한다.
  - 명령 프롬프트는 윈도우에서 사용하는 명령어 입력기 이다. 
<br/>

❼ 명령 프롬프트를 실행했으면 명령어를 `Ctrl+V`로 붙여넣고, `Enter`를 눌러 실행한다. 
  - 중간에 나오는 질문은 y를 입력하고 `Enter`를 누른다. 
  - 그러면 자동으로 클로드를 재실행하며 Desktop Commander MCP를 클로드에 적용한다. 
<br/>

❽  이제 클로드에서 왼쪽 위에 있는 [햄버거] 버턴을 누르고 [도움말→개발자모드활성화]를 누른다. <br/>
   그러면 경고 메시지가 나오는데 [활성화]를 누른다. 
<br/>

❾ 그러면 클로드가 다시 실행된다.  `⇆` 버튼을 누르면 설치된 MCP 목록을 확인할 수 있다.
  - 클로드에서 MCP를 활용할 준비가 끝났다.   
<br/>


### Tip. MCP 트랜드는 PulseMCP에서, 설치는 서미더리에서!
- 서미더리는 MCP를 찾고 설치할 수 있는 최고의 웹사이트지만, 어떤 MCP가 유용한지, 무엇이 대세인지 파악하기는 어렵다. 
- 스미더리의 Popular 부문에서 가장 많은 사용자의 선택을 받은 MCP를 확인할 수 있지만 왜 여기에 이 MCP가 있는지는 알기 어렵다. 
- **PulseMCP**는 이런 답답함을 해소해준다.
  - [pulsemcp.com](https://www.pulsemcp.com/) 사으트에 접속하면 Anthropic Reference 부문, Official Providers 부문, Community Service 부문이 있다.
  - 스미더리에서 MCP를 고를 때는 이것이 동작하는 MCP인지, 제대로 된 결과를 내주는 MCP인지 알 수 없다. 
  - 그럴때 PulseMCP의 Anthropic Reference 부문 MCP를 살펴보거나, 규모 있는 개발사의 공식 MCP가 있는 Official Provideers 부문을 살펴보면 좋다. 
- `[Note]` Anthropic은 클로드와 MCP 체계를 만든 회사이다. 
- Community Servers 부문은 사용자가 만든 MCP이다. 
  - 종류가 다양하고 인지도가 낮은 프로그램의 MCP도 있어 유용하지만, 
  - 기대한 결과가 나오지 않거나 제대로 운영되지 않아 동작하지 않을 수도 있다. 

❿

