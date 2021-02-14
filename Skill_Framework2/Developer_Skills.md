소프트웨어 개발자 역량평가 기준표
============================
# 개요
## 문서의 목적
- 이 문서는 "새로운 소프트웨어 개발자 교육플랫폼"을 구축하기 위한 정보수집 목적으로 작성되었습니다.
- 아래 내용은 학습된 역량을 평가하고 안내하기 위한 기준으로 사용될 예정입니다.

## 새로운 역량 기준표의 필요성
- (Realworld Assessment) 교육을 통해 육성된 스킬평가의 기준이 현장에서 평가되는 것과 동일하고자 함.

## Q&A
- 국가직무능력표준를 사용하지 않는 이유는
   - 국가직무능력표준은 직무별로 개발자를 구분하고 있어 정책 수립에 유리함.
   - 기업은 사업환경이 계속 변하므로 직무에 따라 채용을 하지 않음
- 기업채용시 평가기준은?
   - 일을 할 수 있는 스킬의 경험을 기준으로 판단함.
   - 예를 들어 "DB엔진니어(상)" 이렇게 채용하지 않고, "MySQL 숙련자" 이렇게 채용함
   - 일반적으로 2~3개 이상의 직무를 하고 있고, 직무의 경계도 모호함

## 작성 기준
- 기업현장, 개발자들이 현장에서 평가하고 채용하는 내용을 기준으로 수집하고자 합니다. (헷갈린다면 채용기술서 기준이라고 생각)
- 기초데이터는 [StackOverflow 2020년 개발자 관련조사](https://insights.stackoverflow.com/survey/2020)를 기준으로 작성했습니다.(전세계 65,000명 응답)
- 각 항목별 시각이 산업별로 부르는게 다를 수 있어 주관적인 의견을 환영합니다.
- 이 논의에 도움주실분을 기다립니다. (PR로 참여를 부탁드립니다.)


# 개발자 유형 Developer Type

## 작성 기준
- 기업현장, 개발자들이 현장에서 평가하고 채용하는 내용을 기준으로 수집하고자 합니다.
- 일반적으로 하나의 유형에는 필수적으로 익혀야 할 "기술세트(하드스킬 + 소프트스킬)"가 있습니다.
- 기초데이터는 StackOverFlow에서 개발자들이 응답한 전체 내용으로 기술되었습니다.


|구분|직업군|설명|
|---|---|---|
|Developer|||
||back-end|서버와 데이터베이스 등 사용자 입출력외에서 발생되는 제반로직에 관련된 기술들|
||full-stack|특정 종류의 어플리케이션을 만들기 위해 필요한 솔루션, 소프트웨어 스택을 전반적으로 사용할 줄 아는 것|
||front-end|웹, 앱 등 사용자에 대한 입출력과 그에 관계된 제반로직에 대한 기술들|
||desktop or enterprise applications|윈도우 프로그래밍 등, 단독어플리케이션을 개발하는 기술들|
||mobile|스마트폰 위에서 운용되는 앱을 개발하는 기술들|
||embedded appliacations|자동차, 로봇 등의 내부에서 운용되는 어플리케이션을 개발하는 기술들|
||QA or test|어플리케이션의 동작품질을 전반적으로 검사하여 무중단 서비스 및 제품의 무결성을 높이는 기술들|
||game or graphics|게임을 만드는 데 특화된 기술들|
|Engineering|||
||DevOps specialist|개발된 내역이 운영에 매끄럽게 반영할 수 있는 전략을 운용함으로써 서비스가 계속 진화할 수 있도록 하는 제반기술들|
||Database administrator|데이터베이스 어플리케이션 및 데이터 운영에 대한 총괄기술들|
||System administrator|서버 시스템에 대한 전반적인 기술관리자|
|Data|||
||Data or business analyst|데이터 및 비즈니스 분석가|
||Data scientist or machine learning specialist|사업에 도움이 되도록 데이터에 숨겨진 것들을 발견하는 발견자|
||Data Engineer|여러가지 필요에 따라 데이터를 정리, 변환 등을 처리하는 기술자|
|Non-Developer|||
||Designer|웹 디자이너|
||Academic Researcher|학문적 연구자|
||Educator|교육자|
||Engineering manager|기술관리자|
||Product Manager|제품 관리자|
||Scientist|(찐) 과학자|
||Engineer, site reliability|SRE, 소프트웨어와 프로그래밍을 통해 시스템 운용을 자동화하는 사람 (그래서 시스템 신뢰성을 확보하는 사람)|
||Senior executive/VP|IT 임원|
||Marketing or sales professional|IT 마케팅 전문가|


# 개발기술 Developer Skills

## 작성 기준
- 기업현장, 개발자들이 현장에서 평가하고 채용하는 내용을 기준으로 수집하고자 합니다.
- 기술 숙련도에 대한 평가는 기업별로 개발자별로 상이할 수 있습니다.
- 그럼에도 불구하고 개발자분들의 "주관적 의견"을 모으고자 합니다.
- 기초데이터는 StackOverFlow에서 개발자들이 응답한 전체 내용으로 기술되었습니다.

## Q&A
- 스킬이 왜 이거밖에 없나?
   - StackOverFlow 기준이며 한국개발자도 0.32% 참여했습니다.
   - 벤더 솔루션 기반의 기술은 기재되지 않았습니다.
- 협업툴도 중요한가?
   - 협업툴은 "힘께 일하는 스킬"에 대한 내용이므로 같은 무게로 다루어집니다. 
   - StackOverFlow 기반이므로 오픈된 협업툴 응답률이 높습니다.
- "구분"항목 (언어/웹프레임워크/기타프레임워크/DB스킬/협업툴)에 대한 변경은?
   - 추가변경될 수도 있지만, 국제트렌드와 맞추기 위해 StackOverFlow와 가능하면 맞추려고 합니다.

|구분|항목|하|중하|중중|중상|상|
|---|---|---|---|---|---|---|
|Language||||||  <!-- Language -->
||JavaScript|||||
||HTML/CSS|||||			
||SQL|||||		
||Python|||||
||JavaScript|||||
||Bach/Shell/PowerShell|||||
||C#|||||
||PHP|||||
||TypeScript|||||
||C++|||||
||C|||||
||Go|||||
||Kotlin|||||
||Ruby|||||
||Assembly|||||
||VBA|||||
||Swift|||||
||R|||||
||Rust|||||
||Objective-C|||||
||Dart|||||
||Ladder|||||
||Perl|||||
||Haskell|||||
||Julia|||||
|Web Framework|||||| <!-- Web Framework -->
||jQuery|||||
||React.js|||||
||Angular|||||
||ASP.NET|||||
||Express|||||
||ASP.NET Core|||||
||Vue.js|||||
||Spring|||||
||Angular.js|||||
||Django|||||
||Flask|||||
||Laravel|||||
||Ruby on Rails|||||
||Symfony|||||
||Gatsby|||||
||Drupal|||||
|Other Framework|||||| <!-- Other Framework -->
||Node.js|||||
||.NET|||||
||.NET Core|||||
||Pandas|||||
||TensorFlow|||||
||React Native|||||
||Unity 3D|||||
||Ansible|||||
||Flutter|||||
||Teraform|||||
||Hard|||||
||Cordova|||||
||Xamarin|||||
||Apache Spark|||||
||Torch/PyTorch|||||
||Hadoop|||||
||Unreal Engine|||||
||Puppet|||||
||Chief|||||
|Database Skills|||||| <!-- Database Skills -->
||MySQL|||||
||PostgreSQL|||||
||MS SQL Server|||||
||SQLite|||||
||MongoDB|||||
||Redis|||||
||MariaDB|||||
||Oracle|||||
||Firebase|||||
||Elasticsearch|||||
||DynamoDB|||||
||Cassandra|||||
||IBM DB2|||||
||Couchbase|||||
|Developer Platform|||||| <!-- Developer Platform -->
||Linux|||||
||Windows|||||
||Docker|||||
||AWS|||||
||Android|||||
||MacOS|||||
||Rasberry Pi|||||
||Microsoft Azure|||||
||WordPress|||||
||Google Cloud Platform|||||
||iOS|||||
||Governors|||||
||Heroku|||||
||Arduino|||||
||Slack Apps and Integrations|||||
||IBM Cloud or Watson|||||
|Cooperation Tools||||||  <!--Cooperation Tools -->
||Github|||||				
||Slack|||||
||Jira|||||			
||Google Suite(Docs, Meet, etc)|||||
||Gitlab|||||
||Gonfluence|||||
||Trello|||||
||Microsoft Teams|||||
||Microsoft Azure|||||
||Stack Overflow for Teams|||||
||Facebook Workplace|||||


