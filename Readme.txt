1] Feature of my project

   i)This project is capable to automate execution and validation
   ii)Constructed the request body using parameters taken from an excelfile,i have created an Common utility using ApachePoi to read data from excelfile and allure result to generate the html report.
   iii)Project is constructed on the  theory of data driven and keyword driven
         .I dived the projects into four parts and make four package
            1>Request Repositry=I have encapsulated BaseURI,Requestbody,Resource.
            2>Common Method= I have fetched the statuscode and Responsebody in common method.
            3>Test Class=I used @test annotation and extracted statuscode and responsebody and we parse the response and validate the responsebody parameter.
   iv)The test execution is driven by TestNG.xml.
    v)Project is capable to save evidence of the execution inside text files which contain details of       sent request,endpoint and response received and generate easy to understand pass/fail report.
