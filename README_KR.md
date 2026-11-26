<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/brand/replay-logo-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/brand/replay-logo-light.png">
  <img alt="REPLAY" src="assets/brand/replay-logo-light.png" width="240">
</picture>

# 버블파이터 어드벤처 (BubbleFighter Adventure)

모바일 액션 게임

> **경고: Lab Track 참가 승인을 받은 창작자만 이용할 수 있습니다.** 승인받지 않은 사내 제작, 학습, 연구, 개인 공부, 상업 등 목적과 관계없이 모든 이용을 제한합니다.

> 이용 조건은 저장소 루트의 [LICENSE](LICENSE) 와 [NOTICE](NOTICE) 를 따릅니다. 뷰어: [이 게임을 뷰어로 보기](https://nexon-replay.github.io/Boomhill/#/g/bubblefighter-adventure). 세계관과 다른 게임은 [허브](https://nexon-replay.github.io/Boomhill/)에 있습니다.

## 폴더

| 폴더 | 내용 |
|---|---|
| `2d/` | 2D 그림: 묶음마다 폴더 하나, 그림은 PNG(여러 프레임이면 스프라이트 시트)와 아틀라스 JSON |
| `3d/` | 3D 미리보기 모델: 분류마다 폴더 하나. `<id>.glb` 모델, `<id>.webp` 썸네일, `<id>.json` 부가 정보 |
| `3d/_shared/` | 여러 모델이 나눠 쓰는 텍스처, 표정 그림, 조립 파츠(이름은 원래 이름_짧은 해시) |
| `2d/manifest.json`, `3d/manifest.json` | 파일마다 크기와 SHA-256 |

## 2D 그림

| 묶음 | 제목 | 그림 | 프레임 |
|---|---|---:|---:|
| `010_ui` | UI | 312 | 312 |
| `020_item` | 아이템, 무기 아이콘 | 143 | 143 |
| `030_map` | 맵, 배경 | 54 | 54 |
| `040_fx` | 효과 텍스처 | 119 | 119 |
| `050_texture` | 텍스처(캐릭터, 맵, 무기) | 81 | 81 |
| | 합계 | 709 | 709 |

## 3D 미리보기 모델

브라우저에서 바로 보는 미리보기입니다(압축 GLB, 텍스처 긴 변 512px, 캐릭터는 기본 동작만). 게임 제작, 편집에는 아래 원본 zip 을 쓰세요.

| 폴더 | 분류 | 모델 |
|---|---|---:|
| `3d/010_character/` | 캐릭터 | 47 |
| `3d/020_weapon/` | 무기, 아이템 | 45 |
| `3d/030_map/` | 맵 | 16 |
| `3d/040_anim/` | 애니메이션 | 492 |
| | 합계 | 600 |

## 3D 원본 zip

압축하지 않은 GLB, 원래 해상도 PNG 텍스처, 전체 동작을 분류마다 묶었습니다. 저장소의 Releases 에서 받습니다.

| 분류 | 파일 | 크기 | 모델 |
|---|---|---:|---:|
| 전체 | [bubblefighter-adventure-3d-all.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighterAdventure/releases/download/3d-originals-v1/bubblefighter-adventure-3d-all.zip) | 18.8MB | 629 |

형식은 [허브 저장소의 docs/format.md](https://github.com/NEXON-REPLAY/Boomhill/blob/main/docs/format.md), 쓰는 법은 [자료 안내](https://nexon-replay.github.io/Boomhill/guide.html)에 있습니다.
