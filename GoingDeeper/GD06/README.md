# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 최은학
- 리뷰어 : 박범찬


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
          <img width="523" height="563" alt="image" src="https://github.com/user-attachments/assets/94f346be-a466-4e70-b5c1-56d33908f6d7" />
          <img width="457" height="393" alt="image" src="https://github.com/user-attachments/assets/a19b2305-a402-47b8-8c67-07c37026bc69" />
          <img width="420" height="75" alt="image" src="https://github.com/user-attachments/assets/785567b3-17d3-4500-ab3b-7dadce36e8cb" />
          - 주어진 예문을 포함하여 챗봇에 던진 질문에 답하는 결과가 잘 나왔습니다.
              - 학습 목표 : 챗봇이 사용자의 질문에 그럴듯한 형태로 답하는 사례가 있는가?
              - 제출 루브릭 평가 기준 : 주어진 예문을 포함하여 챗봇에 던진 질문에 적절히 답하는 사례가 제출되었다.

    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="855" height="614" alt="image" src="https://github.com/user-attachments/assets/74984306-545c-4078-97dd-183fcb14a63b" />
          <img width="810" height="529" alt="image" src="https://github.com/user-attachments/assets/9d156e3c-9315-424b-b343-77162e74215e" />
          - Lexical Substitution 함수를 정의하는 부분에서 단어를 저장하는 변수, 돌아가는 구조에 대한 주석이 잘 적혀있습니다.
          - 인코딩을 벡터로 표기하는 부분에서 토큰화 / 정수 인코딩 / 시작 토큰과 종료 토큰 추가 / 패딩으로 나눠 명시되어 있습니다. 
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 회고 부분에 포함되어 추가 실험과 개선 방향성에 대해서 잘 명시되어 있습니다.
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="797" height="417" alt="image" src="https://github.com/user-attachments/assets/edeee9f8-add4-4166-8c7c-975a58a9b56c" />
          - 프로젝트를 진행하면서 했던 실험들에 대해서 회고를 잘 작성하였습니다.
              - 토크나이저, 데이터 증강, BLEU 점수, 개선 방향 등

        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="537" height="672" alt="image" src="https://github.com/user-attachments/assets/03f9e8bd-0ed1-4589-ac3a-a559781f94bf" />
          <img width="845" height="545" alt="image" src="https://github.com/user-attachments/assets/d901e5a2-da87-4fe8-8433-ddaf19bd6d80" />
          - 예문 리스트에 따른 답변을 생성, 출력할 때, 하이퍼파라미터를 같이 출력하여 가독성을 높였습니다.
          - 결과 출력적 간단한 테스트 질문에 따른 정답 label과 생성한 label을 비교하였고 BLEU Score 결과를 명시했습니다.



# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```

- 데이터 증강에 대해서는 데이터가 부족한 경우가 아니라면 굳이 안하는 것이 성능에 좋다는 것이 느껴졌습니다.
- 챗봇을 평가하는 지표로 BLEU Score가 효율적인지에 대한 의문이 남았습니다. (평가 기준이 그러니까,,,)
- 토크나이저를 정하는 과정에서 SPM을 정하는 이유가 명확해서 좋았습니다.
