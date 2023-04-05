{
    "EKSCluster": {
       "Type": "AWS::EKS::Cluster",
       "Properties": {
          "Name": "Dgod",
          "Version": "1.20",
          "RoleArn": "arn:aws:iam::012345678910:role/eks-service-role-AWSServiceRoleForAmazonEKS-EXAMPLEBQ4PI",
          "ResourcesVpcConfig": {
             "SecurityGroupIds": [
                "sg-6979fe18"
             ],
             "SubnetIds": [
                "subnet-6782e71e",
                "subnet-e7e761ac"
             ],
             "EndpointPublicAccess": false,
             "EndpointPrivateAccess": true,
             "PublicAccessCidrs": [
                "1.1.1.2/32"
             ]
          },
          "Logging": {
             "ClusterLogging": {
                "EnabledTypes": [
                   {
                      "Type": "api"
                   },
                   {
                      "Type": "audit"
                   }
                ]
             }
          },
          "Tags": [
             {
                "Key": "key",
                "Value": "val"
             }
          ]
       }
    }
 }
