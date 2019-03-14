# gx-eks-demo
## amazon-eks-nodegroup-launch_template

Use this YAML file to create an EKS node group with different Instance Types(for example, m5.large, c5.large) and Purchase options(On demand or/and Spot).

### How To
1. Create a CloudFormation Stack, use this YAML file as template
2. Fill in the Stack name and parameters
    - OnDemandBaseCapacity: Describe the number of base On Demand instances for your worker nodes.
    - OnDemandPercentageAboveBaseCapacity: Describe the On Demand instance percentage for your worker nodes besides base ones. 
    - InstanceTypeOverride: Describe the instance types for your worker nodes.
    For detailed information, please refer to https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-autoscaling-autoscalinggroup-instancesdistribution.html 
    
