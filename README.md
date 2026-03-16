<div align="center">

# DX11 Wuthering Waves

<img src="./Styles/Rinascita.jpg" width="80%" />
</div>

<h3>📅 개발 기간 : 2개월 &nbsp;&nbsp;</h3>
<h3>👥 개발 인원 : 7명</h3>

<h3> 담당 파트 : Shader | 디퍼드 렌더링 파이프라인, SFX </h3>
<h3> Origin : https://github.com/PJH1998/Wuthring-Wave-Final </h3>

<br></br>


# 게임 플레이 하이라이트

<table>
  <tr>
    <td align="center" width="50%">
      <h3>레비아탄 컷씬</h3>
      <img src="./Styles/LeviatanCutScene.webp" width="100%">
    </td>
    <td align="center" width="50%">
      <h3>레비아탄 전투 (QTE)</h3>
      <img src="./Styles/LeviatanQTE2.webp" width="100%">
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <h3>코로사우로스 전투</h3>
      <img src="./Styles/Corosaurus.webp" width="100%">
    </td>
    <td align="center" width="50%">
      <h3>거짓된 신왕 전투</h3>
      <img src="./Styles/LieKing.webp" width="100%">
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <h3>로그인 화면 </h3>
      <img src="./Styles/EnvMap.webp" width="100%">
    </td>
    <td align="center" width="50%">
      <h3>갓 레이</h3>
      <img src="./Styles/Ray0.webp" width="100%">
    </td>
  </tr>
  
</table>

<br>

## 👥 팀원 목록

| 이름 | 역할 | 설명 |
| :---: | :--- | :--- |
| **박지호(팀장)** | **MainFramework** | 메인 프레임워크, 카메라, 최적화, 레벨 디자인, 천국 맵 배치|
| **김정훈** | **Shader** | 디퍼드 렌더링 파이프라인, SFX |
| **노영훈** | **Player / Animation** | 플레이어 상태 제어, 애니메이션 제어 |
| **임은비** | **Effects** | 전투 및 환경 Effect |
| **이진호** | **AI / Monster** | 몬스터 전투 AI, NPC |
| **김기훈** | **UI System** | UI 인터페이스, 미니게임, 스크립트 |
| **신우혁** | **Map** | 맵 에디터, 1Stage 배치 |

- 플레이 및 담당 파트 영상
    - 셰이더 파트 28 : 40 ~ 32 : 19
    - 게임 플레이 37 : 49 ~ 49 : 05

[https://youtu.be/5lqrt_9vJ7g](https://youtu.be/5lqrt_9vJ7g)


- 프로젝트 개요
    - C++과 DirectX11 기반으로 제작한 명조: 워더링 웨이브 모작 프로젝트입니다.
    - 7인 팀 프로젝트로 진행하여 
    셰이더 구현과 Deferred Rendering 기반 렌더링 파이프라인 구조 구현을 담당했습니다.

- 개발 목표
    - 원작 게임의 렌더링 환경을 분석하여 Deferred Rendering 기반 렌더링 파이프라인 구조 재현
    - 환경 연출을 위한 다양한 셰이더 및 렌더링 기법 구현
    
- 구현 목록

| **구분** | **내용** |
| --- | --- |
| 상호작용 | Decal 기반 스캔 범위 표시 및 오브젝트 탐지 시스템 |
| 이펙트 | 플레이어 궁극기 스크린 이펙트 |
| 렌더링 & 그래픽스 | 렌더 타겟 기반 렌더링 파이프라인 <br> HDR / 외곽선 / Decal / Rim Light <br> Down Sampling / Up Sampling <br> PBR 기반 조명 및 재질 표현 <br> Cascade Shadow Map 기반 동적 객체 그림자 표현 <br> Atlas Shadow Map 기반 정적 객체 그림자 표현 <br> Temporal Reprojection을 활용한 볼류메트릭 포그 및 God Ray 표현 <br><br> **Post Processing** <br> SSAO / Bloom / Blur / LUT <br> 화면 왜곡 / 화면 분할 <br> Reflection Probe 기반 물 반사 표현   |
