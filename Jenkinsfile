dpipeline {
     agent any
     parameters {
         string(name: 'VpcCIDR', defaultValue: '10.0.0.0/16', description: 'VPC cidr block' )
     }    
     stages {
         stage('Submit Stack') {
         steps {
         sh "aws cloudformation create-stack  --template-body file://VPC.yaml --region 'us-east-2' --
           }
          }
         }         
         }
