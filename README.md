# Duet AI Playbooks

| Blueprints for Duet AI assisted use-cases on Google Cloud |
| ------------- |

[![Reference](https://img.shields.io/badge/Reference-DuetAI%20Official%20Documentation-purple.svg)](https://cloud.google.com/duet-ai/docs)



```diff
+ Develop & Deploy a Python App on Cloud Run +
```
<!-- Raw HTML Table -->
<table>
  <thead>
    <tr>
      <th>Use Case</th>
      <th>Persona</th>
      <th>Video Demo</th>
      <th>Duet AI Prompts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="8" style="background-color: #FFD700;">Develop & Deploy a Python App on Cloud Run</td>
      <td rowspan="8">Developer</td>
      <td rowspan="8"><a href="https://www.youtube.com/watch?v=ch4YqJ2kAyU"><img src="https://img.youtube.com/vi/ch4YqJ2kAyU/0.jpg" alt="Video 1"></a></td>
    </tr>
    <tr><td>How do I create a new Cloud Run app in Cloud Code using the command palette of cloud code? What languages are supported?</td></tr>
    <tr><td>Create a variable called inventory which is a list of 3 JSON objects. Each JSON object has 2 attributes: productid and onhandqty. Both attributes are strings.</td></tr>
    <tr><td>Modify the flask import statement to add the inventory.py file and the jsonify library and import inventory</td></tr>
    <tr><td>Generate an app route to display a list of inventory items in json format from the inventory.py file. Use the GET method.</td></tr>
    <tr><td>Is there a cloud run local emulator?</td></tr>
    <tr><td>How can I use cloud run local emulator using the command palette for VScode?</td></tr>
    <tr><td>How can I deploy the app to cloud run using the command palette for VScode?</td></tr>
  </tbody>
</table>



```diff
+ GCloud Commands on Cloud Shell +
```
<!-- Raw HTML Table -->
<table>
  <thead>
    <tr>
      <th>Use Case</th>
      <th>Persona</th>
      <th>Video Demo</th>
      <th>Duet AI Prompts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="8" style="background-color: #FFD700;">GCloud Commands on Cloud Shell</td>
      <td rowspan="8">Developer / DevOps / Sysadmin / MLOps</td>
      <td rowspan="8"><a href="https://www.youtube.com/watch?v=ch4YqJ2kAyU"><img src="https://img.youtube.com/vi/ch4YqJ2kAyU/0.jpg" alt="Video 1"></a></td>
    </tr>
    <tr><td>How can I use gcloud commands to list all Cloud Storage buckets in a project and their sizes?</td></tr>
    <tr><td>Create a gcloud command to give the developer Google group access to view my Google Cloud project.</td></tr>
    <tr><td>Change that to editor access.</td></tr>
    <tr><td>Generate gcloud command to list VM instances and filter out the terminated ones.</td></tr>
    <tr><td>Explain the gcloud commands for creating and managing Cloud AI Platform custom training jobs.</td></tr>
    <tr><td>Show me how to use gcloud to configure and manage Cloud Monitoring dashboards for monitoring various Google Cloud resources.</td></tr>
    <tr><td>Guide me through the process of setting up Cloud Shell for automatic project configuration and environment setup using gcloud.</td></tr>
  </tbody>
</table>


```diff
+ Jenkins Declarative Pipeline Creation +
```

<!-- Raw HTML Table -->
<table>
  <thead>
    <tr>
      <th>Use Case</th>
      <th>Persona</th>
      <th>Video Demo</th>
      <th>Duet AI Prompts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="4" style="background-color: #FFD700;">Jenkins Declarative Pipeline Creation</td>
      <td rowspan="4">DevOps</td>
      <td rowspan="4"><a href="https://www.youtube.com/watch?v=ch4YqJ2kAyU"><img src="https://img.youtube.com/vi/ch4YqJ2kAyU/0.jpg" alt="Video 1"></a></td>
    </tr>
    <tr><td>Write a Jenkinsfile to demonstrate declarative stages of a build for a Java application.</td></tr>
    <tr><td>Uses echo commands to demonstrate CI/CD instead of real deployments.</td></tr>
  </tbody>
</table>

```diff
+ Using Duet AI as a Pair Programmer for ETL Application on Python & Deploy to Cloud Functions +
```
<!-- Raw HTML Table -->
<table>
  <thead>
    <tr>
      <th>Use Case</th>
      <th>Persona</th>
      <th>Video Demo</th>
      <th>Duet AI Prompts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="10" style="background-color: #FFD700;">Using Duet AI as a Pair Programmer for ETL Application on Python & Deploy to Cloud Functions</td>
      <td rowspan="10">Backend Developer / Data Engineer</td>
      <td rowspan="10"><a href="https://www.youtube.com/watch?v=ch4YqJ2kAyU"><img src="https://img.youtube.com/vi/ch4YqJ2kAyU/0.jpg" alt="Video 1"></a></td>
    </tr>
    <tr><td>Function that downloads a JSON file from a GCS bucket.</td></tr>
    <tr><td>Function that takes a dictionary and transforms the value of the 'date' key from DD-MM-YYYY to YYYY-MM-DD format.</td></tr>
    <tr><td>Create a requirements.txt for my code.</td></tr>
    <tr><td>Create unit tests for my code.</td></tr>
    <tr><td>Modify this code so that it runs on a Cloud Function gen 2. The code's main function will be triggered when a new file is uploaded to a GCS bucket.</td></tr>
    <tr><td>How do I deploy this code to Cloud Function?</td></tr>
    <tr><td>How do I apply the principle of least privilege to this Cloud Function?</td></tr>
    <tr><td>Which IAM permissions do I need to run this code?</td></tr>
    <tr><td>How do I restart cold starts in my Cloud Function?</td></tr>
  </tbody>
</table>

```diff
+ Logs & Debugging +
```
<!-- Raw HTML Table -->
<table>
  <thead>
    <tr>
      <th>Use Case</th>
      <th>Persona</th>
      <th>Video Demo</th>
      <th>Duet AI Prompts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="3" style="background-color: #FFD700;">Logs & Debugging</td>
      <td rowspan="3">Operations / Developer</td>
      <td rowspan="3"><a href="https://www.youtube.com/watch?v=ch4YqJ2kAyU"><img src="https://img.youtube.com/vi/ch4YqJ2kAyU/0.jpg" alt="Video 1"></a></td>
    </tr>
    <tr><td>Explain this log entry in 3 to 5 bullet points</td></tr>
    <tr><td>Suggest steps to prevent this error</td></tr>
  </tbody>
</table>

```diff
+ Deploy a Netdata Monitoring App on a VM +
```
<!-- Raw HTML Table -->
<table>
  <thead>
    <tr>
      <th>Use Case</th>
      <th>Persona</th>
      <th>Video Demo</th>
      <th>Duet AI Prompts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="3" style="background-color: #FFD700;">Deploy a Netdata Monitoring App on a VM</td>
      <td rowspan="3">Developer / DevOps / Sysadmin</td>
      <td rowspan="3"><a href="https://www.youtube.com/watch?v=ch4YqJ2kAyU"><img src="https://img.youtube.com/vi/ch4YqJ2kAyU/0.jpg" alt="Video 1"></a></td>
    </tr>
    <tr><td>Write a shell script to install Netdata on Docker</td></tr>
    <tr><td>Explain the deployment process in 3 to 5 bullet points</td></tr>
  </tbody>
</table>


```diff
+ Microservices Deployment on Kubernetes +
```

<!-- Raw HTML Table -->
<table>
  <thead>
    <tr>
      <th>Use Case</th>
      <th>Persona</th>
      <th>Video Demo</th>
      <th>Duet AI Prompts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="12" style="background-color: #FFD700;">Microservices Deployment on Kubernetes</td>
      <td rowspan="12">Full Stack Web Developer</td>
      <td rowspan="12"><a href="https://www.youtube.com/watch?v=ch4YqJ2kAyU"><img src="https://img.youtube.com/vi/ch4YqJ2kAyU/0.jpg" alt="Video 1"></a></td>
    </tr>
    <tr><td>What's the gcloud command for creating a zonal GKE cluster with a custom number of nodes and custom machine type?</td></tr>
    <tr><td>Can you explain the contents of this repo https://github.com/GoogleCloudPlatform/microservices-demo?</td></tr>
    <tr><td>What is a Logs Explorer query to search for logs from Pods in a namespace called "default"?</td></tr>
    <tr><td>How can I build a private build environment that is not connected to the internet in Google Cloud? I want to be able to use Docker to build my container images in this environment.</td></tr>
    <tr><td>What is a Cloud Build private pool?</td></tr>
    <tr><td>Can you give me a gcloud command to create my first Cloud Build private pool?</td></tr>
    <tr><td>Can you show me an example of a Cloud Build private pool config file?</td></tr>
    <tr><td>What does the egressOption field do?</td></tr>
    <tr><td>If I create a private pool with NO_PUBLIC_EGRESS enabled, can I use Artifact Registry to host my packages privately and access them from a private pool?</td></tr>
    <tr><td>How can I use gcloud to create a private Docker repository for container images in Artifact Registry?</td></tr>
    <tr><td>Is the kms-key parameter optional for "gcloud artifacts repository create" if I don't need encryption?</td></tr>
  </tbody>
</table>

```diff
+ Architecting a GKE Autopilot Cluster to Deploy a Web App +
```

<!-- Raw HTML Table -->
<table>
  <thead>
    <tr>
      <th>Use Case</th>
      <th>Persona</th>
      <th>Video Demo</th>
      <th>Duet AI Prompts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="7" style="background-color: #FFD700;">Architecting a GKE Autopilot Cluster to Deploy a Web App</td>
      <td rowspan="7">Architect</td>
      <td rowspan="7"><a href="https://www.youtube.com/watch?v=ch4YqJ2kAyU"><img src="https://img.youtube.com/vi/ch4YqJ2kAyU/0.jpg" alt="Video 1"></a></td>
    </tr>
    <tr><td>How do I create a GKE Autopilot cluster?</td></tr>
    <tr><td>What is the command to create a GKE Autopilot cluster in my current project and in the us-central region named duet-ai-demo using the gcloud CLI?</td></tr>
    <tr><td>What is the kubectl command to create a deployment called hello-server for the image us-docker.pkg.dev/google-samples/containers/gke/hello-app:1.0?</td></tr>
    <tr><td>What is the kubectl command to expose this deployment on port 80 and target port 8080 with a load balancer?</td></tr>
    <tr><td>What is the kubectl command to see the external IP address associated with this load balancer?</td></tr>
    <tr><td>What is the kubectl command to see the external IP address associated with this load balancer?</td></tr>
  </tbody>
</table>


```diff
+ Identify Security Misconfigurations on GKE with Duet AI +
```
<!-- Raw HTML Table -->
<table>
  <thead>
    <tr>
      <th>Use Case</th>
      <th>Persona</th>
      <th>Video Demo</th>
      <th>Duet AI Prompts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="4" style="background-color: #FFD700;">Identify Security Misconfigurations on GKE with Duet AI</td>
      <td rowspan="4">Security Engineer</td>
      <td rowspan="4"><a href="https://www.youtube.com/watch?v=ch4YqJ2kAyU"><img src="https://img.youtube.com/vi/ch4YqJ2kAyU/0.jpg" alt="Video 1"></a></td>
    </tr>
    <tr><td>What services in Google Cloud can help me identify areas to improve security for a set of microservices running in a GKE cluster?</td></tr>
    <tr><td>How does Security Command Center define a vulnerability?</td></tr>
    <tr><td>How do control plane authorized networks work in GKE?</td></tr>
  </tbody>
</table>

```diff
+ Architecture & Design Help +
```

<!-- Raw HTML Table -->
<table>
  <thead>
    <tr>
      <th>Use Case</th>
      <th>Persona</th>
      <th>Video Demo</th>
      <th>Duet AI Prompts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="7" style="background-color: #FFD700;">Architecture & Design Help</td>
      <td rowspan="7">Architect</td>
      <td rowspan="7"><a href="https://www.youtube.com/watch?v=ch4YqJ2kAyU"><img src="https://img.youtube.com/vi/ch4YqJ2kAyU/0.jpg" alt="Video 1"></a></td>
    </tr>
    <tr><td>We have landed on using Cloud Run, Cloud Memorystore, and Cloud SQL together.</td></tr>
    <tr><td>Is there a solution available from Google that uses these three technologies for a web application?</td></tr>
    <tr><td>If yes, write a Terraform script to deploy the architecture.</td></tr>
    <tr><td>Also, include a tfvars file to declare necessary variables.</td></tr>
    <tr><td>Draw an ASCII flow diagram for the architecture.</td></tr>
    <tr><td>What are some of the pros and cons to using Anthos over GKE for my application?</td></tr>
    
  </tbody>
</table>


```diff
+ Use Duet AI to learn about Google Cloud networking +
```
<!-- Raw HTML Table -->
<table>
  <thead>
    <tr>
      <th>Use Case</th>
      <th>Persona</th>
      <th>Video Demo</th>
      <th>Duet AI Prompts</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="9" style="background-color: #FFD700;">Use Duet AI to learn about Google Cloud networking</td>
      <td rowspan="9">Network Engineer</td>
      <td rowspan="9"><a href="https://www.youtube.com/watch?v=ch4YqJ2kAyU"><img src="https://img.youtube.com/vi/ch4YqJ2kAyU/0.jpg" alt="Video 1"></a></td>
    </tr>
    <tr><td>Explain IP addressing setup in Google Cloud.</td></tr>
    <tr><td>How can I create a network that uses IPv4 and IPv6 addresses?</td></tr>
    <tr><td>Tell me about Cloud Firewalls.</td></tr>
    <tr><td>What are the best practices for a private network?</td></tr>
    <tr><td>How does NAT work in Google Cloud?</td></tr>
    <tr><td>Does Google Cloud use BGP?</td></tr>
    <tr><td>Provide documentation to create a VPC network.</td></tr>
    <tr><td>How do I check my networks in Google Cloud using gcloud CLI commands?</td></tr>
  </tbody>
</table>


___
:ledger: Maintainer: **[Prasanjit Singh](https://www.linkedin.com/in/prasanjit-singh)** 
___

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
<br><sub><sup>
[Digital Millennium Copyright Act (DMCA) Notice](https://github.com/BINPIPE/resources/blob/master/dmca.md) <br>
