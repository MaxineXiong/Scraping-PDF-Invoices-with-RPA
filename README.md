### UiPath RPA Robot
# Scraping PDF Invoices

[![GitHub](https://badgen.net/badge/icon/GitHub?icon=github&color=black&label)](https://github.com/MaxineXiong)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform - UiPath RPA](https://img.shields.io/badge/Platform-UiPath_RPA-fa4616)](https://www.uipath.com)

<br/>

This repository houses an automation solution that harnesses the power of **[UiPath Automation Platform](https://www.uipath.com/)** to effortlessly **scrape data**, including *Company Name, Invoice Number, Date, Customer ID, Payment Terms*, and *Total Amount*, from a substantial batch of **1000 invoices issued to different customers**. The extracted data is then intelligently compiled and stored in the **invoices_data.xlsx** Excel file, offering a streamlined alternative to the laborious and time-consuming task of manually collecting and entering data from these invoices. Additionally, the RPA solution categorizes the successfully and unsuccessfully scraped invoices into separate folders. Impressively, this RPA robot completes the entire process in just **approximately 130 minutes**, achieving nearly **100% accuracy**, a task that would otherwise require days of human effort.

This repository includes solutions created using both **Classic Design** and **Modern Design** in UiPath Studio. _You can check out the **automation demo video** below_:


https://github.com/MaxineXiong/Scraping-PDF-Invoices-with-RPA/assets/55864839/25ec1db4-d02c-4ff1-8dfa-7f68e3002ecb


<br/>


## **Installation**

Before installing **UiPath Softwares**, please make sure your system meets the hardware and software requirements outlined in the **[UiPath documentation](https://docs.uipath.com/studio/standalone/2022.10/user-guide/hardware-and-software-requirements)**.

The **Uipath Platform** includes the following tools:

- **UiPath Studio**
- **UiPath Assistant**
- **UiPath Automation Cloud, including UiPath Orchestrator**

<details>  
<summary> To run this project successfully, please follow these steps to install UiPath Studio:
</summary>

***

Step 1 : Visit [uipath.com](https://www.uipath.com/) and click **Try UiPath Free** button.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_1.png">
</p>

Step 2: **Sign up** for a personal account.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_2.png">
</p>  

Step 3: **Verify** your account in email.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_3.png">
</p>  

Step 4: **Log into** the **UiPath Automation Cloud** using your account, and click the **Download Uipath Studio** button.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_4.png">
</p>   

Step 5: Click **Sign in**.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_5.png">
</p>    

Step 6: Select **UiPath Studio Pro**.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_6.png">
</p>  

Step 7: Follow the system instructions to complete the installation of **UiPath Studio Pro**.
<p align="center">
<img width="900" src="https://github.com/YenLinWu/RPA_UiPath/blob/master/Installation/README_Images/Install_UiPath_Studio_7.png">
</p> 

</details> 

<br/>

## **Usage**

To run the RPA workflow on your local machine, follow these steps:

1. Either **download** this repository to your local machine or **clone** it directly within your UiPath Studio.
2. Open the **UiPath Studio** software on your machine.
3. Locate and **open** either **Main_modern.xaml** or **Main_classic.xaml** file from the downloaded repository in **UiPath Studio**.
4. **Run** the **Main.xaml** file to initiate the invoice scraping process.

<br/>

## **Acknowledgement**

I would like to express my gratitude to the **[UiPath community](https://community.uipath.com/)** for providing resources, tutorials, and a platform for automation enthusiasts to learn and collaborate.

<br/>

## **License**

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/), which means you're free to modify, distribute, and use the code in your own projects.

