# 🚁 대화형 드론 순찰 시스템

LLM Agent와 강화학습 기반 경로 계획, YOLO 객체 탐지를 결합한  
**자율 드론 순찰 시뮬레이션 시스템**입니다.

<p align="center">
  <img width="420" height="594" alt="Frame 1" src="https://github.com/user-attachments/assets/6dfa4b72-f96f-44b9-a160-0a575dfaf373" />
</p>

## 📌 Overview

사용자가 자연어로 순찰 구역을 지정하면 LLM이 명령을 해석하고,
드론이 지정된 공간을 자율 순찰합니다.

순찰 중에는 **360° 스캔과 YOLO 기반 사람 탐지**를 수행하며,
탐지 결과와 순찰 기록을 웹 UI에서 확인할 수 있습니다.

## ✨ Key Features

- 💬 **LLM 기반 자연어 순찰 명령**
  - "2층 전체 순찰해줘"
  - "방을 돌면서 사람이 있는지 확인해줘"

- 🚁 **자율 순찰**
  - 3D 공간 정보를 활용한 경로 생성
  - 강화학습 기반 드론 이동

- 👤 **YOLO 객체 탐지**
  - 순찰 지점에서 360° 스캔
  - 사람 탐지 및 위치 기록

- 🖥️ **Web UI**
  - 순찰 구역 지정
  - 실시간 순찰 상태 확인
  - 탐지 결과 및 보고서 제공

## 🔄 System Flow

`사용자 명령`
→ `LLM 공간/의도 해석`
→ `경로 계획`
→ `드론 자율 비행`
→ `YOLO 사람 탐지`
→ `순찰 결과 보고`

## 🛠 Tech Stack

`Python` `Unity` `YOLOv8` `Qwen2.5` `SAC` `FastAPI`

## 👥 Team AURORA

AI 연합 동아리 **Prometheus** 프로젝트
