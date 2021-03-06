# 파일점검 에러코드

Illustrator에서 대부분의 오류는 타입라이브러리가 제대로 등록되어있지 않을 때 나타나며 그 해결방법은 다음과 같다.

```bat
:: 커맨트프롬프트를 관리자모드로 실행한다.

:: {IllustratorPath} 는 실제 사용하는 일러스트레이터의 경로로 변경후 복사해서 붙여넣는다.
:: 예) C:\Program Files\Adobe\Adobe Illustrator CC 2014\Plug-ins\Extensions\ScriptingSupport.aip

:: 한글판일경우 이럴수도 있음 -> "플러그-인\확장 모듈\스크립팅 지원.aip" 
"%windir%\Microsoft.NET\Framework\v4.0.30319\regtlibv12.exe" "{{IllustratorPath}}\Plug-ins\Extensions\ScriptingSupport.aip"

```

### CorelDRAW

| ErrorCode	| Message																																|
| --------- | --------------------------------------------------------------------------------------------------------------------------------------|
| CDR_001	| 애플리케이션이 실행되고 있지 않습니다.																									|
| CDR_002	| 열린 문서가 없습니다.																													|
| CDR_003	| 선택된 건수가 틀립니다.																													|
| CDR_004	| 제품사이즈가 틀립니다.																													|
| CDR_005	| 문서에 잠겨있는 객체가 포함되어 있습니다.																									|
| CDR_006	| 채움색상에 별색을 사용할 수 없습니다.																									|
| CDR_007	| 채움색상이 CMYK형식이 아닙니다.																											|
| CDR_008	| 계조채움안에 CMYK형식이 아닌 색상이 포함되어 있습니다.																					|
| CDR_009	| 무늬채움이 포함되어 있습니다. (무늬채움은 인쇄시 화면에서 보는 것과 다르게 출력될 수 있습니다.)												|
| CDR_010	| 채움색상을 오버프린트 하고 있습니다.																										|
| CDR_011	| 외곽선색상에 별색을 사용할 수 없습니다.																									|
| CDR_012	| 외곽선색상이 CMYK형식이 아닙니다.																										|
| CDR_013	| 외곽선이 너무 얇습니다. (얇은 외곽선은 인쇄시 흐릿하게 나올 수 있습니다.)																	|
| CDR_014	| 외곽선을 오버프린트 하고 있습니다.																										|
| CDR_015	| 내용이 없는 빈 텍스트가 사용되었습니다.																									|
| CDR_016	| 텍스트의 크기가 너무 작습니다. (텍스트가 너무 작으면 인쇄시 보기가 어려울 수 있습니다.)													 	|
| CDR_017	| 이미지의 색상형식이 잘못되어 있습니다.																									|
| CDR_018	| 이미지의 해상도가 너무 낮습니다.																											|
| CDR_019	| 외부에 연결된 이미지가 포함되어 있습니다.																									|
| CDR_020	| 투명한 이미지가 사용되었습니다.																											|
| CDR_021	| 이미지를 오버프린트 하고 있습니다.																										|
| CDR_022	| 코렐 기타 효과가 사용되었습니다. (분리하거나 비트맵으로 변환해주시기 바랍니다.)															 	|
| CDR_023	| OLE개체가 임베딩 되어있습니다. (OLE개체는 인쇄시 오류가 발생할 수 있습니다.)																|
| CDR_024	| EPS개체가 임베딩 되어있습니다. (EPS파일을 불러올때 편집가능한 상태로 불러오시기 바랍니다.)													|
| CDR_025	| 파워클립 효과가 사용되었습니다.																											|
| CDR_026	| 렌즈효과가 사용되었습니다.																												|
| CDR_027	| 인쇄할 수 없는 개체가 사용되었습니다.																									|

### Illustrator

