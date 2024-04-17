## [PROJECT] OpenAI 기반 검색 대화형 로컬환경 LLM 챗봇 구축 프로젝트 

![image](https://github.com/ckaudwn1685/ResearchAI-TESTVER/assets/122199987/5e11d504-e6ab-4493-b9fc-02dfe2cb597b)


#  구성
   - 서버 -> Node.js 및 Express를 사용하여 작성된 서버 (Flowise, index js)
   -  클라이언트(프론트엔드) -> (app.js)
   -  HTML 웹페이지(UI)

![image](https://github.com/ckaudwn1685/ResearchAI-TESTVER/assets/122199987/225b3168-12bc-43e0-abef-352097479708)

  -> Node.js 및 Express를 사용하여 작성된 서버 (flowise, index js).
    주어진 요청(req)에 대한 처리로서, 클라이언트로부터 받은 메시지를 사용하여
    외부 API인 Flowise API에 대한 예측(prediction)을 생성합니다.
    이를 RESTful하게 처리하기 위해 Express의 라우터로 설정되어 있습니다.


![image](https://github.com/ckaudwn1685/ResearchAI-TESTVER/assets/122199987/2eebcc8a-bb5c-4e6b-9798-145fc910cd4a)

  -> [Flowise](https://github.com/ckaudwn1685/Flowise)를 통해 구축한 대화형 챗봇의 모습. ChatOpenAI 모델 선택 및 파라미터 자유자재로 수정변경 가능. 
  <sub>*Flowise : Open source UI visual tool to build your customized LLM ochestration flow & AI agents</sub>

![image](https://github.com/ckaudwn1685/ResearchAI-TESTVER/assets/122199987/e4f336d7-a004-4339-a6de-639cd03416c7)

  -> 서버를 배포하기 위해 Render 내 Flowise의 API를 연결하여 서버 구축완료.
