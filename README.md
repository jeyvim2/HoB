# HoB (Houdini on Blender)

HoB is a Blender add-on that runs Houdini inside Blender. Houdini networks (SOP, COP, LOP, OBJ, VOP,
CHOP, DOP) are edited in Blender's Node Editor, their parameters are drawn in Blender's sidebar, and the
Houdini engine cooks the results (geometry, volumes, images, USD stages, rigs) into Blender objects.

- **Download:** [latest release](https://github.com/jeyvim2/HoB/releases/latest): `hob-1.0.0.zip` (the
  Blender extension) and `hob-examples.zip` (example scenes, optional).
- **User guide (English / 한국어):** https://coherent-equipment-446.notion.site/41974ea2456f81408695dc33e2bcac44

## Requirements

- Windows 10 or 11 (64-bit)
- **Houdini 22.x, installed separately.** HoB does not include, download or install Houdini. Get it from
  SideFX ([sidefx.com/download](https://www.sidefx.com/download/)), install it and start it once so that
  its licence is set up. Any licence works, the free Apprentice too (with limits, see the user guide).
- Blender 5.2 or later

## Install

1. Install Houdini first (see Requirements).
2. In Blender, open **Edit > Preferences > Get Extensions**, open the menu at the top right, choose
   **Install from Disk...** and pick `hob-1.0.0.zip`.
3. In the 3D Viewport press `N`, choose the tab **HoB** and press **Start Engine**.

The user guide has the first steps, troubleshooting, the licence FAQ and the limitations.

## Licence, no support

HoB is free software under the GNU General Public License, version 3 or later (GPL-3.0-or-later), see
[LICENSE](LICENSE). It comes with no warranty and **no support**: no help desk, no bug tracker, no
promise of fixes or updates. The release zip holds the complete source of the add-on and its engine
(Python); you may change it and share your version under the same licence.

Houdini is a product of Side Effects Software Inc.; Blender is a project of the Blender Foundation.
HoB is not made or endorsed by either.

## 한국어

HoB는 Blender 안에서 Houdini를 실행하는 Blender 애드온입니다. Houdini 네트워크를 Blender의 Node Editor에서
편집하면 Houdini 엔진이 결과를 Blender 오브젝트로 가져옵니다.

- **내려받기:** [최신 릴리스](https://github.com/jeyvim2/HoB/releases/latest)의 `hob-1.0.0.zip`(Blender
  확장)과 `hob-examples.zip`(예제 장면, 선택)
- **사용 가이드(English / 한국어):** https://coherent-equipment-446.notion.site/41974ea2456f81408695dc33e2bcac44
- **Houdini는 따로 설치해야 합니다.** HoB에는 Houdini가 들어 있지 않고, HoB가 Houdini를 내려받거나 설치하지도
  않습니다. SideFX([sidefx.com/download](https://www.sidefx.com/download/))에서 Houdini 22.x를 받아 설치하고,
  라이선스가 설정되도록 한 번 실행해 두십시오. 무료 Apprentice를 포함해 어떤 라이선스든 됩니다(제한은 가이드 참고).
- 요구 사항: Windows 10/11 64비트, Blender 5.2 이상.
- 설치: Blender에서 **Edit > Preferences > Get Extensions** > 오른쪽 위 메뉴 > **Install from Disk...**로
  `hob-1.0.0.zip`을 고른 뒤, 3D Viewport에서 `N` > **HoB** 탭 > **Start Engine**을 누릅니다.

HoB는 GPL-3.0-or-later 자유 소프트웨어이며 보증과 지원 없이 있는 그대로 제공됩니다(문의·신고 창구 없음,
수정·업데이트 약속 없음). 릴리스 zip에 애드온과 엔진의 전체 소스(Python)가 들어 있습니다.
