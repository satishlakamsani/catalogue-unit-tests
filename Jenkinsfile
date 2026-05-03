def configMap = [
    project: "roboshop",
    component: "catalogue"
]
//add printing
echo "Triggering the library pipeline"

if ( env.BRANCH_NAME.equalsIgnoreCase('main') ){
    echo "checking later"
}
else{
    nodeJSEKSPipeline(configMap)
}