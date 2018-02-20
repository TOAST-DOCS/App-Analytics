## Analytics > App Analytics > 개요

Analytics는 자사의 게임앱을 이용하는 유저들의 이용패턴과 다양한 지표에 대한 분석 데이터서비스를 지원합니다.<br />
Analytics가 제공하는 분석데이터를 이용하시려면 앱 등록 후, Analytics에서 제공하는 SDK 적용이 필요합니다. (SDK는 iOS, 안드로이드, Unity를 지원합니다.)

## 서비스구조

Analytics SDK는 앱 이용자 로그를 수집합니다. Analytics 분석 시스템은 SDK로부터 로그를 수집/분석합니다.

![그림 1 서비스구조도](https://raw.githubusercontent.com/ToastAnalytics/ToastAnalytics/master/docs/Developer/images/an_1.png)<br>
[그림 1 서비스구조도]

Analytics는 TOAST Cloud 웹 콘솔에서 시작하시거나, 바로 Analytics 사이트에서 시작하실 수 있습니다. Analytics 만을 사용하는 이용자는 Analytics 사이트 (<http://analytics.toast.com>) 에서, TOAST Cloud 상품을 이용하는 이용자는 TOAST Cloud 웹콘솔(<http://console.toast.com>)에서 바로 시작하실 수 있습니다. <br />
이 문서는 Analytics 사이트로 직접 접속하는 경우 위주로 설명합니다. TOAST Cloud 웹콘솔에서 시작하는 경우는 TOAST Cloud Console에서 시작하기를 참조해주세요.

## 마케팅 가이드

 마케팅 담당자는 마케팅 실행 후 유입된 이용자를 모니터링하고 성과를 측정할 도구가 필요합니다.

 TOAST Analytics에서는

- 간편하게 트래킹 URL을 발급하여 채널별 유입되는 이용자를 실시간으로 모니터링할 수 있습니다.
- Post-Install 성과측정을 위한 다양한 분석지표와 LTV 예측지표를 제공합니다.
- 채널별 비교분석을 통해서 효율이 높은 채널을 믹스하여 운영할 수 있습니다.

<br>** * 본 마케팅 운영 가이드는 상황에 맞춰 필요한 부분을 Quick하게 이용할 수 있습니다.**

|상황|가이드|
|:---|:---|
|1) 마케팅 트랙킹 기능을 처음 사용해보거나, 개념 이해가 필요한 경우|[마케팅 트래킹 소개] [트래킹 URL 발급] [채널 추가]|
|2) MAT, Appsflyer 를 통해 광고를 집행한 경우|	[트래킹 URL 발급] [3rd Party Tracker 추가] [3rd Party Tracker Postback 설정]|
|3) 구글 애드워즈에 광고를 집행한 경우|[트래킹 URL 발급] [구글애드워즈 광고트래킹]|
|4) 페이스북에 광고를 집행한 경우|	[트래킹 URL 발급] [페이스북 광고 트래킹]|
|5) TOAST Analytics에서 수집된 이벤트(install)를 전달받고자 하는 경우|[파트너사 Postback 데이터 전송]|
