# Scripts

#drop_empty_folder_here.bat

1. VaM.exe와 같은 폴더에 #drop_empty_folder_here.bat 파일을 넣는다  

2. VAM폴더 외부의 다른곳에 비어있는 새 폴더를 만든다  

3. 비어있는 새 폴더를 #drop_empty_folder_here.bat 파일 위로 드래그 앤 드랍  

4. 관리자 권한을 요청하는데 <a href="https://ko.wikipedia.org/wiki/%EC%8B%AC%EB%B3%BC%EB%A6%AD_%EB%A7%81%ED%81%AC">심볼릭 링크</a> 생성시 관리자 권한이 필요함  

스크립트가 적절하게 복사와 링크를 생성  
기본 var패키지는 복사 후 모두 hide 설정함  
씬 브라우저에서 Show Hidden 해야 보인다

  현재 1.20.77.9버전 기본 var패키지들  
  AcidBubbles.Timeline.210.var  
  DJ.NailPolish.1.var  
  DJ.TanLines.1.var  
  Jackaroo.SmartSuitJaR.1.var  
  JayC_Re-animator.Hair_Curly_Bob.1.var  
  MacGruber.Life.12.var  
  MeshedVR.3PointLightSetup.1.var  
  MeshedVR.AssetsPack.1.var  
  MeshedVR.BonusScenes.9.var  
  MeshedVR.DemoScenes.2.var  
  MeshedVR.OlderContent.1.var  
  MeshedVR.PresetsPack.2.var  
  NoOC.Clothing_SailorLingerie.2.var  
  NoStage3.Hair_Long_Upswept_Top_Bun.1.var  
  NoStage3.UnityAssetVamifier.20.var  
  Vince.Clothing_PleatedSkirtV2T.2.var  
  Xstatic.MegaParticlePack.1.var  

테스트 할 파일들 복사해서 쓰다가
다쓰고 나면 테스트했던 파일들은 빼놓고 새로 만들었던 폴더 통째로 지우면 된다

임시파일 2개 생성 후 자동 삭제 됨  
%temp%\getadmin.vbs 관리자 권한 요청용 VB스크립트  
.\\#drop_empty_folder_here.ps1 실제 작업용 파워셸 스크립트  

파워셸 스크립트는 기본적으론 드래그 앤 드랍이 안되기 때문에 배치파일로 드래그 앤 드랍을 받아서 넘겨주는 식으로 구현  
Cache를 제외한 다른 심볼릭 링크를 폴더에 걸지 않고 파일에 건 이유  
'예전에 디렉토리 심볼릭 링크를 걸어놨더니 누군가 굳이 디렉토리 내부로 들어가서 실제 파일을 지우는 일이 있었음'  
  
