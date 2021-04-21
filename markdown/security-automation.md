<!-- .slide: data-background-image="images/RH_NewBrand_Background.png" -->
## DevOps Culture <!-- {_class="course-title"} -->
### Security and Testing Automation <!-- {_class="title-color"} -->
DO250 <!-- {_class="title-color"} -->



<!-- .slide: id="continuous-integration" -->
## Security and Testing Automation



### Security and Testing Automation
Security Automation helps to limit the risk of cyber threats and software vulnerabilities that could negatively impact the business while simultaneously minimizing negative impacts to service reliability and stability.



### Security and Testing Automation
#### _Who is It for?_
* Organizations with infrequent deployments due to monthly security evaluations
* Newly developed software is frequently rejected by security or quality assurance
* The same type of security incidents occur repeatedly, due to inconsistent verification of software settings or configuration
* Organization having difficulty passing software compliance audits



### Security and Testing Automation
#### Type
* **Pre-commit checks**: Pre-commit checks are tests that run just before a developer commits changes
* **Static Application Security Testing (SAST)**: SAST tests analyze application source code to find the most common software security vulnerabilities
* **Software Composition Analysis (SCA)**: Identifies any known vulnerabilities for imported components
* **Dynamic Application Security Testing (DAST)**: Security tests that search for vulnerabilities by interacting with the running application



### Security and Testing Automation
#### Type
* **Interactive Application Security Testing (IAST)**: IAST is a hybrid testing approach that combines SAST and DAST
* **Fuzz Testing**: Fuzz tests provide invalid, unexpected, random data to a running application and monitor for changes to the application stability or reliability
* **Application Monitoring and Alerting**: Automates monitoring of application telemetry, sending alerts when specific conditions are reached.
* **Penetration Testing**: A set of simulations, or authorized attempts, to gain access to a system by finding and exploiting a vulnerability



### What's it Look Like?
![Jenkins](images/security-pipeline-ex.svg)



<!-- .slide: id="pre-attack-pipelines-summary"-->
## Summary
#### Wrap-up
* **Security and Testing Automation**: Integrate several changes into a shared repo and rely heavily on testing to make sure that the changes and commits works and have passed all (unit testing / code quality / code conduct).
* **Continuous Delivery**: The goal is to have a working artifact that's ready to be deployed at any time. It relies on testing and automation to make sure that it has passed all functional tests and can be Manually deployed (push button).
* **Continuous Deployment/Release**: One step further now that we are sure that this is ready to deploy to production then we can rely on features toggle, dark launches or other deployment strategy to promote to other critical environments asap using these techniques for the new features/fixes won't risk the operation.


