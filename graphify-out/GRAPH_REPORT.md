# Graph Report - wiki/  (2026-05-27)

## Corpus Check
- Corpus is ~6,732 words - fits in a single context window. You may not need a graph.

## Summary
- 23 nodes · 43 edges · 6 communities (3 shown, 3 thin omitted)
- Extraction: 88% EXTRACTED · 12% INFERRED · 0% AMBIGUOUS · INFERRED: 5 edges (avg confidence: 0.81)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_AX 실무 & 할루시네이션|AX 실무 & 할루시네이션]]
- [[_COMMUNITY_그래프DB & AI 데이터 전략|그래프DB & AI 데이터 전략]]
- [[_COMMUNITY_온톨로지 핵심 개념|온톨로지 핵심 개념]]
- [[_COMMUNITY_위키 시스템 & 인제스트|위키 시스템 & 인제스트]]
- [[_COMMUNITY_위키 메타|위키 메타]]
- [[_COMMUNITY_위키 로그|위키 로그]]

## God Nodes (most connected - your core abstractions)
1. `온톨로지 (Ontology)` - 12 edges
2. `관리 가능한 자동화 (Manageable Automation)` - 10 edges
3. `기업 문서 자동화 (Enterprise Document Automation)` - 9 edges
4. `AI Ready Data` - 7 edges
5. `그래프DB (Graph Database)` - 6 edges
6. `소스: 온톨로지 기반 그래프DB 구축 방법론 (엔코아 김선영)` - 6 edges
7. `소스: AI는 왜 틀리는가? 그 답은 온톨로지에 있다 (한국딥러닝)` - 6 edges
8. `멀티 에이전트 (Multi-Agent)` - 5 edges
9. `지식 그래프 & 디지털 맥락지도` - 5 edges
10. `할루시네이션 (Hallucination)` - 4 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Hyperedges (group relationships)
- **온톨로지 → 지식그래프 → 그래프DB: AI Ready Data 구현 스택** — aitech_ontology, aitech_knowledge_graph, aitech_graphdb, axsil_ai_ready_data [EXTRACTED 0.95]
- **할루시네이션 원인 → 온톨로지 해결 → RAG 설계 개선** — aitech_hallucination, aitech_ontology, axsil_enterprise_doc_auto [EXTRACTED 0.90]
- **멀티에이전트 + 기업문서자동화 + 관리가능한자동화: AX 설계 핵심 삼각형** — axsil_multi_agent, axsil_enterprise_doc_auto, axsil_manageable_auto [INFERRED 0.85]

## Communities (6 total, 3 thin omitted)

### Community 0 - "AX 실무 & 할루시네이션"
Cohesion: 1.00
Nodes (8): 할루시네이션 (Hallucination), 기업 문서 자동화 (Enterprise Document Automation), 관리 가능한 자동화 (Manageable Automation), 멀티 에이전트 (Multi-Agent), Human-in-the-loop: 개입 제거가 아닌 개입 지점 설계가 목표, 자동화 범위 vs 통제 가능성 트레이드오프, 소스: AI는 왜 틀리는가? 그 답은 온톨로지에 있다 (한국딥러닝), 소스: 멀티 에이전트 시대, 기업 문서 업무 자동화도 '관리 가능한 AI'가 필요하다 (한국딥러닝)

### Community 1 - "그래프DB & AI 데이터 전략"
Cohesion: 1.00
Nodes (6): 그래프DB (Graph Database), 지식 그래프 & 디지털 맥락지도, AI Ready Data, 기업 AI 도입 실패 패턴: 기술 먼저 → 데이터 준비 부족 → 실망, 그래프DB는 온톨로지의 자연스러운 구현체: RDBMS 유연성 한계 극복, 소스: 온톨로지 기반 그래프DB 구축 방법론 (엔코아 김선영)

### Community 2 - "온톨로지 핵심 개념"
Cohesion: 1.00
Nodes (4): 온톨로지 (Ontology), 데이터 모델 vs 온톨로지: 저장 정규화 vs 의미 정규화, 온톨로지 업스트림 설계가 다운스트림 엔지니어링을 결정한다, 소스: 온톨로지 - 위키백과

## Knowledge Gaps
- **4 isolated node(s):** `Wiki Log`, `Wiki Index`, `나의 위키 시스템`, `wiki/ 운영 규칙 (CLAUDE.md)`
  These have ≤1 connection - possible missing edges or undocumented components.
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.