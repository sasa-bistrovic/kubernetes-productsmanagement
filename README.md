<p><b><font face="Arial" size="4">Procedure for starting the project:</font></b></p>
<p><b><font face="Arial">1. You need to have docker desktop and minikube installed and kubernetes running.</font></b></p>

<p><b><font face="Arial">2. Clone the project from github.com with the command:</font></b></p>

<p><font face="Arial">$ git clone https://github.com/sasa-bistrovic/kubernetes-productsmanagement.git</font></p>

<p><b><font face="Arial">3. In the "/kubernetes-productsmanagement" folder, run the command:</font></b></p>

<p style="margin-top: 0; margin-bottom: 0"><font face="Arial">minikube config set cpus 6</font></p>
<p style="margin-top: 0; margin-bottom: 0"><font face="Arial">minikube config set memory 6500</font></p>
<p style="margin-top: 0; margin-bottom: 0"><font face="Arial">minikube start</font></p>
<p style="margin-top: 0; margin-bottom: 0"><font face="Arial">kubectl apply -f kubernetes.yaml</font></p>
<p style="margin-top: 0; margin-bottom: 0"><font face="Arial">kubectl get pods</font></p>

<p><b><font face="Arial">4. After running the containers inside kubernetes run the command:</font></b></p>

<p style="margin-top: 0; margin-bottom: 0"><font face="Arial">minikube tunnel</font></p>

<p><b><font face="Arial">5. Here is picture from productsmanagement URL "http://localhost:5050":</font></b></p>

<font face="Arial">

<img src="https://github.com/sasa-bistrovic/kubernetes-productsmanagement/blob/main/ProductsManagement-1.png"></img>

</font>