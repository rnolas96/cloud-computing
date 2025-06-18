This repository serves as the index for my cloud computing projects that  orchestrating both serverless and edge-based pipelines.  
It contains pointers to the private implementation repositories for each phase:

- **Part I - EC2**
  [Private Repo ->] (IN Progress)
- **Part II – FaaS (ECR Approach)**  
  [FaaS Repo](https://github.com/rnolas96/cloud-computing-lambda)  
- **Part III – Edge Computing**  
  [Edge Repo](https://github.com/rnolas96/cloud-computing-edge)  

## Overview
We explore two complementary architectures for face recognition on video frames:
1. A fully managed, serverless pipeline using AWS Lambda and ECR.  
2. An edge-deployed pipeline using AWS IoT Greengrass.  

## Structure
- `part1/` → Contains the PaaS/ECR Lambda code (face detection & recognition).  
- `part2/` → Contains the Greengrass component code and client scripts.  
