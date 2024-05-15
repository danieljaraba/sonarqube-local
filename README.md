# sonarqube-local

The following project shows a simple way to deploy SonarQube using Docker and analyze a local repository of code.

## Installation

1. Run the Docker container with a volume:
   ```
   docker run -d --name sonarqube -p 9000:9000 -v sonarqube_data:/opt/sonarqube/data sonarqube
   ```
2. Wait for the container to complete the initialization and log in into SonarQube dashboard.
   ![image](https://github.com/danieljaraba/sonarqube-local/assets/69940328/eff35981-e31a-4f0b-88d0-ee44abd9d5cd)
3. Create a local project in SonarQube and select the baseline to analyze.
   ![image](https://github.com/danieljaraba/sonarqube-local/assets/69940328/fc035feb-987f-45be-b442-5c1756077988)
   ![image](https://github.com/danieljaraba/sonarqube-local/assets/69940328/a7e5fa7f-1b55-431f-8afb-048c703b7c30)
4. Choose the analysis method (in our case locally).
   ![image](https://github.com/danieljaraba/sonarqube-local/assets/69940328/da48915d-439d-410d-8aa3-3477a6ddfb9e)
5. Provide a token.
   ![image](https://github.com/danieljaraba/sonarqube-local/assets/69940328/f4d6cabb-ff68-466b-ab7a-ca7e90417f31)
6. Select the type of project and follow the steps to analyze.
   ![image](https://github.com/danieljaraba/sonarqube-local/assets/69940328/5d328737-3c17-4b53-9eef-7ff9690edf9a)
   ![image](https://github.com/danieljaraba/sonarqube-local/assets/69940328/087dad19-fc0f-426c-97a3-74798fbccba3)
7. Wait to finish the analyze and review the results.
   ![image](https://github.com/danieljaraba/sonarqube-local/assets/69940328/765bc2ec-6367-4388-b94c-a7d3ed9b6729)


