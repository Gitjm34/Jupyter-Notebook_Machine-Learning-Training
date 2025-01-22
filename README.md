# Jupyter-Notebook_Machine-Learning-Training
# 🚀 KDD CUP 99 기반 네트워크 공격 탐지 (Intrusion Detection System)

### 📌 프로젝트 개요
이 프로젝트는 **KDD CUP 99 데이터셋을 활용하여 네트워크 공격을 탐지하는 머신러닝 모델을 개발하는 것을 목표로 합니다.  
Logistic Regression, Random Forest, SVM 등의 모델을 학습하고 성능을 비교하여 가장 효과적인 탐지 모델을 선정합니다.

---

### 🔍 **기술 스택 (Tech Stack)**
- 🐍 Python (Jupyter Notebook)
- 📦 Scikit-learn (Machine Learning)
- 📊 Pandas, NumPy (데이터 처리)
- 🎨 Matplotlib, Seaborn (데이터 시각화)

---

### 📂 **데이터셋 (Dataset)**
- **KDD CUP 99**: 네트워크 트래픽 기반 공격 탐지 데이터셋
- 공격 유형:
  - **DoS (Denial of Service) 공격**: `smurf.`, `neptune.`, `pod.` 등
  - **Probe (탐색 공격)**: `portsweep.`, `nmap.`, `ipsweep.` 등
  - **R2L (Remote to Local) 공격**: `warezmaster.`, `guess_passwd.`, `ftp_write.` 등
  - **U2R (User to Root) 공격**: `buffer_overflow.`, `rootkit.`, `perl.` 등

---

### ⚙ **모델 및 학습 과정**
1️⃣ **데이터 전처리**
   - 결측치 제거, 라벨 인코딩, 특성 변환(StandardScaler 적용)

2️⃣ **모델 학습 및 성능 비교**
   - **Logistic Regression** → 정확도: `99.83%`
   - **Random Forest** → 정확도: `99.99%`
   - **SVM (Support Vector Machine)** → 테스트 중

3️⃣ **성능 평가**
   - **Confusion Matrix, Precision, Recall, F1-score 분석**
   - **ROC Curve(AUC)** 값 비교

---

### 📊 **모델 성능 결과**
| 모델 | 정확도 (Accuracy) | Precision | Recall | F1-score |
|------|----------------|-----------|--------|----------|
| Logistic Regression | 99.83% | 1.00 | 0.99 | 0.99 |
| Random Forest | 99.99% | 1.00 | 1.00 | 1.00 |
| SVM | 테스트 진행 중 | - | - | - |

---

### 🖥 **실행 방법 (How to Run)**
#### 1️⃣ **환경 설정**
```bash
pip install numpy pandas scikit-learn matplotlib seaborn

✨ 참고 자료 (References)
KDD CUP 99 Dataset: http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html
Scikit-learn Documentation: https://scikit-learn.org/


