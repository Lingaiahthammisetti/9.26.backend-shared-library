@Library('jenkins-shared-library')

//create variable of map type and set the values
def configMap =[
    type: "nodejsEKS",
    component: "backend",
    project: "expense"
]

pipelineDecision.decidePipeline(configMap)

 echo "Branch Name: ${env.BRANCH_NAME}"