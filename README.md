<h1>Kubernetes Configuration Management with Kustomize</h1>

<h2>Description</h2>
<p>
This project demonstrates how to manage multi-environment Kubernetes deployments using Kustomize. It covers creating reusable base configurations and customizing them with environment-specific overlays for staging and production.This approach helps ensure consistent deployments and maintainable YAML files using Kubernetes-native tooling.
</p>

<h2>Tools and Technologies</h2>
<ul>
  <li>Kubernetes</li>
  <li>Kustomize (built into kubectl)</li>
  <li>Kind (Kubernetes-in-Docker)</li>
  <li>YAML configuration files</li>
</ul>

<h2>Project Walk-through</h2>

<p align="center">
Build base deployment, service, configmap, & include it in kustomization.yaml <br />
<img src="https://i.postimg.cc/rw3qbpQk/1.jpg"/>
<br />
<br />
Customize staging overlay with replica patch and debug settings <br/>
<img src="https://i.postimg.cc/YCm5vzf5/2.jpg" />
<br />
<br />
Customize production overlay with probes, limits, and 3 replicas <br/>
<img src="https://i.postimg.cc/4ym8rXWD/3.jpg"/>
<br />
<br />
Deploy both overlays using Kustomize and verify deployments <br/>
<img src="https://i.postimg.cc/y6DCqK36/4.jpg" /> 
<img src="https://i.postimg.cc/13Pdz1Xq/5.jpg" />
<br />
<br />

</p>
