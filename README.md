# kakao_tech_step3_backend
## 성능지표 분석하기

### 📊 Before

#### 🖼️ 결과 이미지
<img width="2192" height="1180" alt="image" src="https://github.com/user-attachments/assets/d94956d6-9878-401c-bfc9-9f066b36dfb3" />
<img width="2256" height="636" alt="image" src="https://github.com/user-attachments/assets/3e300252-9132-4519-b724-6f4555d41655" />

---

#### 📊 전체 테스트 요약 (TOTAL RESULTS)

| 항목 | 값 |
|------|------|
| **총 요청 수 (checks_total)** | 5,890 |
| **성공한 요청 수 (checks_succeeded)** | 195 (3.31%) |
| **실패한 요청 수 (checks_failed)** | 5,695 (96.68%) |
| **평균 요청 처리 속도** | 6.38 req/s |
| **총 실행 시간** | 15분 22.6초 |
| **Virtual Users (VUs)** | 최대 200명 |
| **총 반복 횟수 (iterations)** | 3,694회 (평균 4.0/s) |

---

#### 📍 개별 API별 지연 시간 (Latency Metrics)

| 구분 | 평균 응답시간 (avg) | 최소 (min) | 중앙값 (med) | 최대 (max) | p(90) | p(95) | 실패 수 |
|------|------------------|-----------|-------------|-------------|--------|--------|---------|
| **browse_latency** | 14,977 ms | 11,031 ms | 14,999 ms | 15,063 ms | 15,000 ms | 15,001 ms | 1,484 |
| **header_latency** | 14,429 ms | 27 ms | 14,999 ms | 15,051 ms | 15,000 ms | 15,001 ms | 1,060 |
| **intro_latency** | 14,346 ms | 12 ms | 14,999 ms | 15,075 ms | 15,000 ms | 15,001 ms | 1,060 |
| **reviews_latency** | 14,397 ms | 6 ms | 14,999 ms | 15,205 ms | 15,000 ms | 15,001 ms | 1,038 |
| **update_mentee_latency** | 18,827 ms | 19 ms | 19,999 ms | 20,089 ms | 20,000 ms | 20,001 ms | 535 |
| **update_mentor_latency** | 18,950 ms | 52 ms | 19,999 ms | 20,023 ms | 20,000 ms | 20,000 ms | 518 |

---

#### 🌐 HTTP 통계 (HTTP Metrics)

| 항목 | 값 |
|------|------|
| **평균 HTTP 요청 시간 (avg)** | 15.38초 |
| **최소 요청 시간 (min)** | 6.99ms |
| **중앙값 (med)** | 14.99초 |
| **최대 요청 시간 (max)** | 20.08초 |
| **90% 구간 (p90)** | 19.99초 |
| **95% 구간 (p95)** | 19.99초 |
| **HTTP 실패율** | 96.68% |
| **성공 응답의 평균 시간** | 7.36초 (p90=14.48초, p95=14.86초) |

---

#### ⚙️ 실행 환경 (Execution)

| 항목 | 값 |
|------|------|
| **평균 Iteration 시간** | 25.19초 |
| **Iteration 최소~최대** | 0.61초 ~ 46.05초 |
| **Iteration 90% 구간** | 45.51초 |
| **Iteration 95% 구간** | 45.54초 |
| **VUs (가상 유저 수)** | 최대 200 |

---

#### 📡 네트워크 (Network)

| 항목 | 값 |
|------|------|
| **데이터 수신량 (data_received)** | 227 kB (246 B/s) |
| **데이터 송신량 (data_sent)** | 711 kB (770 B/s) |




### 📊 After

<img width="2034" height="1175" alt="스크린샷 2025-10-26 021909" src="https://github.com/user-attachments/assets/8073f1bf-262a-4d76-a420-2a55237b75d7" />


<2025/10/28>

<img width="2034" height="1358" alt="image" src="https://github.com/user-attachments/assets/521485c2-a258-47da-beaf-d2936415dcbc" />

