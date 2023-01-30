### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the starter code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:


#### final-project-starter.yml
Students have to write the CloudFormation code using this YAML template for building the cloud infrastructure, as required for the project. 

#### server-parameters.json
Students may use a JSON file for increasing the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityProject". 

In YAML code, the `${EnvironmentName}` would be substituted with `UdacityProject` accordingly.

### Load balancer URL
- The load balancer url for this project is: http://udagr-webap-4kgekjw9tt4k-1400563281.us-east-1.elb.amazonaws.com/

### Setup Instruction

#### Mac / Linux

1. Install `aws` command line tool, and configure 
    - aws commandline configuration instruction is provided [here](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart.html)

2. In terminal, starting from the project root folder (after downloading of this project is complete), type the following command

```
make deploy
```

3. To delete stack after running, type the following command (starting in `<PROJECT_ROOT>/project_starter` folder)

```
make delete
```
<br/>
**NOTE:** Please refer to Cloudformation to check delete status as the command may or may not delete entire stack on the first try.

#### Windows

1. Install Ubunutu on WSL2 to be able to run shell script files

2. Enter Ubuntu Terminal by typing `bash` in Command Prompt

3. Install `make` package

2. Install `aws` command line tool, and configure 
    - aws commandline configuration instruction is provided [here](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart.html)

3. In Ubuntu Terminal, starting from the project root folder (after downloading of this project is complete), type the following command

```
make deploy
```

4. To delete stack after running, type the following command (starting in `<PROJECT_ROOT>/project_starter` folder)

```
make delete
```
<br/>
**NOTE:** Please refer to Cloudformation to check delete status as the command may or may not delete entire stack on the first try.