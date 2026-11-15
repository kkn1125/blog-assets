# 혼자 만든 2D 게임, 엔진에서 콘텐츠 에디터까지

아티클 `/solo-2d-game-development-retrospective/`에서 사용할 스크린샷 40장이다.

- `initial/`: 초기 2D 게임 10장.
- `advanced/`: 고도화된 게임과 World Studio 30장.
- 원본 PNG를 재압축·크기 변경 없이 보존했다. 파일 끝의 10자리 문자열은 원본 SHA-256 일부다.
- Blog Writer의 이미지 에셋에서 폴더를 선택하거나 `village`, `combat`, `quest`, `inventory`, `world-studio` 등으로 검색한다. 이미지를 누르면 공개 URL이 복사된다.
- 아래 Markdown을 복사해서 아티클에 붙여 넣을 수 있다.

## 초기 버전 · 맵과 월드

| 이미지 | 본문에 붙여 넣을 Markdown |
| --- | --- |
| [초기 버전 마을 맵 진입](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/world/01-village-map-transition-2a0853487f.png) | `![초기 버전 마을 맵 진입](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/world/01-village-map-transition-2a0853487f.png)` |
| [초기 버전 필드와 몬스터 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/world/02-field-overview-0780cc0846.png) | `![초기 버전 필드와 몬스터 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/world/02-field-overview-0780cc0846.png)` |
| [초기 버전 건물과 캐릭터 깊이 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/world/03-building-depth-order-332ff012c1.png) | `![초기 버전 건물과 캐릭터 깊이 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/world/03-building-depth-order-332ff012c1.png)` |
| [초기 버전 마을의 여러 캐릭터](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/world/04-village-multiplayer-d83f6f2ec2.png) | `![초기 버전 마을의 여러 캐릭터](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/world/04-village-multiplayer-d83f6f2ec2.png)` |

## 초기 버전 · 전투

| 이미지 | 본문에 붙여 넣을 Markdown |
| --- | --- |
| [초기 버전 슬라임 전투](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/combat/01-slime-battle-dd0421f450.png) | `![초기 버전 슬라임 전투](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/combat/01-slime-battle-dd0421f450.png)` |
| [초기 버전 레벨업과 피해량 표시](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/combat/02-level-up-cc8d54a773.png) | `![초기 버전 레벨업과 피해량 표시](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/combat/02-level-up-cc8d54a773.png)` |

## 초기 버전 · 인벤토리·장비 UI

| 이미지 | 본문에 붙여 넣을 Markdown |
| --- | --- |
| [초기 버전 인벤토리와 소지금](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/ui/01-inventory-e892bc1d06.png) | `![초기 버전 인벤토리와 소지금](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/ui/01-inventory-e892bc1d06.png)` |
| [초기 버전 장비 슬롯과 능력치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/ui/02-equipment-and-stats-83884c0e2f.png) | `![초기 버전 장비 슬롯과 능력치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/ui/02-equipment-and-stats-83884c0e2f.png)` |

## 초기 버전 · NPC 대화

| 이미지 | 본문에 붙여 넣을 Markdown |
| --- | --- |
| [초기 버전 NPC 대화창](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/npc-dialogue/01-npc-dialogue-377772b7b0.png) | `![초기 버전 NPC 대화창](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/npc-dialogue/01-npc-dialogue-377772b7b0.png)` |
| [초기 버전 NPC 말풍선 안내](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/npc-dialogue/02-npc-speech-bubble-278eda5acc.png) | `![초기 버전 NPC 말풍선 안내](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/initial/npc-dialogue/02-npc-speech-bubble-278eda5acc.png)` |

## 고도화 버전 · 마을·실내·월드

| 이미지 | 본문에 붙여 넣을 Markdown |
| --- | --- |
| [고도화 버전 마을 전체 화면과 캐릭터](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/01-village-overview-f9166aead1.png) | `![고도화 버전 마을 전체 화면과 캐릭터](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/01-village-overview-f9166aead1.png)` |
| [마을 광장과 우물·안내판 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/02-village-square-92ec4fd1ea.png) | `![마을 광장과 우물·안내판 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/02-village-square-92ec4fd1ea.png)` |
| [마을에서 채팅 패널과 말풍선 표시](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/03-chat-panel-6ffbb6b2e8.png) | `![마을에서 채팅 패널과 말풍선 표시](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/03-chat-panel-6ffbb6b2e8.png)` |
| [마을 NPC·말풍선·표지판 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/04-npc-and-signboard-c789359e34.png) | `![마을 NPC·말풍선·표지판 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/04-npc-and-signboard-c789359e34.png)` |
| [다양한 지붕의 건물과 마을 길](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/05-village-buildings-a0a62e851b.png) | `![다양한 지붕의 건물과 마을 길](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/05-village-buildings-a0a62e851b.png)` |
| [마을 연못과 다리·벤치·우물](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/06-pond-and-bridge-92189f09eb.png) | `![마을 연못과 다리·벤치·우물](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/06-pond-and-bridge-92189f09eb.png)` |
| [무기점 실내 진입과 오브젝트 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/07-weapon-shop-interior-021d4650b5.png) | `![무기점 실내 진입과 오브젝트 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/07-weapon-shop-interior-021d4650b5.png)` |
| [무기점 카운터·갑옷·진열대 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/08-weapon-shop-layout-a1478b562f.png) | `![무기점 카운터·갑옷·진열대 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/08-weapon-shop-layout-a1478b562f.png)` |
| [무기점 NPC의 말풍선 대화](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/09-shopkeeper-dialogue-01568b3865.png) | `![무기점 NPC의 말풍선 대화](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/09-shopkeeper-dialogue-01568b3865.png)` |
| [마을 입구와 건물 진입 안내](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/10-village-entrance-8343fd9c4d.png) | `![마을 입구와 건물 진입 안내](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/10-village-entrance-8343fd9c4d.png)` |
| [마을 주거 구역과 숲 경계](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/11-residential-area-1aab3044f1.png) | `![마을 주거 구역과 숲 경계](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/11-residential-area-1aab3044f1.png)` |
| [마을 전환 안내와 필드 출입구](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/12-town-transition-40859b18d2.png) | `![마을 전환 안내와 필드 출입구](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/12-town-transition-40859b18d2.png)` |
| [촌장의 집 실내와 NPC 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/13-chief-house-interior-1352fdb855.png) | `![촌장의 집 실내와 NPC 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/13-chief-house-interior-1352fdb855.png)` |
| [어두운 실내의 버려진 집 진입](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/14-abandoned-house-entry-c1e82d7086.png) | `![어두운 실내의 버려진 집 진입](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/14-abandoned-house-entry-c1e82d7086.png)` |
| [실내 조명과 어둠 영역](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/15-interior-lighting-6cad1c99c5.png) | `![실내 조명과 어둠 영역](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/15-interior-lighting-6cad1c99c5.png)` |
| [숲 연못과 다양한 수목·바위 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/16-forest-pond-and-trees-dccb4902e5.png) | `![숲 연못과 다양한 수목·바위 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world/16-forest-pond-and-trees-dccb4902e5.png)` |

