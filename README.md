[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url] 
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/Aboalia/NRPM-Addon">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">[Receivable - Payable Notes Management (RPN)] Add-on</h3>

  <p align="center">
    An Cheque or Notes Processing Project on MEA localization 
    <br />
    <a href="https://github.com/Aboalia/NRPM-Addon"><strong>Explore the Project»</strong></a>
    <br />
    <br />
    <a href="https://github.com/Aboalia/NRPM-Addon">View Demo</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Here's why</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
1. Here, the process of receiving Cheques in the company's treasury from the customer, whether it is one or more.

[![Receiving Cheques][product-screenshot01]]()

2. a Journal entry is made, which is summarized in increasing the intermediary 'Received Cheques Account' with the total value of the checks and decreasing the customer’s debt with the same value.

[![Receiving Cheques][product-screenshot02]]()

3. Here, the selected Cheque will return to the customer due to insufficient funds, for example, or the customer paid the check value in cash.

[![Receiving Cheques][product-screenshot03]]()

4. A journal entry is made, the value of which is combined from the check to be returned, thus increasing the customer's indebtedness.

[![Receiving Cheques][product-screenshot04]]()



### Built With

Add-ons/plugins Developed by:
* [SAP Business One SDK](https://www.sap.com/mena/products/business-one.html)
* [Microsoft C#](https://dotnet.microsoft.com/learn/csharp)
* [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-2019)



<!-- GETTING STARTED -->
## Here`s Why
SAP Business One standard does not Applicable to Egyptian Customer and Vendors they usually refuse to totally pay the Cheques and pay it in installment payments or cases of returning the check from the bank due to insufficient balance so we develop an integrated [Receivable Cheques or Payable Cheques] Add-on to solve the Egyptian Customer & Vendors issues.

### Installation
Get Os And Database type
1. Windows Server
 ```sh
   https://www.microsoft.com/en-us/evalcenter/evaluate-sql-server-2019?filetype=EXE
   ```
2. SQL Server
   ```sh
   https://www.microsoft.com/en-us/evalcenter/evaluate-sql-server-2019?filetype=EXE
   ```
OR version For HANA
1. Linux
    ```sh
   https://www.suse.com/download/sle-sap/
   ```
   
2. HANA DB
   ```sh
   https://launchpad.support.sap.com/#/softwarecenter
   ```
   
3. Get a SAP Business One Client at 
 ```sh
   https://www.sap.com/mena/products/business-one.html
   ```
4. Assgin Addon to Sld throw Extension Manager
   ```sh
   https://[Domain]:40000/ExtensionManager/
   ```


<!-- CONTACT -->
## Contact

Your Name - [LinkedIn]( https://www.linkedin.com/in/engabo3lia/) - Ahmed.Aboalia2015@gmail.com

Project Link: [Project Link](https://github.com/Aboalia/NRPM-Addon)




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/Aboalia/NRPM-Addon/network/members
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/Aboalia/NRPM-Addon/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/Aboalia/NRPM-Addon/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/Aboalia/NRPM-Addon/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/Aboalia/NRPM-Addon/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/engabo3lia/
[product-screenshot01]: images/ScreenShot01.PNG
[product-screenshot02]: images/ScreenShot02.PNG
[product-screenshot03]: images/ScreenShot03.PNG
[product-screenshot04]: images/ScreenShot04.PNG


