@Library('jenkins-shared-library')

//create variable of map type and set the values
def configMap =[
    type: "nodejsEKS",
    component: "backend",
    project: "expense"
]

//pipelineDecision.decidePipeline(configMap)

if( ! env.GIT_BRANCH.contains('main')){
    pipelineDecission.decidePipeline(configMap)
}
else{
    echo "Proceed with CR or NON-PROD pipeline"
}