| ErrorCode | Message																																|
| --------- |---------------------------------------------------------------------------------------------------------------------------------------|
| ILU_001	| 애플리케이션이 실행되고 있지 않습니다.																									|
| ILU_002	| 열린 문서가 없습니다.																													|
| ILU_003	| 선택된 건수가 틀립니다.																													|
| ILU_004	| 제품사이즈가 틀립니다.																													|
| ILU_005	| 문서에 잠겨있는 객체가 포함되어 있습니다.																									|
| ILU_006	| 문서에 안내선개체가 포함되어 있습니다.																									|
| ILU_007	| 채움색상에 별색을 사용할 수 없습니다.																									|
| ILU_008	| 채움색상이 CMYK형식이 아닙니다.																											|
| ILU_009	| 채움색상을 오버프린트 하고 있습니다.																										|
| ILU_010	| 외곽선색상에 별색을 사용할 수 없습니다.																									|
| ILU_011	| 외곽선색상이 CMYK형식이 아닙니다.																										|
| ILU_012	| 외곽선이 너무 얇습니다. (얇은 외곽선은 인쇄시 흐릿하게 나올 수 있습니다.)																	|
| ILU_013	| 외곽선을 오버프린트 하고 있습니다.																										|
| ILU_014	| 외곽선에 점선이 사용되었습니다. (확장 메뉴를 사용하지 않으면 실선으로 표현될 수 있습니다.)													|
| ILU_015	| 내용이 없는 빈 텍스트가 사용되었습니다.																									|
| ILU_016	| 텍스트의 크기가 너무 작습니다. (텍스트가 너무 작으면 인쇄시 보기가 어려울 수 있습니다.)													 	|
| ILU_017	| Illustrator 10 이전버전에서 작성된 텍스트가 발견되었습니다. (메뉴항목의 문자 -> 이전 텍스트 -> 모든 이전 텍스트 업데이트 명령을 사용하세요.)	|
| ILU_018	| 이미지의 색상형식이 잘못되어 있습니다.																									|
| ILU_019	| 이미지의 해상도가 너무 낮습니다.																											|
| ILU_020	| 외부에 연결된 이미지가 포함되어 있습니다.																									|
| ILU_021	| 투명한 이미지가 사용되었습니다.																											|
| ILU_022	| 이미지를 오버프린트 하고 있습니다.																										|
| ILU_023	| 메쉬개체가 포함되어 있습니다.																											|
| ILU_024	| 플러그인개체가 포함되어 있습니다.																										|
| ILU_025	| 심볼개체가 사용되었습니다. (메뉴항목의 오브젝트 -> 확장 명령을 사용하세요.)															 		|
| ILU_026	| 그래프개체가 사용중입니다.																												|
| ILU_027	| NonNativeItem개체가 포함되어 있습니다.																									|
| ILU_028	| 개체에 클리핑마스크가 사용되었습니다.																								 		|
| ILU_029	| 개체에 투명도가 적용되어 있습니다.																										|
| ILU_030	| 개체에 색상혼합효과(Blending)가 적용되어 있습니다.																					 	|
| ILU_031	| 아웃라인 하지 않은 텍스트가 발견되었습니다.																				 				|

### PDF

| ErrorCode | Message																																|
| --------- |---------------------------------------------------------------------------------------------------------------------------------------|
| PDF_001	| PDF파일이 선택되지 않았습니다.																											|
| PDF_002	| PDF파일안에 페이지 수와 주문의 내용이 다릅니다.																							|
| PDF_003	| PDF파일안에 페이지 크기와 주문의 내용이 다릅니다.																							|

### PS (.mega 파일)

| ErrorCode | Message																																|
| --------- |---------------------------------------------------------------------------------------------------------------------------------------|
| PS_001	| mega파일이 선택되지 않았습니다.																											|
| PS_002	| mega파일 이름에 정보가 없습니다.																											|
| PS_003	| mega파일정보의 페이지 수와 주문의 내용이 다릅니다.																						|
| PS_004	| mega파일정보의 페이지 크기와 주문의 내용이 다릅니다.																						|

### 기타

| ErrorCode	| Message																																|
| --------- | --------------------------------------------------------------------------------------------------------------------------------------|
| ERR_001	| 작업이 취소되었습니다.																													|
| ERR_999	| 기타																																	|
