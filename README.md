# ABSN_survey
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>간호학사편입 집중과정(ABSN) 운영평가 설문지</title>
  <style>
    body {
      font-family: 'Malgun Gothic', Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 20px;
      background-color: #f5f5f5;
    }
    h1, h2, h3 {
      text-align: center;
    }
    form {
      background-color: #fff;
      max-width: 1000px;
      margin: 0 auto;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    fieldset {
      margin-bottom: 25px;
      padding: 15px;
      border: 1px solid #ccc;
    }
    legend {
      font-weight: bold;
      padding: 0 10px;
    }
    .matrix-table, .choice-table {
      width: 100%;
      border-collapse: collapse;
      margin-bottom: 15px;
    }
    .matrix-table th, .matrix-table td,
    .choice-table th, .choice-table td {
      border: 1px solid #ddd;
      padding: 8px;
      text-align: center;
      vertical-align: middle;
    }
    .matrix-table th {
      background-color: #eee;
    }
    .question {
      margin-bottom: 15px;
    }
    label {
      display: block;
      margin-bottom: 5px;
    }
    .inline {
      display: inline-block;
      margin-right: 15px;
    }
    .checkbox-group label, .radio-group label {
      display: inline-block;
      margin-right: 10px;
    }
    .open-text {
      width: 100%;
      min-height: 80px;
    }
    input[type="text"], input[type="number"], textarea {
      width: 100%;
      padding: 8px;
      box-sizing: border-box;
      margin-bottom: 10px;
    }
    .submit-btn {
      display: block;
      margin: 0 auto;
      padding: 12px 20px;
      font-size: 16px;
    }
    /* 임베드 배포 시 외부 컨테이너 스타일 (선택사항) */
    .form-container {
      max-width: 1000px;
      margin: 0 auto;
    }
  </style>
</head>
<body>
  <div class="form-container">
  <form method="post" action="submit_form.php">
    <!-- 설문지 제목 및 소개 -->
    <h1>간호학사편입 집중과정(ABSN) 운영평가 설문지</h1>
    <p>
      안녕하십니까?<br>
      본 연구는 연세대학교 간호대학 교육과정위원회에서 진행하는 정책연구의 일환으로,
      간호학사편입 집중과정(Accelerated Bachelor of Science in Nursing, ABSN)의 운영 현황을 점검하고 발전 전략을 도출하는 것을 목적으로 합니다.
      이를 위해 졸업생 여러분의 교육과정 평가 및 학습 경험, 진로 및 취업 현황을 분석하고자 합니다.<br>
      귀하의 답변은 향후 연세대학교 간호대학의 학사편입 집중과정의 개선방안을 제시하는 데 도움이 될 것입니다.<br><br>
      설문 작성 소요 시간: 약 15분<br>
      (참여하지 않거나 도중에 중단하셔도 불이익은 없습니다.)<br>
      개인정보는 연구 목적 외에는 사용되지 않습니다.<br>
      설문 후 연락처 기입 시 기프티콘(10,000원 상당) 지급 예정입니다.<br>
      문의: 이경희 교무부학장 / 김연지 연구교수, 연락처: 02-2228-3230, 이메일: redyonji@yuhs.ac<br><br>
      소중한 시간 내주셔서 감사합니다.
    </p>

    <!-- [교육목표/프로그램 학습성과] 섹션 -->
    <fieldset>
      <legend>[교육목표/프로그램 학습성과]</legend>
      
      <!-- 1번: 교육목표 평가 (매트릭스) -->
      <div class="question">
        <p><strong>1. 교육목표 평가:</strong> 우리 간호대학은 7개의 교육목표를 가지고 있습니다. 졸업 후 현 시점에서, 귀하는 우리대학의 교육목표를 얼마나 달성했다고 생각하십니까? 해당 항목에 체크해 주십시오.</p>
        <table class="matrix-table">
          <tr>
            <th>교육목표</th>
            <th>전혀 그렇지 않다</th>
            <th>그렇지 않다</th>
            <th>보통이다</th>
            <th>그렇다</th>
            <th>매우 그렇다</th>
          </tr>
          <!-- 각 행에 대해 radio 그룹 이름은 eduObj_1, eduObj_2, ... -->
          <tr>
            <td>1. 전인간호실천을 위해 인간의 건강기능양상을 통합적으로 이해한다.</td>
            <td><input type="radio" name="eduObj_1" value="1" required></td>
            <td><input type="radio" name="eduObj_1" value="2"></td>
            <td><input type="radio" name="eduObj_1" value="3"></td>
            <td><input type="radio" name="eduObj_1" value="4"></td>
            <td><input type="radio" name="eduObj_1" value="5"></td>
          </tr>
          <tr>
            <td>2. 건강문제 해결을 위해 비판적 사고능력과 과학적 지식을 통합한다.</td>
            <td><input type="radio" name="eduObj_2" value="1" required></td>
            <td><input type="radio" name="eduObj_2" value="2"></td>
            <td><input type="radio" name="eduObj_2" value="3"></td>
            <td><input type="radio" name="eduObj_2" value="4"></td>
            <td><input type="radio" name="eduObj_2" value="5"></td>
          </tr>
          <tr>
            <td>3. 대상자의 안녕촉진을 위해 치료적 돌봄을 제공한다.</td>
            <td><input type="radio" name="eduObj_3" value="1" required></td>
            <td><input type="radio" name="eduObj_3" value="2"></td>
            <td><input type="radio" name="eduObj_3" value="3"></td>
            <td><input type="radio" name="eduObj_3" value="4"></td>
            <td><input type="radio" name="eduObj_3" value="5"></td>
          </tr>
          <tr>
            <td>4. 건강관리팀 내에서 협력관계를 형성한다.</td>
            <td><input type="radio" name="eduObj_4" value="1" required></td>
            <td><input type="radio" name="eduObj_4" value="2"></td>
            <td><input type="radio" name="eduObj_4" value="3"></td>
            <td><input type="radio" name="eduObj_4" value="4"></td>
            <td><input type="radio" name="eduObj_4" value="5"></td>
          </tr>
          <tr>
            <td>5. 윤리적‧법적 책임의식을 바탕으로 간호전문직관을 확립한다.</td>
            <td><input type="radio" name="eduObj_5" value="1" required></td>
            <td><input type="radio" name="eduObj_5" value="2"></td>
            <td><input type="radio" name="eduObj_5" value="3"></td>
            <td><input type="radio" name="eduObj_5" value="4"></td>
            <td><input type="radio" name="eduObj_5" value="5"></td>
          </tr>
          <tr>
            <td>6. 국내외 환경변화에 능동적으로 대응하는 능력을 함양한다.</td>
            <td><input type="radio" name="eduObj_6" value="1" required></td>
            <td><input type="radio" name="eduObj_6" value="2"></td>
            <td><input type="radio" name="eduObj_6" value="3"></td>
            <td><input type="radio" name="eduObj_6" value="4"></td>
            <td><input type="radio" name="eduObj_6" value="5"></td>
          </tr>
          <tr>
            <td>7. 개척정신과 기독교적 사랑을 바탕으로 섬김의 글로벌 리더십을 발휘한다.</td>
            <td><input type="radio" name="eduObj_7" value="1" required></td>
            <td><input type="radio" name="eduObj_7" value="2"></td>
            <td><input type="radio" name="eduObj_7" value="3"></td>
            <td><input type="radio" name="eduObj_7" value="4"></td>
            <td><input type="radio" name="eduObj_7" value="5"></td>
          </tr>
        </table>
      </div>
      
      <!-- 2번: 프로그램 학습성과 평가 (매트릭스) -->
      <div class="question">
        <p><strong>2. 프로그램 학습성과 평가:</strong> 우리 간호대학은 졸업 시 성취해야 하는 10개 프로그램 학습성과를 규정하였습니다. 졸업 후 현 시점에서, 귀하는 학습성과를 얼마나 성취했다고 생각하십니까?</p>
        <table class="matrix-table">
          <tr>
            <th>프로그램 학습성과</th>
            <th>전혀 성취하지 못했다</th>
            <th>성취하지 못했다</th>
            <th>보통이다</th>
            <th>성취하였다</th>
            <th>잘 성취하였다</th>
          </tr>
          <!-- 각 행의 radio 그룹은 progOutcome_1 ~ progOutcome_10 -->
          <tr>
            <td>1. 대상자의 건강문제를 해결하기 위해 다양한 지식과 기술을 통합할 수 있다.</td>
            <td><input type="radio" name="progOutcome_1" value="1" required></td>
            <td><input type="radio" name="progOutcome_1" value="2"></td>
            <td><input type="radio" name="progOutcome_1" value="3"></td>
            <td><input type="radio" name="progOutcome_1" value="4"></td>
            <td><input type="radio" name="progOutcome_1" value="5"></td>
          </tr>
          <tr>
            <td>2. 대상자의 간호상황에 따른 핵심기본간호술을 실행할 수 있다.</td>
            <td><input type="radio" name="progOutcome_2" value="1" required></td>
            <td><input type="radio" name="progOutcome_2" value="2"></td>
            <td><input type="radio" name="progOutcome_2" value="3"></td>
            <td><input type="radio" name="progOutcome_2" value="4"></td>
            <td><input type="radio" name="progOutcome_2" value="5"></td>
          </tr>
          <tr>
            <td>3. 치료적 관계형성을 위한 의사소통기술을 적용할 수 있다.</td>
            <td><input type="radio" name="progOutcome_3" value="1" required></td>
            <td><input type="radio" name="progOutcome_3" value="2"></td>
            <td><input type="radio" name="progOutcome_3" value="3"></td>
            <td><input type="radio" name="progOutcome_3" value="4"></td>
            <td><input type="radio" name="progOutcome_3" value="5"></td>
          </tr>
          <tr>
            <td>4. 비판적 사고와 과학적 지식에 근거한 간호과정을 적용할 수 있다.</td>
            <td><input type="radio" name="progOutcome_4" value="1" required></td>
            <td><input type="radio" name="progOutcome_4" value="2"></td>
            <td><input type="radio" name="progOutcome_4" value="3"></td>
            <td><input type="radio" name="progOutcome_4" value="4"></td>
            <td><input type="radio" name="progOutcome_4" value="5"></td>
          </tr>
          <tr>
            <td>5. 건강문제해결에 참여하는 전문분야간 협력관계를 설명할 수 있다.</td>
            <td><input type="radio" name="progOutcome_5" value="1" required></td>
            <td><input type="radio" name="progOutcome_5" value="2"></td>
            <td><input type="radio" name="progOutcome_5" value="3"></td>
            <td><input type="radio" name="progOutcome_5" value="4"></td>
            <td><input type="radio" name="progOutcome_5" value="5"></td>
          </tr>
          <tr>
            <td>6. 간호전문직 표준, 윤리적‧법적 기준을 간호상황에 적용할 수 있다.</td>
            <td><input type="radio" name="progOutcome_6" value="1" required></td>
            <td><input type="radio" name="progOutcome_6" value="2"></td>
            <td><input type="radio" name="progOutcome_6" value="3"></td>
            <td><input type="radio" name="progOutcome_6" value="4"></td>
            <td><input type="radio" name="progOutcome_6" value="5"></td>
          </tr>
          <tr>
            <td>7. 간호실무현장에서 간호리더십을 개발할 수 있다.</td>
            <td><input type="radio" name="progOutcome_7" value="1" required></td>
            <td><input type="radio" name="progOutcome_7" value="2"></td>
            <td><input type="radio" name="progOutcome_7" value="3"></td>
            <td><input type="radio" name="progOutcome_7" value="4"></td>
            <td><input type="radio" name="progOutcome_7" value="5"></td>
          </tr>
          <tr>
            <td>8. 간호연구를 계획하고 수행할 수 있다.</td>
            <td><input type="radio" name="progOutcome_8" value="1" required></td>
            <td><input type="radio" name="progOutcome_8" value="2"></td>
            <td><input type="radio" name="progOutcome_8" value="3"></td>
            <td><input type="radio" name="progOutcome_8" value="4"></td>
            <td><input type="radio" name="progOutcome_8" value="5"></td>
          </tr>
          <tr>
            <td>9. 국내외 보건의료 정책변화를 분석할 수 있다.</td>
            <td><input type="radio" name="progOutcome_9" value="1" required></td>
            <td><input type="radio" name="progOutcome_9" value="2"></td>
            <td><input type="radio" name="progOutcome_9" value="3"></td>
            <td><input type="radio" name="progOutcome_9" value="4"></td>
            <td><input type="radio" name="progOutcome_9" value="5"></td>
          </tr>
          <tr>
            <td>10. 섬김의 글로벌 리더십을 실천할 수 있다.</td>
            <td><input type="radio" name="progOutcome_10" value="1" required></td>
            <td><input type="radio" name="progOutcome_10" value="2"></td>
            <td><input type="radio" name="progOutcome_10" value="3"></td>
            <td><input type="radio" name="progOutcome_10" value="4"></td>
            <td><input type="radio" name="progOutcome_10" value="5"></td>
          </tr>
        </table>
      </div>
    </fieldset>

    <!-- [간호수행능력] 섹션 (예시: 1~10행만 포함) -->
    <!-- 실제 문서는 37개 행에 대해 진행되나, 여기서는 예시로 일부 행만 구현 -->
    <fieldset>
      <legend>[간호수행능력]</legend>
      <div class="question">
        <p><strong>1. 간호수행능력 평가:</strong> 졸업 후 현 시점에서, 귀하는 다음 각 항목을 어느 정도 수행할 수 있다고 생각하십니까?</p>
        <table class="matrix-table">
          <tr>
            <th>간호수행능력</th>
            <th>전혀 자신이 없다</th>
            <th>자신이 없다</th>
            <th>잘 할 수 있다</th>
            <th>매우 잘 할 수 있다</th>
          </tr>
          <tr>
            <td>1. 치료적 의사소통 기술을 활용하여 대상자를 이해하고 수용한다.</td>
            <td><input type="radio" name="nursing_1" value="1" required></td>
            <td><input type="radio" name="nursing_1" value="2"></td>
            <td><input type="radio" name="nursing_1" value="3"></td>
            <td><input type="radio" name="nursing_1" value="4"></td>
          </tr>
          <tr>
            <td>2. 대상자의 요구에 수용적인 느낌을 주고 안녕에 관심을 표현한다.</td>
            <td><input type="radio" name="nursing_2" value="1" required></td>
            <td><input type="radio" name="nursing_2" value="2"></td>
            <td><input type="radio" name="nursing_2" value="3"></td>
            <td><input type="radio" name="nursing_2" value="4"></td>
          </tr>
          <!-- 추가 행들은 문서에 따라 계속 추가 -->
        </table>
      </div>
    </fieldset>

    <!-- [학사편입 교육과정과 교육 만족도] 섹션 (일부 예시) -->
    <fieldset>
      <legend>[학사편입 교육과정과 교육 만족도]</legend>
      <div class="question">
        <p><strong>1. 교육 만족도 평가:</strong> 아래 문항에 얼마나 만족하시는지 선택해 주십시오.</p>
        <table class="matrix-table">
          <tr>
            <th>문항</th>
            <th>매우 만족하지 않는다</th>
            <th>만족하지 않는다</th>
            <th>보통이다</th>
            <th>만족한다</th>
            <th>매우 만족한다</th>
          </tr>
          <tr>
            <td>간호학사편입 집중과정 전반</td>
            <td><input type="radio" name="satisfaction_1" value="1" required></td>
            <td><input type="radio" name="satisfaction_1" value="2"></td>
            <td><input type="radio" name="satisfaction_1" value="3"></td>
            <td><input type="radio" name="satisfaction_1" value="4"></td>
            <td><input type="radio" name="satisfaction_1" value="5"></td>
          </tr>
          <tr>
            <td>교수님의 능력 및 열의</td>
            <td><input type="radio" name="satisfaction_2" value="1" required></td>
            <td><input type="radio" name="satisfaction_2" value="2"></td>
            <td><input type="radio" name="satisfaction_2" value="3"></td>
            <td><input type="radio" name="satisfaction_2" value="4"></td>
            <td><input type="radio" name="satisfaction_2" value="5"></td>
          </tr>
          <!-- 나머지 항목들도 유사하게 추가 -->
        </table>
      </div>
      <div class="question">
        <label for="satisfaction_comments">2. (만족하지 않은 경우) 관련 애로사항 및 의견:</label>
        <textarea id="satisfaction_comments" name="satisfaction_comments" class="open-text"></textarea>
      </div>
    </fieldset>

    <!-- [이론 필수 교과목 학습 어려움] (다중 선택 예시) -->
    <fieldset>
      <legend>[이론 필수 교과목 학습 어려움]</legend>
      <div class="question">
        <p>아래의 이론 필수 교과목 중 귀하가 학습에 어려움을 경험했던 교과목은 무엇입니까? (최대 3개 선택 가능)</p>
        <div class="checkbox-group">
          <label><input type="checkbox" name="theoryDifficulty[]" value="간호학의이해"> 간호학의이해</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="글로벌사회와 건강"> 글로벌사회와 건강</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="기초간호과학 I"> 기초간호과학 I</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="생명과학의이해"> 생명과학의이해</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="가족건강"> 가족건강</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="건강사정"> 건강사정</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="건강증진과 교육"> 건강증진과 교육</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="약리학"> 약리학</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="기초간호과학II"> 기초간호과학II</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="병태생리학"> 병태생리학</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="성장발달"> 성장발달</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="의사소통론 I"> 의사소통론 I</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="간호학 I"> 간호학 I</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="간호학 II"> 간호학 II</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="간호학 III"> 간호학 III</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="간호학 IV"> 간호학 IV</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="간호학 V"> 간호학 V</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="의사소통론 II"> 의사소통론 II</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="지역사회간호학"> 지역사회간호학</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="통계학"> 통계학</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="간호관리학"> 간호관리학</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="간호연구"> 간호연구</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="간호윤리와 법"> 간호윤리와 법</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="종합시험"> 종합시험</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="리더십개발"> 리더십개발</label>
          <label><input type="checkbox" name="theoryDifficulty[]" value="임상추론"> 임상추론</label>
        </div>
      </div>
    </fieldset>

    <!-- [실습 교과목 학습 어려움] (다중 선택 예시) -->
    <fieldset>
      <legend>[실습 교과목 학습 어려움]</legend>
      <div class="question">
        <p>아래의 실습 교과목 중 귀하가 학습에 어려움을 경험했던 교과목은 무엇입니까? (최대 2개 선택 가능)</p>
        <div class="checkbox-group">
          <label><input type="checkbox" name="practicalDifficulty[]" value="건강사정 실습"> 건강사정 실습</label>
          <label><input type="checkbox" name="practicalDifficulty[]" value="임상간호실습입문 I/II"> 임상간호실습입문 I/II</label>
          <label><input type="checkbox" name="practicalDifficulty[]" value="통합간호실습 I/II"> 통합간호실습 I/II</label>
          <label><input type="checkbox" name="practicalDifficulty[]" value="통합간호실습 III/IV"> 통합간호실습 III/IV</label>
        </div>
      </div>
    </fieldset>

    <!-- [강점 및 개선사항] 섹션 (일부 예시) -->
    <fieldset>
      <legend>[강점 및 개선사항]</legend>
      <div class="question">
        <p>5. 연세대학교 간호대학의 강점은 무엇입니까? (최대 3개 선택 가능)</p>
        <div class="checkbox-group">
          <label><input type="checkbox" name="strengths[]" value="기독교 정신"> 기독교 정신</label>
          <label><input type="checkbox" name="strengths[]" value="교육과정"> 교육과정</label>
          <label><input type="checkbox" name="strengths[]" value="교육환경"> 교육환경</label>
          <label><input type="checkbox" name="strengths[]" value="교수"> 교수</label>
          <label><input type="checkbox" name="strengths[]" value="비전 제시"> 비전 제시</label>
          <label><input type="checkbox" name="strengths[]" value="교우관계"> 교우관계</label>
          <label><input type="checkbox" name="strengths[]" value="학생 사랑"> 학생 사랑</label>
          <label><input type="checkbox" name="strengths[]" value="동문들의 학교 사랑"> 동문들의 학교 사랑</label>
          <label><input type="checkbox" name="strengths[]" value="진로지도"> 진로지도</label>
          <label><input type="checkbox" name="strengths[]" value="교수-학생관계"> 교수-학생관계</label>
          <label><input type="checkbox" name="strengths[]" value="지속적 투자 및 발전"> 지속적 투자 및 발전</label>
          <label><input type="checkbox" name="strengths[]" value="성장을 위한 동기부여"> 성장을 위한 동기부여</label>
          <label><input type="checkbox" name="strengths[]" value="교과 외 활동"> 교과 외 활동</label>
          <label><input type="checkbox" name="strengths[]" value="기타"> 기타</label>
        </div>
      </div>
      <div class="question">
        <label for="strengths_etc">만약 '기타'를 선택하셨다면, 구체적으로 기재해 주십시오.</label>
        <textarea id="strengths_etc" name="strengths_etc" class="open-text"></textarea>
      </div>
      <div class="question">
        <p>7. 간호학사편입 집중과정 중 강화되어야 한다고 생각하는 것은 무엇입니까? (최대 3개 선택 가능)</p>
        <div class="checkbox-group">
          <label><input type="checkbox" name="improvement[]" value="사회봉사체험활동"> 사회봉사체험활동</label>
          <label><input type="checkbox" name="improvement[]" value="국제활동 프로그램 참여"> 국제활동 프로그램 참여</label>
          <label><input type="checkbox" name="improvement[]" value="인문학적 소양 교육"> 인문학적 소양 교육</label>
          <label><input type="checkbox" name="improvement[]" value="학제간 융합교육"> 학제간 융합교육</label>
          <label><input type="checkbox" name="improvement[]" value="의사소통 능력 증진"> 의사소통 능력 증진</label>
          <label><input type="checkbox" name="improvement[]" value="문화 역량 교육"> 문화 역량 교육</label>
          <label><input type="checkbox" name="improvement[]" value="다양한 선택교과 개설"> 다양한 선택교과 개설</label>
          <label><input type="checkbox" name="improvement[]" value="다양한 협력 및 교류 증진"> 다양한 협력 및 교류 증진</label>
          <label><input type="checkbox" name="improvement[]" value="기타"> 기타</label>
        </div>
      </div>
      <div class="question">
        <label for="improvement_etc">만약 '기타'를 선택하셨다면, 구체적으로 기재해 주십시오.</label>
        <textarea id="improvement_etc" name="improvement_etc" class="open-text"></textarea>
      </div>
      <div class="question">
        <p>9. 간호학사편입 집중과정이 귀하의 학업 시작 당시 개인적 비전/진로방향에 어느 정도 도움이 되었습니까?</p>
        <div class="radio-group">
          <label><input type="radio" name="vision_help" value="전혀 도움이 안됨" required> 전혀 도움이 안됨</label>
          <label><input type="radio" name="vision_help" value="도움이 안됨"> 도움이 안됨</label>
          <label><input type="radio" name="vision_help" value="보통임"> 보통임</label>
          <label><input type="radio" name="vision_help" value="도움이 됨"> 도움이 됨</label>
          <label><input type="radio" name="vision_help" value="매우 도움이 됨"> 매우 도움이 됨</label>
        </div>
      </div>
      <div class="question">
        <label for="vision_suggestions">10. (9번 응답을 바탕으로) 개선할 만한 교과 내용/주제 또는 개선사항을 제안해 주십시오.</label>
        <textarea id="vision_suggestions" name="vision_suggestions" class="open-text"></textarea>
      </div>
      <div class="question">
        <label for="job_competence">11. 현재 업무 수행에 필요한 직무 역량 중, 해당 과정이 얼마나 잘 준비되었다고 생각하십니까?</label>
        <textarea id="job_competence" name="job_competence" class="open-text"></textarea>
      </div>
      <div class="question">
        <p>12. 간호학사편입 집중과정을 타인에게 추천하겠습니까?</p>
        <div class="radio-group">
          <label><input type="radio" name="recommend" value="예" required> 예</label>
          <label><input type="radio" name="recommend" value="아니요"> 아니요</label>
        </div>
      </div>
      <div class="question">
        <label for="recommend_reason">13. (12번 선택 이유) 추천/비추천 이유를 기재해 주십시오.</label>
        <textarea id="recommend_reason" name="recommend_reason" class="open-text"></textarea>
      </div>
    </fieldset>

    <!-- [취업 및 진로 현황] 섹션 -->
    <fieldset>
      <legend>[취업 및 진로 현황]</legend>
      <div class="question">
        <p>1. 현재 취업한 상태입니까?</p>
        <div class="radio-group">
          <label><input type="radio" name="employment_status" value="예" required> 예</label>
          <label><input type="radio" name="employment_status" value="아니요"> 아니요</label>
        </div>
      </div>
      <div class="question">
        <p>2. 현재(최근) 근무경력 – 근무 기관을 아래 보기 중 번호로 기재하거나, 기타인 경우 직접 기재해 주십시오.</p>
        <p>
          (① 상급종합병원, ② 종합병원, ③ 병원, 의원, ④ 학교(보건교사), ⑤ 제약회사, ⑥ 공공기관, ⑦ 기업체, ⑧ 대학원, ⑨ 연구소, ⑩ 경력 없음, ⑪ 기타)
        </p>
        <input type="text" name="workplace" placeholder="예: ① 또는 기타인 경우 기재">
      </div>
      <div class="question">
        <label for="dept">3-1. 근무부서:</label>
        <input type="text" id="dept" name="dept">
        <label for="work_duration">3-2. 근무기간 (Month):</label>
        <input type="text" id="work_duration" name="work_duration">
      </div>
      <div class="question">
        <p>4. 현재 업무에 대해 얼마나 만족하십니까?</p>
        <div class="radio-group">
          <label><input type="radio" name="job_satisfaction" value="매우 불만족" required> 매우 불만족</label>
          <label><input type="radio" name="job_satisfaction" value="불만족"> 불만족</label>
          <label><input type="radio" name="job_satisfaction" value="보통"> 보통</label>
          <label><input type="radio" name="job_satisfaction" value="만족"> 만족</label>
          <label><input type="radio" name="job_satisfaction" value="매우 만족한다"> 매우 만족한다</label>
        </div>
      </div>
      <div class="question">
        <p>5. (병원 근무자 대상) 현재 부서에서 다른 부서로 이동하고 싶다, 병원을 그만두고 이동하고 싶다 등 아래 문항에 체크해 주십시오.</p>
        <table class="matrix-table">
          <tr>
            <th>문항</th>
            <th>전혀 그렇지 않다</th>
            <th>그렇지 않다</th>
            <th>보통이다</th>
            <th>그렇다</th>
            <th>매우 그렇다</th>
          </tr>
          <tr>
            <td>현재 부서에서 다른 부서로 이동하고 싶다.</td>
            <td><input type="radio" name="hospital_move_1" value="1" required></td>
            <td><input type="radio" name="hospital_move_1" value="2"></td>
            <td><input type="radio" name="hospital_move_1" value="3"></td>
            <td><input type="radio" name="hospital_move_1" value="4"></td>
            <td><input type="radio" name="hospital_move_1" value="5"></td>
          </tr>
          <tr>
            <td>현재 다니는 병원을 그만두고 다른 병원으로 이동하고 싶다.</td>
            <td><input type="radio" name="hospital_move_2" value="1" required></td>
            <td><input type="radio" name="hospital_move_2" value="2"></td>
            <td><input type="radio" name="hospital_move_2" value="3"></td>
            <td><input type="radio" name="hospital_move_2" value="4"></td>
            <td><input type="radio" name="hospital_move_2" value="5"></td>
          </tr>
          <tr>
            <td>병원 간호사가 아닌 다른 분야의 간호직으로 일하고 싶다.</td>
            <td><input type="radio" name="hospital_move_3" value="1" required></td>
            <td><input type="radio" name="hospital_move_3" value="2"></td>
            <td><input type="radio" name="hospital_move_3" value="3"></td>
            <td><input type="radio" name="hospital_move_3" value="4"></td>
            <td><input type="radio" name="hospital_move_3" value="5"></td>
          </tr>
          <tr>
            <td>간호직을 그만 두고 다른 직종의 일을 하고 싶다.</td>
            <td><input type="radio" name="hospital_move_4" value="1" required></td>
            <td><input type="radio" name="hospital_move_4" value="2"></td>
            <td><input type="radio" name="hospital_move_4" value="3"></td>
            <td><input type="radio" name="hospital_move_4" value="4"></td>
            <td><input type="radio" name="hospital_move_4" value="5"></td>
          </tr>
        </table>
      </div>
      <div class="question">
        <p>6. 대학원 진학 계획이 있으십니까?</p>
        <div class="radio-group">
          <label><input type="radio" name="grad_plan" value="예, 간호학과 대학원" required> 예, 간호학과 대학원</label>
          <label><input type="radio" name="grad_plan" value="예, 타전공 대학원"> 예, 타전공 대학원</label>
          <label><input type="radio" name="grad_plan" value="아니요"> 아니요</label>
        </div>
      </div>
      <div class="question">
        <label for="grad_reason">7. (진학 계획 선택 이유) 기재해 주십시오.</label>
        <textarea id="grad_reason" name="grad_reason" class="open-text"></textarea>
      </div>
      <div class="question">
        <label for="school_suggestions">8. 우리 간호대학의 발전을 위해 학교에 특별히 하고 싶은 말이나 제안 사항:</label>
        <textarea id="school_suggestions" name="school_suggestions" class="open-text"></textarea>
      </div>
    </fieldset>

    <!-- [일반적 특성] 섹션 -->
    <fieldset>
      <legend>[일반적 특성]</legend>
      <div class="question">
        <p>1. 성별</p>
        <div class="radio-group">
          <label><input type="radio" name="gender" value="남" required> 남</label>
          <label><input type="radio" name="gender" value="여"> 여</label>
        </div>
      </div>
      <div class="question">
        <label for="age">2. 만 나이 (숫자만 입력해주십시오)</label>
        <input type="number" id="age" name="age" required>
      </div>
      <div class="question">
        <p>3. 간호학과 졸업년도</p>
        <div class="radio-group">
          <label><input type="radio" name="grad_year" value="2023년" required> 2023년</label>
          <label><input type="radio" name="grad_year" value="2024년"> 2024년</label>
          <label><input type="radio" name="grad_year" value="2025년"> 2025년</label>
        </div>
      </div>
      <div class="question">
        <p>4. 간호학사 학위 취득에 걸린 기간</p>
        <div class="radio-group">
          <label><input type="radio" name="degree_duration" value="2년" required> 2년</label>
          <label><input type="radio" name="degree_duration" value="3년"> 3년</label>
          <label><input type="radio" name="degree_duration" value="4년 이상"> 4년 이상</label>
        </div>
      </div>
      <div class="question">
        <label for="prev_major">5. 간호학사편입 집중과정 전적 대학 전공학과</label>
        <input type="text" id="prev_major" name="prev_major">
      </div>
      <div class="question">
        <p>6. 간호학사편입 집중과정 입학 전 직장경력 여부</p>
        <div class="radio-group">
          <label><input type="radio" name="work_experience" value="예" required> 예</label>
          <label><input type="radio" name="work_experience" value="아니요"> 아니요</label>
        </div>
      </div>
    </fieldset>

    <!-- [개인정보 활용 동의 및 향후 연구참여 의향 확인] 섹션 -->
    <fieldset>
      <legend>[개인정보 활용 동의 및 향후 연구참여 의향 확인]</legend>
      <div class="question">
        <p>아래에 연락처를 기입해 주시는 분들께 소정의 기프티콘(10,000원)이 지급될 예정입니다.<br>
        연락처는 기프티콘 제공 이외의 목적으로 사용되지 않으며, 연구 종료 후 안전하게 폐기됩니다.</p>
        <div class="checkbox-group">
          <label><input type="checkbox" name="consent" value="동의함" required> 개인정보 활용에 동의합니다</label>
        </div>
      </div>
      <div class="question">
        <label for="phone">휴대폰 번호 (예: 010-0000-0000)</label>
        <input type="text" id="phone" name="phone" required>
      </div>
      <div class="question">
        <p>간호학사편입 집중과정 관련 심층 인터뷰 진행을 위해 연락을 드려도 되겠습니까? (추가 사례금 지급, 인터뷰 설명 후 참여 철회 가능)</p>
        <div class="radio-group">
          <label><input type="radio" name="interview_consent" value="예" required> 예</label>
          <label><input type="radio" name="interview_consent" value="아니요"> 아니요</label>
        </div>
      </div>
    </fieldset>

    <p style="text-align:center;">모든 설문이 종료되었습니다. 응답해 주셔서 감사합니다.</p>
    <input type="submit" value="제출하기" class="submit-btn">
  </form>
  </div>
</body>
</html>
