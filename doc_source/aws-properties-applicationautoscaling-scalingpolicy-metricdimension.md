# Application Auto Scaling ScalingPolicy MetricDimension<a name="aws-properties-applicationautoscaling-scalingpolicy-metricdimension"></a>

Use the `MetricDimension` property to specify the dimension of a metric for a target tracking policy in Application Auto Scaling\. The `Dimensions` subproperty of the [Application Auto Scaling ScalingPolicy CustomizedMetricSpecification](aws-properties-applicationautoscaling-scalingpolicy-customizedmetricspecification.md) property contains a list of `MetricDimension` property types\.

## Syntax<a name="aws-properties-applicationautoscaling-scalingpolicy-metricdimension-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-applicationautoscaling-scalingpolicy-metricdimension-syntax.json"></a>

```
{
  "[[ERROR] BAD/MISSING LINK TEXT](#cfn-applicationautoscaling-scalingpolicy-metricdimension-name)" : String,
  "[[ERROR] BAD/MISSING LINK TEXT](#cfn-applicationautoscaling-scalingpolicy-metricdimension-value)" : String
}
```

### YAML<a name="aws-properties-applicationautoscaling-scalingpolicy-metricdimension-syntax.yaml"></a>

```
[[ERROR] BAD/MISSING LINK TEXT](#cfn-applicationautoscaling-scalingpolicy-metricdimension-name): String
[[ERROR] BAD/MISSING LINK TEXT](#cfn-applicationautoscaling-scalingpolicy-metricdimension-value): String
```

## Properties<a name="aws-properties-applicationautoscaling-scalingpolicy-metricdimension-properties"></a>

`Name`  
The name of the dimension\.  
*Required: *Yes  
*Type*: String  
*Update requires*: No interruption

`Value`  
The value of the dimension\.  
*Required: *Yes  
*Type*: String  
*Update requires*: No interruption