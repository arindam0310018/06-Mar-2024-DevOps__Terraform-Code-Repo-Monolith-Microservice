# Terraform Code Repository: Monolith or Microservice Approach:-

Greetings to my fellow Technology Advocates and Specialists.

In this Session, I will explain __Terraform code repository structure: Monolith vs Microservice.__

| __SPECIAL NOTE:-__ |
| --------- |
| I thank @pwd9000 and @anandarbone for collaborating. Though I am publishing this Article, but both of them have the equal rights to republish and repost. |

| __CONSIDERATIONS:-__ |
| --------- |
| For the purpose of this article, I/We have considered below:- |

| __#__ | __CATEGORY__ | __VALUE__ |
| --------- | --------- | --------- |
| 1. | Cloud Platform | __Azure__ |
| 2. | Devops Platform | __Azure Devops__ |
| 3. | Source control | __Azure Git__ |
| 4. | Pipelines | __Azure Devops Pipelines__ |
| 5. | IaC  | __Terraform__ |
| 6. | Code Structure | __Modules Based__ | 

| What is Monolith based code repository in Terraform ? |
| --------- |
| 1. In simple terms, it means one repository under Azure DevOps Project with multiple folders. |
| 2. Each folder contains Terraform Module per Azure Service. |
| 3. Reference screenshot follows below:- |
| ![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/3e8ydzgzchqr94etinwy.jpg) |

| __Monolith based code repository problem statements:-__ |
| --------- |
| 1. Each time the Pipeline runs, it checks out all codes. | 
| 2. Pipeline execution time increases gradually. |
| 3. Size of the artifacts increases gradually . |
| 4. Avoid Human Error while contributing. |

| What is Microservice based code repository in Terraform ? |
| --------- |
| 1. In simple terms, it means multiple repositories under Azure DevOps Project. |
| 2. Each repository contains Terraform Module per Azure Service. | 
| 3. Reference screenshot follows below:- |
| ![3](https://github.com/arindam0310018/06-Mar-2024-DevOps__Terraform-Code-Repo-Monolith-Microservice/assets/29681063/dd6aa83f-fb88-4158-84cb-21acb7bf5473) |

All the above identified problem statements in Monolith Code Repository is resolved with Microservice based code repository.

| __Mitigating Monolith based code repository problem statements with Microservice based code repository:-__ |
| --------- |
| 1. Each time the Pipeline runs, it checks out only the relevant repositories. | 
| 2. Pipeline execution is fast/not impacted because it checks out only the relevant repositories. |
| 3. Size of the artifacts is way small and the increase is not even noticed because it checks out only the relevant repositories |
| 4. Chances of Human Error is on the lower side since contributor works on specific repositories. |

__Hope You Enjoyed the Session!!!__

__Stay Safe | Keep Learning | Spread Knowledge__
