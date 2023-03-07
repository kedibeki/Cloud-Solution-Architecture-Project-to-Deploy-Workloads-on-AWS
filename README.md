# Cloud-Solution-Architecture-Project-to-Deploy-Workloads-on-AWS

<h2>
Deploying Workloads on AWS
</h2>

<p align="center">
<img src="https://github.com/kedibeki/Cloud-Solution-Architecture-Project-to-Deploy-Workloads-on-AWS/blob/main/Cover-%20Cloud%20Solution%20Architecture%20Project%20to%20Deploy%20Workloads%20on%20AWS.jpg" alt=""/>
</p>

[Click On Here For My Full Presentation](https://github.com/kedibeki/Cloud-Solution-Architecture-Project-to-Deploy-Workloads-on-AWS/blob/main/Cloud%20Solution%20Architecture%20Project%20to%20Deploy%20Workloads%20on%20AWS.pdF)
 
<h2>
Project Background
</h2>

<h4>   

I’m working for a customer that runs their workloads on premises. My customer has two workloads:

&nbsp;

A three-tier architecture composed of a frontend (HTML, CSS, JavaScript), backend (Apache Web Server and a Java application), and database (MySQL). The three-tier application hosts a dynamic website that accepts user traffic from the internet.

&nbsp;

A data analytics workload that runs Apache Hadoop. The analytics workload analyzes a massive amount of data that stored on premises and it also uses visualization tools to derive insights.

&nbsp;

These components are currently running in the data center on physical servers. Currently, if a power outage occurred in the data center, all systems would be brought offline. Because of this issue (in addition to other benefits of the cloud), My customer wants to migrate all components to the cloud and, when possible, use AWS services to replace on-premises components.
![image](https://user-images.githubusercontent.com/107129424/223463692-67fbb61f-7d03-4769-bd97-41e88c1b5828.png)


</h4>

<h2>
What will I do as a Cloud Solutions Architect?
</h2>

<h4>

I have been tasked with designing a solution that uses AWS services to decouple the application layers (frontend, backend, and database), and that hosts both the application and the data analytics workload in the cloud. 

&nbsp;

I can use managed services and advocate for refactoring the code to take advantage of cloud-native technologies, or I can do a lift and shift and advocate for minimal refactoring. 

&nbsp;

Also, the data analytics solution currently runs on Hadoop and I have a requirement to spin up an Amazon EMR cluster for it. However, it’s up to me to choose which AWS services I want to use for the ingestion, storage, and visualization of data.
![image](https://user-images.githubusercontent.com/107129424/223464313-9e578ae8-e184-4beb-a8cc-9fd5b7f2f0a5.png)

</h4>