## 고도화 버전 · 퀘스트·대화

| 이미지 | 본문에 붙여 넣을 Markdown |
| --- | --- |
| [퀘스트 수락과 거절 선택](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/quests/01-quest-offer-f1d3efaac6.png) | `![퀘스트 수락과 거절 선택](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/quests/01-quest-offer-f1d3efaac6.png)` |
| [퀘스트 대화 진행](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/quests/02-quest-dialogue-c1dd366f22.png) | `![퀘스트 대화 진행](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/quests/02-quest-dialogue-c1dd366f22.png)` |
| [퀘스트 목표 진행 상황과 대화 마무리](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/quests/03-quest-objective-progress-682726708f.png) | `![퀘스트 목표 진행 상황과 대화 마무리](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/quests/03-quest-objective-progress-682726708f.png)` |
| [집 앞에서 진행하는 NPC 대화](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/quests/04-house-dialogue-0b02763a11.png) | `![집 앞에서 진행하는 NPC 대화](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/quests/04-house-dialogue-0b02763a11.png)` |

## 고도화 버전 · 전투·이펙트

| 이미지 | 본문에 붙여 넣을 Markdown |
| --- | --- |
| [숲 필드의 몬스터와 NPC 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/combat/01-forest-enemies-cd3414c936.png) | `![숲 필드의 몬스터와 NPC 배치](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/combat/01-forest-enemies-cd3414c936.png)` |
| [숲 전투 중 발사체와 마법 이펙트](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/combat/02-magic-projectile-a9dbcebb3e.png) | `![숲 전투 중 발사체와 마법 이펙트](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/combat/02-magic-projectile-a9dbcebb3e.png)` |
| [몬스터와의 교전 및 타격 이펙트](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/combat/03-hit-effect-99840e7c95.png) | `![몬스터와의 교전 및 타격 이펙트](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/combat/03-hit-effect-99840e7c95.png)` |
| [숲 필드의 근접 공격과 NPC 말풍선](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/combat/04-melee-attack-9b09907bef.png) | `![숲 필드의 근접 공격과 NPC 말풍선](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/combat/04-melee-attack-9b09907bef.png)` |

## 고도화 버전 · 상점·장비 UI

| 이미지 | 본문에 붙여 넣을 Markdown |
| --- | --- |
| [상점 판매 목록과 아이템 툴팁·인벤토리](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/ui/01-shop-and-inventory-22acd1ec0a.png) | `![상점 판매 목록과 아이템 툴팁·인벤토리](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/ui/01-shop-and-inventory-22acd1ec0a.png)` |
| [장비 슬롯과 남은 능력치 포인트](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/ui/02-equipment-and-stat-points-bccd725966.png) | `![장비 슬롯과 남은 능력치 포인트](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/ui/02-equipment-and-stat-points-bccd725966.png)` |
| [능력치 포인트 배분 후 장비·능력 창](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/ui/03-stat-allocation-0d2bde7435.png) | `![능력치 포인트 배분 후 장비·능력 창](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/ui/03-stat-allocation-0d2bde7435.png)` |
| [상점의 아이템 판매 수량 확인](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/ui/04-item-sale-confirmation-6f88078525.png) | `![상점의 아이템 판매 수량 확인](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/ui/04-item-sale-confirmation-6f88078525.png)` |

## 고도화 버전 · World Studio

| 이미지 | 본문에 붙여 넣을 Markdown |
| --- | --- |
| [World Studio 타일 팔레트와 맵 편집 화면](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world-studio/01-tile-palette-and-map-5e05130972.png) | `![World Studio 타일 팔레트와 맵 편집 화면](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world-studio/01-tile-palette-and-map-5e05130972.png)` |
| [World Studio에서 여러 오브젝트 선택](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world-studio/02-object-multi-selection-4b2273c400.png) | `![World Studio에서 여러 오브젝트 선택](https://kkn1125.github.io/blog-assets/images/blog/article/solo-2d-game-development-retrospective/advanced/world-studio/02-object-multi-selection-4b2273c400.png)` |
