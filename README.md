<h1>GitOps Pipeline for Kubernetes using ArgoCD</h1>
<h3>Technologies: Kubernetes, ArgoCD, Git, GitHub, WSL (Ubuntu)</h3>
<p>Implemented a GitOps-based Continuous Deployment (CD) pipeline using ArgoCD on Kubernetes (Minikube) within a WSL (Ubuntu) environment, replacing manual deployment workflows.</p>

<p>Configured GitHub as the single source of truth to manage Kubernetes manifests, ensuring cluster state consistency and version-controlled infrastructure.</p>

<p>Enabled automated sync, self-healing, and prune features in ArgoCD for drift detection, along with automatic namespace creation and application monitoring.</p>

<h3>Architecture</h3>

<img width="1456" height="735" alt="GitOps" src="https://github.com/user-attachments/assets/2c7a6579-49f5-498a-8c2c-7d88ac48fe12" />

<h3>Demo</h3>

<img width="1453" height="592" alt="2" src="https://github.com/user-attachments/assets/22f3de8e-f1e6-432f-9bf8-e2daeb0f04e8" />
</br></br>
<img width="1206" height="283" alt="3-password" src="https://github.com/user-attachments/assets/87020c6e-7e34-4b66-9699-6749fae072af" />
</br></br>

<img width="1156" height="45" alt="decode password" src="https://github.com/user-attachments/assets/2f293ddc-4339-458d-80b7-fd207c25e2fb" />
</br></br>

<h4>Log in to the ArgoCD GUI</h4>


<img width="1895" height="952" alt="argo" src="https://github.com/user-attachments/assets/8a3e4650-d96e-4789-b72c-b6a2e68626d6" />
</br></br>

<h4>After application.yaml get deployed sync will start</h4>

<img width="901" height="50" alt="app yaml to k8s" src="https://github.com/user-attachments/assets/ede87716-88fb-4a3f-9d13-1e4a48e3fbb2" />
</br></br>


<h4>I face into an error and fixed it.</h4>
</br></br>

<img width="1901" height="922" alt="dh-1" src="https://github.com/user-attachments/assets/0dace6ae-085e-4612-b086-45c93b13239a" />
</br></br>

<img width="1897" height="912" alt="dh 2" src="https://github.com/user-attachments/assets/121b22b0-0d5d-4ff5-8e3a-0cf77484035d" />
</br></br>

<h4>Github commit to reslove issue.</h4>

<img width="1596" height="162" alt="error reslove" src="https://github.com/user-attachments/assets/64d1a3d3-87d0-4828-a95e-abdec7386b26" />
</br></br>


<h4>Auto sync happened</h4>

</br></br>

<img width="1916" height="922" alt="final ds" src="https://github.com/user-attachments/assets/94bbd839-eaa3-4d8f-baed-b8ef414b5c88" />
</br></br>

<img width="1907" height="913" alt="final final" src="https://github.com/user-attachments/assets/eab40b84-d666-413f-8575-04ee24bde323" />
</br></br>

