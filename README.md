# :chains: Minecraft Precision Chain Climber

마인크래프트의 **사슬(Chain)** 블록을 사다리처럼 이용할 수 있게 해주는 혁신적인 물리 제어 스크립트입니다.

## :sparkles: Key Features
* **정밀 충돌 감지:** 플레이어 주변 반경 1블록 내의 사슬을 감지하여 자연스러운 상호작용을 보장합니다.
* **지능형 이동 제어:** * **상승:** 위를 보고 이동/점프 시 부드럽게 상승
    * **정지:** 쉬프트(Sneak) 키를 눌러 공중 매달리기 가능
    * **하강:** 아래를 보고 이동 시 안전하게 하강
* **안전 시스템:** 사슬 근처에서 추락할 경우 **낙하 데미지를 자동으로 무효화**합니다.

## :tools: Technical Insights
* **Vector Physics:** 마인크래프트의 기본 중력을 이기기 위해 `velocity`와 `vector` 연산을 활용했습니다.
* **Dynamic Radius Check:** 정지된 좌표 체크가 아닌 동적 반경 체크를 통해 UX(사용자 경험)를 극대화했습니다.

## :rocket: How to use
1. 서버에 `Skript` 플러그인을 설치합니다.
2. `plugins/Skript/scripts` 폴더에 이 파일을 넣습니다.
3. `/sk reload PrecisionChainClimber`를 입력합니다.
