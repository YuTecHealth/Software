# Software

## TriBLE Default Firmwares / Apps

 ### Using TriBLE with TriAnswer child boards
  
  **Q**: What are TriAnswer child boards? 
  
  **A**: Analog front-end solutions aim to ease the bio-signal measurement. - [**Trianswer**](https://www.yutechealth.com/trianswer_en.html) (Order here)  

  **Q**: How to use TriBLE with TriAnswer child boards?
  
  **A**: A TriBLE has 3 channels for connecting with child boards. The channel name and its characteristic UUID are shown in the following figure. 
  To simply get the data with TriAnswer child boards, we provide two factory default firmwares and the corresponding APP. Please follow the **firmware setting steps** and **APP using steps**
  <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/TriBLE_w_Child.png" align="middle"
    alt="Yutech logo" width="1000" height=""></code>
  
  
	
 1. For **wireless** communication
  
    - Firmware: 
	
      - **TriAnswer BLE FW - Ver.H** (Factory default setting of TriBLE)
				 
    - APP:
	
      - **Android (TriAnswer SCR APP)**
  
      - **iOS (TriBLE Monitor APP)**
  
      - **PC (TriAnswer TCR APP)**
		
 2. For **wired** communication
  
    - Firmware:
  
      - **TriAnswer UART FW - Ver.S** 
				 
    - APP:
  
      - **PC (TriAnswer TCR APP)**
 
 
 ### App using steps
 1. Intall the APP. 
 
    - Download here: 
	
	  - [**Android:**](https://github.com/YuTecHealth/TriAnswer-SCR-APP/raw/main/TriAnswer_SCR_speedInfo.apk) <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/TriAnswer_SCR_APP_QR.png" align="middle" 
alt="Yutech logo" width="200" height=""></code>
	  
	  - **iOS:**  App Store > Search [**TriBLE**](https://apps.apple.com/tw/app/trible/id1532572637) and download <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/TriAnswer_iOS_download.png" align="middle" 
alt="Yutech logo" width="200" height=""></code>
	  
	  - **PC:** Click [here](https://drive.google.com/file/d/1zl-DEultRcGqctC-qeT3eFK8n2D576jf/view?usp=sharing)
	
 2. Power on TriBLE
 3. Launch the App you want to use and follow the guidelines in [video](https://www.youtube.com/watch?v=2cSzfthJ7Kk).
 
 <!--
 #### Android TriAnswer SCR using guidelines
 
 - Android TriAnswer SCR is a single channel waveform monitor and recorder
	
 - Operation procedure
	
   - Type in the UUID of the channel you want to monitor (A003~A001) in the **Char UUID** box
	  
   - Press **Set UUID** to lock the setting	  
   
   - Choose **Allow Output file** and click **Create File** to save data
   
   - Press **Scan** and choose your **TriBLE**
   
   - Choose the sampling rate
   
   - Remember click **Disconnect** after measurement
   
   - 
	  
 #### iOS TriBLE using guidelines
 #### PC TriAnswer TCR using guidelines
 
 
 <code><img src="https://github.com/YuTecHealth/YuTecHealth/blob/master/Asset/TriBLE_nRF52_Arduino/readme_8.png" align="middle"
    alt="Yutech logo" width="1000" height=""></code>
