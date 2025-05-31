# 국토교통부 예산 정보 QA 기반 RAG & LLM Fine-tuning 실습

## 프로젝트 목적
이 프로젝트는 [DACON의 국토교통부 예산 정보 QA 대회](https://dacon.io/competitions/official/236295/overview/description)를 기반으로, 팀원들과 함께 RAG (Retrieval-Augmented Generation) 기법과 LLM (대형 언어 모델) 미세조정 기술을 실습하고 연구하기 위한 내부 학습용 프로젝트입니다.
공식 대회는 종료되었지만, 실전 수준의 데이터셋과 문제 유형을 통해 문서 기반 질의응답 시스템 구축과 모델 훈련 워크플로우를 경험하는 것을 목표로 합니다.

## 시작하기
```bash
git clone https://github.com/Habonit/openfiscal-qa

cp .env.example .env
```
- .env 파일을 생성한 후, 각자의 환경에 맞게 수정합니다.
- Python 가상환경을 사용합니다. 설치되지 않은 경우 Miniconda 설치를 권장합니다.

```bash
conda create -n <가상환경 이름> python=3.11
conda activate <가상환경 이름>
pip install -r requirements.txt
```
- 여기까지 진행한 후 main.ipynb를 전체 실행합니다.