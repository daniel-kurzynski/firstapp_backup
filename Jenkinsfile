#!/usr/bin/env groovy 

node {
    deleteDir()
    sh "git clone --depth 1 https://github.com/SAP/cloud-s4-sdk-pipeline.git -b v11 pipelines"
    load './pipelines/s4sdk-pipeline.groovy'
}
