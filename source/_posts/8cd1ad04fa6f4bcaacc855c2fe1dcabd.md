---
layout: post
title: 요구 사항(Requirement)
abbrlink: 8cd1ad04fa6f4bcaacc855c2fe1dcabd
tags:
  - requirements definition
categories:
  - 프로그램 친화적 설계
date: 1724058466012
updated: 1724243133848
---

## 요구 사항 (Requirements)

시스템이 만족해야 할 요구 사항들을 정의합니다. 이 단계에서 기능적 요구 사항, 비기능적 요구 사항 등을 모두 포함해야 합니다.

### 표

| Requirement ID (required) | Requirement Name (required) | Description                           | Verification Method (required) | Priority | Status   | Source | Related Requirements | Rationale                      |
| ------------------------- | --------------------------- | ------------------------------------- | ------------------------------ | -------- | -------- | ------ | -------------------- | ------------------------------ |
| REQ-001                   | 기본 도형 그리기                   | 사용자가 사각형, 원, 선 등의 기본 도형을 그릴 수 있어야 한다. | 테스트                            | High     | Proposed | 고객 요청  | REQ-002, REQ-003     | 기본적인 그림판 기능 제공을 위해 필요하다.       |
| REQ-002                   | 색상 선택                       | 사용자가 도형의 색상을 선택할 수 있어야 한다.            | 테스트                            | Medium   | Proposed | 고객 요청  | REQ-001              | 사용자가 원하는 색상으로 도형을 꾸미기 위해 필요하다. |
| REQ-003                   | 저장 기능                       | 사용자가 작업한 그림을 파일로 저장할 수 있어야 한다.        | 테스트                            | High     | Proposed | 고객 요청  | REQ-004              | 작업 내용을 잃지 않기 위해 필수적이다.         |
| REQ-004                   | 불러오기 기능                     | 사용자가 기존에 저장된 그림 파일을 불러올 수 있어야 한다.     | 테스트                            | High     | Proposed | 고객 요청  | REQ-003              | 이전 작업을 이어서 할 수 있게 하기 위해 필요하다.  |

### 필드와 값

하위 필드의 값이 한정적인 필드와 그 값 목록.

1. **Status (상태)**
   - Proposed (제안됨)
   - Approved (승인됨)
   - Implemented (구현됨)
   - Verified (검증됨)
   - Rejected (거부됨)

2. **Priority (우선순위)**
   - High (높음)
   - Medium (중간)
   - Low (낮음)

3. **Verification Method (검증 방법)**
   - *Required*
   - Test (테스트)
   - Analysis (분석)
   - Review (검토)

4. **Source (출처)**
   - Customer Request (고객 요청)
   - Legal Requirement (법적 요구사항)
   - Stakeholder Input (이해관계자 의견)
   - Market Research (시장 조사)

**Requirement ID**, **Verification Method** ,**Requirement Name**는 필수 값 입니다.
