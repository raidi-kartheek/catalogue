// @Library('jenkins-shared-library') _

// def configMap = [
//     project: "roboshop",
//     component: "catalogue"
// ]

// // if branch is not equal to main, then run CI pipeline
// if ( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){
//     nodeJSEKSPipeline(configMap)
// }
// else {
//     echo "Please follow the CR process"
// }

@Library('jenkins-shared-library') _

def configMap = [
    project: "roboshop",
    component: "catalogue"
]
if (env.BRANCH_NAME.equalsIgnoreCase('main')){
    echo "We will deal later"
}
else {
    nodeJSEKSPipeline(configMap)
}