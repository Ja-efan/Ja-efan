# 연재환 · AI Engineer

[English](README.md) · **한국어**

사용자의 문제를 정의하고 Agent를 개발·평가하며 AI 제품을 만듭니다.

[포트폴리오](https://jaefan.notion.site/Jaehwan-Yeon-200d2e168cd380abb942c7bf82c704b5) · [jaehwan.contact@gmail.com](mailto:jaehwan.contact@gmail.com)

## Cutback · AI Engineer
2025.08–2026.09

**Script-based Editing: 대본 기반 편집 기능의 초기 개발 및 파이프라인 개편**  
대본 기반 편집 기능을 초기 개발하고, 이후 사용자 인터뷰를 바탕으로 기능 개편 팀을 이끌었습니다. 파이프라인을 공동 설계하며 모듈 간 인터페이스를 조율하고 입출력 데이터를 구조화했으며, 재촬영 후보 그룹화 모듈을 구현·검증했습니다.

**Visual Editing: 시각 정보를 활용한 영상 편집 파이프라인 구축**  
영상의 키프레임을 기반으로 시각적으로 유의미한 구간을 찾고 설명을 생성해 편집과 검색 기능에 연결했습니다. 음성이 없는 영상에서도 사용자가 요청한 장면을 선택·연결할 수 있도록 지원 범위를 확장했습니다.

**Agent Optimization: AI Agent의 비용·실행 시간 최적화**  
공통 입력의 재사용과 필요한 정보의 사전 전달을 중심으로 Agent의 입력·실행 구조를 개선했습니다. Context Caching으로 서버 대본 편집 비용을 약 30% 절감하고, prefetch·single-shot 등 최적화로 실행 시간을 약 21% 단축했습니다.

**Evaluation: 정답이 여러 개인 편집 결과의 평가 자동화**  
여러 유효한 결과를 인정할 수 있도록 영상 주제 분할 평가를 단일 정답 비교에서 기존 가이드라인에 따른 LLM 평가로 전환했습니다. 배치 평가와 결과 이력 관리를 구현해 모델·프롬프트 변경에 따른 결과를 반복 비교할 수 있도록 했습니다.

**Architecture Wiki: 코드 변경과 함께 갱신되는 팀 지식 관리**  
코드 변경을 분석해 Markdown Wiki의 갱신안을 생성하고 Slack으로 공유하는 파이프라인을 구축했습니다. 사람과 Code Agent가 모듈 구조와 의존 관계를 같은 문서에서 참고할 수 있도록 해 팀의 컨텍스트 공유와 온보딩을 도왔습니다.

## 주요 프로젝트

- [Hello Job](https://github.com/Ja-efan/HelloJob) — 기업 조사 Agent, [SWOT MCP 도구](https://github.com/Ja-efan/swot-analysis-mcp), 취업 준비를 돕는 AI 백엔드.
- [쇼쇼숏](https://github.com/Ja-efan/shoshoshorts) — 이미지 생성 백엔드, AWS/GCP 인프라 및 CI/CD.
- [MeetGenius](https://github.com/Ja-efan/MeetGenius) — Jetson Orin Nano 기반 온디바이스 RAG와 회의록 요약.

## 주요 기술

Python · TypeScript · LangGraph · MCP · FastAPI · Docker · AWS · GCP
