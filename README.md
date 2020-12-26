# graduate_project
졸업작품

셀프 AI계산대 

##작동방식: 
  
  사용자가 계산대 위에 과자를 올려놓으면 계산대가 과자를 인식하고 자동으로 계산을 해준다
  중복으로 과자를 놓아도 인식하며 복수의 물건들도 한번에 인식이 가능하다
       

##한계점: 
  
  1.편의점을 한정해서 생각해 물품의 가짓수가 15개 정도이며 동시에 물건을 두는 경우 3개부터 인식률이 떨어진다.
  2.카메라와의 거리에 따라 인식률이 달라졌다.      
        

##추가 기술: 
  
  1.yolo를 이용해 훈련시켰으며 augmentation 으로 45도씩 돌려 추가 데이터를 생산했다. 
    네이버,인스타,구글에서 데이터를 크롤링하고 augmentation으로 추가한 총 데이터 수는 1500개 정도이다.
  2.mssql에 데이터 db를 정리했고 계산대 프로그램이 sql-server 인증 방식으로 접근하게했다
  3.ui는 pyqt를 이용해 작업했으며 스레드로 바코드 인식과 물품인식을 나눠 작동하게 했다.
          
        
