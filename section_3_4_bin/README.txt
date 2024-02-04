                                                                                                             
      ABOOK       KCODAB    ODABOOK           ABO       OOKCODABOO      OOKCOD       DABOOK    BOOKCO   OOK    
    CODABOOKCO   OOKCODAB   CODABOOKC        ODABO      BOOKCODABOO    ABOOKCOD     CODABOOK   ABOOK    BOO    
   OKC   BOOKC  ABOO  ODAB  KCODABOOKC       CODAB      ABOOK   ABO   ODAB  KCOD   OKCO  BOOK   ABO    DA      
  BOO     BOOK  DAB    ODA  OKCO   OOKC     OKCODA        BOO   DAB   COD    KCO   OOK    BOO   DAB   CO       
  ABO          CODA    CODA  OKC   BOOK     OOK ODA       ABOOKCODA  OKCO    OKCO ABOO    ABOO  ODABOOK        
  DA           KCOD    KCOD  OOK    BOO    ABOOKCODA      DABOOKCODA OOKC    OOKC DABO    DABO  CODABOO        
  OD            KCO    OKC   BOO   DABO    DABOOKCOD      ODABOOKCODA OOK    BOO   DAB    ODA   KCODABO        
  CO       OD   OKC    OOK  DABO  CODAB   CODA   KCOD     COD    KCOD BOO    ABO   ODA    COD   OKC  ABO       
  KCO     KCO   OOKC  ABOO CODABOOKCODA   KCO     KCO     KCODABOOKCO ABOO  ODAB   CODA  OKCO   OOK  DAB       
   KCODABOOKC    OOKCODAB  KCODABOOKCO  BOOKCO   OOKCOD BOOKCODABOOK   ABOOKCOD     CODABOOK   ABOOK ODABOOK   
    KCODABO       OOKCOD   OKCODABOO    ABOOKC   BOOKCO ABOOKCODABO     ABOOKC       CODABO   ODABOO CODABOO   




*********************************************************************************************
* COMPANION CODE FOR THE BOOK “Component Oriented Development & Assembly – CODA Using Java” *
* AUTHORS – Piram Manickam, Sangeetha S, Subrahmanya S V                                    *
* REFERENCE – http://www.codabook.com                                                       *
* CODE CONTRIBUTORS – Vishal Verma, Shikhar Johari, Soumya Bardhan, Rohit Jain,		    *
*                     Karthika Nair, Vibhuti Pithwa, Vaasavi Lakshmi                        *
********************************************************************************************* 


1. The zip file you downloaded contains this README file and the binaries for the section 3.4 of the book.

2. To execute the binary, unzip the contents of the zip file into a local folder on your machine, let us name this folder - 'AgeCalculator'. The folder would contain following files:

	- AgeCalculatorSpring.jar
	- AgeCalculatorSpringClient.jar
	- README.txt


Getting the required libraries:
-------------------------------

1. First create a folder - 'lib' inside the folder - 'AgeCalculator'.
 
2. You would need SPRING LIBRARIES to run the project. You can download the latest version of Spring binaries from their website - 'http://www.springsource.org/spring-framework'. Once the download is complete, extract the zip file to '/lib' folder. The lib folder should directly contain the JAR files, without any sub-folder.
                  
3. Secondly, you would need Apache Commons Logging library. You can download the latest version from Apache website - 'http://commons.apache.org/proper/commons-logging/download_logging.cgi'. Extract the downloaded zip archive to the '/lib' folder. Again, the lib folder should directly contain the JAR files.

4. Now, check to see that your folder has following structure:

        AgeCalculator --+-- AgeCalculatorSpring.jar
                        +-- AgeCalculatorSpringClient.jar
                        +-- lib -+
                                 |
                                 +-- All the Spring JARs
                                 +-- Apache Commons Library JARs.


Running the program
-------------------

1. The program can be run from your OS console window provided the Java Runtime Environment is installed and configured. 

2. From the command prompt, navigate to the folder - 'AgeCalculator'.

3. Run the following command to start execution of the program:

      java -cp ./*;lib/* agecalculatorspringclient.AgeCalculatorSpringClient

4. Use the Age Calculator program as guided.